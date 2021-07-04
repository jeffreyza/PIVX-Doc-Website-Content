---
title: 'New Ticket'
form:
    validation: loose
    fields:
        uid:
            type: random
        type:
            type: select
            size: long
            classes: 'fancy my-3'
            label: 'Support Category'
            help: 'Select the best category for your request'
            options:
                default: 'Select A Category'
                wallet: Wallet
                masternode: Masternode
                staking: Staking
        summary:
            label: Summary
            placeholder: 'Summarize your issue'
            type: text
            validate:
                required: true
        name:
            label: Name
            placeholder: 'Enter your first name or handle'
            type: text
            validate:
                required: true
        email:
            label: Email
            placeholder: 'Enter your email address'
            type: email
            validate:
                required: true
        message:
            label: Message
            size: long
            placeholder: 'Enter your message'
            type: textarea
            rows: 10
            style: 'width 600px'
        files:
            type: file
            multiple: true
            destination: '/user/data/flex-objects/tickets.json/{{ form.value.uid|e }}/'
            accept:
                - 'image/*'
                - 'file/txt'
                - 'file/md'
    buttons:
        submit:
            type: submit
            value: Submit
            classes: btn btn-primary
        reset:
            type: reset
            value: Reset
            classes: btn btn-primary
    process:
        ip:
            label: IP Address
        timestamp:
            label: Timestamp
        discord: null
        ticket: null
        #redirect: "/path to/location/{{ form.value.form-nonce }}"
        reset: true
        message: 'Thank you for getting in touch!'
        display: thank-you
---

### New Ticket
For the fastest support, we recomend you join our Discord community.
