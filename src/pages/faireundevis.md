---
title: Faireundevis
sections:
  - type: form_section
    content: >
      **DEVIS GRATUIT**<br>


      <p style="text-align: justify;">Nous ne facturons pas de devis. Payer pour
      un premier diagnostic n'a pas de sens d'après nous. Vous payez uniquement
      si votre machine est à nouveau en état de marche.</p>


      **REPARATION AVEC SATISFACTION GARANTIE**


      Vous réglez uniquement le devis si la réparation est réalisée avec succès.
      Pas de mauvaises surprises. Les tarifs vont **de 120 à 430€ TTC**, selon
      la panne et l’âge de votre machine. La facturation se fait toujours après
      réparation.


      **ENVOI ET RETOUR INCLUS**<br>


      <p style="text-align: justify;">Vous recevez une étiquette d'envoi, avec
      assurance incluse. Votre colis bien sécurisé, il ne vous reste plus qu’à
      coller l’étiquette et le déposer en point relais. Vous pouvez aussi
      déposer votre machine à notre atelier si vous êtes sur Brest. </p>


      **GARANTIE 90 JOURS**<br>


      <p style="text-align: justify;">Notre expertise nous permet de vous
      garantir nos interventions pendant 90 jours. Nous avons les outils et
      composants pour assurer une réparation de haute qualité.</p>
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
        default_value: Votre nom / prénom
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: 'Votre adresse email '
        is_required: true
      - input_type: tel
        name: Téléphone
        label: Téléphone
        default_value: Votre numéro
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: 'Modèle '
        label: Modèle à réparer
        default_value: Sélectionner
        options:
          - MacBook Pro Retina
          - MacBook Pro USB C Touchbar
          - MacBook Air
          - 'MacBook Pro '
          - MacBook
          - Iphone
          - Ipad
          - Imac
          - Autres (merci de précisez par message)
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
          - Remplacement Batterie
          - Connecteur cassé
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
seo:
  title: Reset Lab - Faire un devis
  description: >-
    Votre MacBook / Iphone / Ipad / Imac est en panne ? Nous sommes spécialistes
    en réparation de carte-mère. Venez déposer votre machine sur Brest ! 
  robots: []
  extra: []
  type: stackbit_page_meta
---
