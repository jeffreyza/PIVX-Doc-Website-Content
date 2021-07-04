---
title: 'View Ticket'
cache_enable: false
---

### I Know, It's A Work in Progress

Sample test links:  
* Valid ticket: https://nuduvi.com/support/view-ticket/id:6053b46209a6b0103deb591d16b94e65  
* Invalid ticket: https://nuduvi.com/support/view-ticket/id:jskfljsdlfkjskdfjsdlfkjsdlfj  


{% set flex = grav.get('flex') %}
{% if(uri.param('id')) %}
  {% set ticket = flex.object(uri.param('id'), 'tickets') %}
  {% if ticket %}
    **{{ ticket.name|e }}** wrote _"{{ ticket.summary|e }}"_ with the following message:  
    {{ ticket.message|markdown }}  
  {% else %}
    Oops, invalid ticket id or the ticket has been removed!.
      {% include "forms/form.html.twig" with { form: forms('search-tickets') } %}
  {% endif %}
{% else %}
  {% include "forms/form.html.twig" with { form: forms('search-tickets') } %}
{% endif %}