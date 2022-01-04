---
title: Home
sections:
  - type: hero_section
    title: David Fotógrafo
    subtitle: >-
      Fotógrafo urbano y de moda, colaborando con grandes empresas textiles y publicitarias realizando fotos para catálogos y de
 viajes, con experiencia en manejo de modelos e iluminación. 
 Participaciones en varias exposiciones a nivel nacional en fotografía artistica. 

    actions:
      - label: Contáctame
        url: /contact
        style: primary
    image: images/hero.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: grid_section
    title: Cliente y Empresas
    subtitle: He trabajado con
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Logo 1
        image_align: center
      - image: images/logo-2.svg
        image_alt: Logo 2
        image_align: center
      - image: images/logo-3.svg
        image_alt: Logo 3
        image_align: center
      - image: images/logo-4.svg
        image_alt: Logo 4
        image_align: center
      - image: images/logo-5.svg
        image_alt: Logo 5
        image_align: center
      - image: images/logo-6.svg
        image_alt: Logo 6
        image_align: center
      - image: images/logo-7.svg
        image_alt: Logo 7
        image_align: center
      - image: images/logo-8.svg
        image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: features_section
    title: Mis Servicios
    subtitle: ¿Qué es lo que hago?
    features:
      - title: Fotógrafo de Modas
        subtitle: 'Moda y catalogos'
        content: >-
          Fotografía de prensa, en eventos de moda, desfiles, eventos sociales, creación de catalogos para ropa urbana, vestido de baño, ropa interior. 
        actions:
          - label: Trabajos realizados
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-1.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Fotografía Artística
        subtitle: 'Sensualidad, empoderamiento, autoestima'
        content: >-
          Fotografía en artes finas, expresando la belleza y sensualidad del cuerpo femenino, para modelos o mujeres que simplemente quieren verse sensuales y recobrar la confianza en sí mismas. 
        actions:
          - label: Saber más
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-2.svg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Fotógrafo de viajes 
        subtitle: 'Promoción de lugares turísticos, hoteles y restaurantes'
        content: >-
          Fotografía de lugares vacacionales, airbnb, fincas u hoteles y lugares a promocionar. 
        actions:
          - label: Mira mis viajes
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Testimonios
    subtitle: Lo que mis clientes dicen
    grid_items:
      - content: >-
          David es un gran fotógrafo, super profesional y respetuoso con una perspectiva distinta de las cosas.


          **Anna Suarez,** *RaveStore, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >-
          David realmente entiende mis necesidades y sabe sacar lo mejor de mi haciendo que todo fluya. Estoy muy satisfecha.


          **Maria Alejandra Velez,** *Modelo*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Trabajar con David es muy agradable, entiende las ideas y lo que la marca requiere proyectar.


          **Elena Jaramillo,** *SunBath Tienda*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Me encanta la sutilesa con la que todo surge, me siento en confianza y disfruto de cada sesion con David.

          **Camila A,** *Cliente*
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: |
      ## Hablemos

      Si quieres mas información sobre mis servicios no dudes en escribirme.
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
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario guarda mi información para poder ser
          contactado.
        is_required: true
    submit_label: Enviar
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
