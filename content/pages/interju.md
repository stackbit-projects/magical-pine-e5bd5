---
title: Home
sections:
  - type: hero_section
    title: Segítsd egy interjúval a jövő szálláshelykezelőjének létrejöttét
    subtitle: >-
      Szoftvereinket a kis szállásadók igényeire szabjuk. Magánszállásadóként
      egy mélyinterjúval segíthetsz, hogy nemsokára egy igazán felhasználóbarát
      és egyszerű megoldás is elérhető legyen.
    content: |
      ####
    actions: []
    align: center
    padding_top: large
    padding_bottom: large
    background_color: none
    background_image: images/hero-background.jpg
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: left center
    media_position: right
    media_width: fifty
  - section_id: foglalomotor-feliratkozas
    title_align: left
    content: >
      ## Jelentkezz interjúra és oldjuk meg együtt a foglalással és
      adminisztrációval kapcsolatos problémákat!


      Résztvevőink életre szóló kedvezményeket kapnak a szoftvereinkből.


      Az interjú online zajlik az általad választott időpontban, és csak a
      szálláshelyeddel kapcsolatos dolgokról beszélgetünk.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: interju-jelentkezes
    form_action: jelentkezes
    form_fields:
      - input_type: text
        name: Név
        label: Név
        options:
          - lorem-ipsum
          - lorem-ipsum
        is_required: false
      - input_type: email
        name: Email cím
        label: Email cím
        options: []
        is_required: true
      - input_type: select
        name: Szálláshely mérete
        default_value: Férőhelyek száma (fő)
        options:
          - 2-6 fő
          - 7-16 fő
          - 16-30 fő
          - 30+
        is_required: false
        label: 'Szálláshelyed mérete (a legnagyobb, ha több van)'
      - input_type: checkbox
        name: Adatkezelési beleegyezés
        label: Elfogadom az adatkezelési nyilatkozatot.
        default_value: lorem-ipsum
        options: []
        is_required: true
    submit_label: Jelentkezés
    align_vert: middle
    padding_top: large
    padding_bottom: large
    has_border: false
    background_color: primary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
seo:
  title: Stackbit Event Theme
  description: The preview of the Event theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Event Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Event theme
      keyName: property
    - name: 'og:image'
      value: images/feature-3.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Event Theme
    - name: 'twitter:description'
      value: The preview of the Event theme
    - name: 'twitter:image'
      value: images/feature-3.jpg
      relativeUrl: true
layout: advanced
---
