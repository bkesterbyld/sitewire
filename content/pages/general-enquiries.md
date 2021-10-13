---
title: General enquiries
sections:
  - type: hero_section
    title: Get Support
    subtitle: We'll get back to you ASAP
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Support Request?&#xA;&#xA;


      If you need help, please let us know if you are a lender, borrower or
      lender's capital partner. If you're a borrower having trouble with the
      mobile app, please let us know what type of phone you have and provide any
      details you can about the issue you're having.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Borrower
          - Lender
          - Note Buyer
      - input_type: textarea
        name: Any details to share or questions we can answer?
        label: Any details to share or questions we can answer?
        default_value: Your message
        is_required: false
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Contact Sitewire
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
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
