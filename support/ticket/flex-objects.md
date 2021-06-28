---
title: Tickets
permissions:
    inherit: true
access:
    site.login: true
    admin.login: true
flex:
    directory: tickets
    collection:
        title: '{{ directory.title }}'
        layout: default
        object:
            layout: list-default
    object:
        title: 'Ticket: {{ object.name }}'
        layout: default
visible: false
---

Hello