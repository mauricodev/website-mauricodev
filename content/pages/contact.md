---
title: "Hello! \U0001F44B"
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Thank you very much for taking the time to see my work. If you want you
      can leave me a message below or just email me directly at
      <mauricodev@gmail.com>.


      Have a nice day!
    form_id: contactForm
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
        default_value: Please select (Optional)
        options:
          - Work together
          - Job Offer
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: I would like to talk...
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Talk with Mauricio Carrasco
      keyName: property
    - name: 'og:description'
      value: The contact page in Mauricodev Website.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Talk with Mauricio Carrasco
    - name: 'twitter:description'
      value: The contact page in Mauricodev Website.
layout: advanced
---
