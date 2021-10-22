---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Estamos a un click de distancia, déjame conocerte
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Seleccionar
        options:
          - Consulta
          - Empleo
          - Comentario
          - Otro asunto
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena la información enviada y que puedo ser contactado.
    submit_label: Enviar mensaje
seo:
  title: Contacto - Daniel González
  description: Estamos a un click de distancia - contáctame
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contacto
      keyName: property
    - name: 'og:description'
      value: Estamos a un click de distancia - contáctame
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contacto
    - name: 'twitter:description'
      value: Estamos a un click de distancia - contáctame
layout: advanced
---
