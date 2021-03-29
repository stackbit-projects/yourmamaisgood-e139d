---
title: General enquiries
sections:
  - type: hero_section
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ### Billing

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.

      ### Privacy

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: FULL NAME
        default_value: Your full name
        is_required: true
      - input_type: email
        name: email
        label: WORK EMAIL
        default_value: Your w
        is_required: true
      - input_type: tel
        name: phone
        label: PHONE NUMBER
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
      - input_type: text
        name: company
        label: COMPANY NAME
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
      - input_type: text
        name: country
        label: COUNTRY
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: client
        options:
          - 'Yes'
          - 'No'
        is_required: false
        type: form_field
        label: ALREADY AN AUREL CLIENT ?
        default_value: Please select...
      - input_type: select
        name: subject
        label: SUBJECT
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: YOUR MESSAGE
        default_value: Your message
    submit_label: Send Message
    align_vert: top
    padding_top: none
    padding_bottom: large
    background_color: none
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
layout: advanced
---
