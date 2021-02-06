---
title: Faireundevis
sections:
  - type: form_section
    content: >
      **DEVIS GRATUIT**<br>


      <p style="text-align: justify;">La réparation est facturée si elle est
      réalisée avec succès. Si elle n'est pas réalisable, uniquement les frais
      d'envoi seront à votre charge.   </p>


      **ENVOI ET RETOUR INCLUS**<br>


      <p style="text-align: justify;">Vous recevez une étiquette d'envoi, avec
      assurance incluse. Votre colis bien sécurisé, il ne vous reste plus qu’à
      coller l’étiquette et le déposer en point relais. </p>


      **GARANTIE 90 JOURS**<br>


      <p style="text-align: justify;">Notre expertise nous permet de vous
      garantir nos interventions pendant 90 jours.</p>
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: faire un devis
    form_action: /envoyer un devis
    form_fields:
      - input_type: text
        name: name
        label: Nom / Prénom
        default_value: 'Votre nom '
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: 'Votre adresse email '
        is_required: true
      - input_type: number
        name: Téléphone
        label: Numéro pour vous joindre
        default_value: Numéro
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: 'Modèle '
        label: Modèle ProduitMachine
        default_value: Sélectionner
        options:
          - MacBook Pro Retina
          - MacBook Pro USB C Touchbar
          - MacBook Air
          - 'MacBook Pro '
          - MacBook
          - Iphone
          - Je ne sais pas
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
          - Récupération de données
          - 'J''en ai aucune idée ! '
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
    background_image: images/perpetual-yam.jpeg
template: advanced
excerpt: Réparer mon MacBook
---
