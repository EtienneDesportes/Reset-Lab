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
        default_value: Quel Modèle MacBook ?
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
        default_value: Your message
    submit_label: Envoyer demande
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image_opacity: 10
    background_image: images/successful-cabbage.png
template: advanced
---
