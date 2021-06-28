---
title: 'Search Tickets'
form:
  name: search-tickets
  validation: loose
  fields:
    ticket:
        label: Ticket ID
        placeholder: 'Enter your ticket ID'
        type: text
        classes: mb-3
        validate:
            required: true
    lastname:
        type: honeypot
#    g-recaptcha-response:
#        label: Captcha
#        type: captcha
#        recaptcha_not_validated: 'Captcha not valid!'
  buttons:
      submit:
        type: submit
        value: Submit
        classes: btn btn-primary
  process:
#      captcha: true
      redirect: "/view-ticket/id:{{ form.value.ticket }}"
---

