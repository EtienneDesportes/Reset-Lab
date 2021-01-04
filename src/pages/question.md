---
title: ''
excerpt: lorem-ipsum
sections:
  - type: form_section
    content: ''
    content_align: left
    form_position: top
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Votre nom ?
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse email ?
        is_required: true
      - input_type: select
        name: Modèle MacBook
        label: Modèle MacBook
        default_value: Sélectionner
        options:
          - MacBook Pro Retina
          - MacBook Pro USB C Touchbar
          - MacBook Air
          - 'MacBook Pro '
          - MacBook
        is_required: true
      - input_type: select
        name: type de pannes
        label: Type de pannes
        default_value: Sélectionner
        options:
          - Dommage liquide
          - Rétro-éclairage
          - 'Problème démarrage '
          - Batterie ne charge pas
          - Ventilateurs soufflent constamment
          - J'en ai aucune idée ! (Et c'est pas un souci)
        is_required: false
        type: form_field
      - input_type: select
        name: Année du modèle
        label: Année du modèle
        default_value: Sélectionner
        options:
          - '2019'
          - '2018'
          - '2017'
          - '2016'
          - '2015'
          - '2014'
          - '2013'
          - '2012'
          - '2011'
          - '2010'
          - '2009'
        is_required: false
        type: form_field
      - input_type: textarea
        name: message
        label: Message
        default_value: Votre message
    submit_label: Envoyer ma demande
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image_opacity: 10
    background_image: images/successful-cabbage.png
    subtitle: Prise de contact sans demande de réparation
    title_align: center
template: advanced
---
