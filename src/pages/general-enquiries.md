---
title: ''
sections:
  - type: form_section
    content: >-
      **RÉPARÉ OU REMBOURSÉ**<br>

      <p style="text-align: justify;">Payer pour un devis ou une « recherche de
      panne » nous parait un peu décalé. Notre principe est simple, vous ne
      paierez que si votre Macbook est réparé ! </p>


      **ENVOI ET RETOUR INCLUS**<br>

      <p style="text-align: justify;">Vous recevrez une étiquette transporteur,
      avec assurance incluse. Votre Mac bien emballé, il ne vous reste qu’à
      coller l’étiquette et déposer votre colis en point relais : simplicité,
      rapidité.</p>


      **GARANTIE 180 JOURS**<br>

      <p style="text-align: justify;">On sait exactement ce qu’on fait, comment
      on le fait et d’où viennent nos pièces. C’est pour cela qu’on peut vous
      garantir nos interventions pendant 180 jours.</p>
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
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
template: advanced
---
