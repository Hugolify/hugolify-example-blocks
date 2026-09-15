---
isPage: true
draft: false
title: Form
description: Add form
icon: text-cursor-input
hero:
  surtitle: Blocks
  title: Block form
  text: Add form (connect with netlify), input, textarea and select available. 4 widths available.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/form/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/form.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: form
    ui:
      grid: small
      offset: center
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
  - type: form
    ui:
      grid: medium
      offset: center
    heading:
      surtitle: Grid medium / Offset center
    name: contact
    submit: Send message
    items:
      - type: text
        name: firstname
        label: Firstname
        placeholder: John
        autocomplete: given-name
        required: true
      - type: text
        name: lastname
        label: Lastname
        placeholder: Doe
        autocomplete: familly-name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        full: true
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
  - type: form
    ui:
      grid: large
      offset: center
    name: contact
    submit: Send message
    heading:
      surtitle: Grid large / Offset center / All field types
      title: Lorem ipsum dolor sit amet.
      text: Semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: number
        name: number
        label: Number
        required: false
      - type: url
        name: url
        label: URL
        required: false
      - type: date
        name: date
        label: Date
        required: false
      - type: time
        name: time
        label: Time
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: checkbox
        name: checkbox
        label: Checkbox - Semper urna enim
        required: false
      - type: switch
        name: checkbox
        label: Switch
        required: false
      - type: radio
        name: radio
        label: Radio - Viverra faucibus tellus bibendum sed
        required: false
      - type: range
        name: range
        label: Range
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
      - type: text
        name: readonly
        label: Read only
        value: Read only
        readonly: true
      - type: file
        name: file
        label: File
  - type: form
    ui:
      grid: large
      offset: center
    name: contact
    submit: Send message
    heading:
      surtitle: Grid large / Offset center / Disabled fields
      title: Lorem ipsum dolor sit amet.
      text: Semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        disabled: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        disabled: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        disabled: true
      - type: number
        name: number
        label: Number
        disabled: true
      - type: url
        name: url
        label: URL
        disabled: true
      - type: date
        name: date
        label: Date
        disabled: true
      - type: time
        name: time
        label: Time
        disabled: true
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        disabled: true
      - type: checkbox
        name: checkbox
        label: Checkbox - Semper urna enim
        disabled: true
      - type: switch
        name: checkbox
        label: Switch
        disabled: true
      - type: radio
        name: radio
        label: Radio - Viverra faucibus tellus bibendum sed
        disabled: true
      - type: range
        name: range
        label: Range
        disabled: true
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        disabled: true
      - type: file
        name: file
        label: File
        disabled: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: light
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme light
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: highlight
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: accent
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: dark
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: neutral
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: black
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme black
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true

  - type: form
    ui:
      grid: small
      offset: center
      theme: white
    name: contact
    submit: Send message
    heading:
      surtitle: Grid small / Offset center / Basic fields / Theme white
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
---
