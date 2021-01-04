---
title: Blog
sections:
  - type: hero_section
    title: Blog
    subtitle: ''
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: 'Abonnez vous ! '
    title_align: center
    content: Abonnez-vous à notre newsletter pour ne rien manquer.
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse email
        is_required: true
    submit_label: Envoyer
    padding_top: none
    padding_bottom: none
    has_border: true
    background_color: secondary
template: advanced
---
