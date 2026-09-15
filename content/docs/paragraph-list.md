---
draft: false
title: Paragraph list
description: Add a list of paragraph in 1 or 2 columns
icon: list-ordered
hero:
  surtitle: Design System
  title: Paragraph list
  ui:
    align: center
    theme: light

blocks:

  # COLUMN 2
  - type: paragraph-list
    ui:
      grid: container
      column: 2
    heading:
      surtitle: Grid container / Column 2
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper. Pellentesque nec nisi nunc.
        ctas:
          - url: /
            text: CTA text
            link: true
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie. Etiam dictum dictum
          purus, vitae sagittis urna condimentum quis.
        ctas:
          - url: /
            text: CTA text
            link: true
      - surtitle: Surtitle
        title: Aliquam mattis sapien vitae magna aliquet malesuada.
        text: Pellentesque fringilla eros eu blandit consequat. Nulla nisl ipsum,
          venenatis sit amet risus ut.
      - surtitle: Surtitle
        title: Maecenas velit dolor, volutpat vel laoreet in.
        text: Dictum pellentesque dui, lacinia quis sem.

  # SANS EN-TÊTE DE BLOC — les titres d'items restent en h2
  - type: paragraph-list
    ui:
      grid: medium
      column: 2
      offset: center
    heading:
      surtitle: Grid medium / Offset center / Column 2
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper. Pellentesque nec nisi nunc.
        ctas:
          - url: /
            text: CTA text
            link: true
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie. Etiam dictum dictum
          purus, vitae sagittis urna condimentum quis.
        ctas:
          - url: /
            text: CTA text
            blank: true
            link: true
      - surtitle: Surtitle
        title: Aliquam mattis sapien vitae magna aliquet malesuada.
        text: Pellentesque fringilla eros eu blandit consequat. Nulla nisl ipsum,
          venenatis sit amet risus ut.
      - surtitle: Surtitle
        title: Maecenas velit dolor, volutpat vel laoreet in.
        text: Dictum pellentesque dui, lacinia quis sem.

  # GRID — column 1 (défaut)
  - type: paragraph-list
    ui:
      grid: container
      column: 1
    heading:
      surtitle: Grid container / Column 1
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: >-
          Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper. Pellentesque nec nisi nunc. Fusce commodo vehicula tortor,
          sed convallis purus posuere a.
        ctas:
          - url: /
            text: CTA text
            link: true
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis, nulla neque convallis.
        text: >-
          Sed convallis enim placerat volutpat molestie. Etiam dictum dictum
          purus, vitae sagittis urna condimentum quis.
        ctas:
          - url: /
            text: CTA text
            link: true
  - type: paragraph-list
    ui:
      grid: large
      column: 1
      offset: center
    heading:
      surtitle: Grid large / Offset center / Column 1
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper. Pellentesque nec nisi nunc.
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis, nulla neque convallis.
        text: Sed convallis enim placerat volutpat molestie.
  - type: paragraph-list
    ui:
      grid: medium
      column: 1
      offset: center
    heading:
      surtitle: Grid medium / Offset center / Column 1
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper. Pellentesque nec nisi nunc.
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis, nulla neque convallis.
        text: Sed convallis enim placerat volutpat molestie.
  - type: paragraph-list
    ui:
      grid: small
      column: 1
      offset: center
    heading:
      surtitle: Grid small / Offset center / Column 1
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis, nulla neque convallis.
        text: Sed convallis enim placerat volutpat molestie.

  # ALIGN
  - type: paragraph-list
    ui:
      grid: medium
      offset: center
      align: center
    heading:
      surtitle: Grid medium / Offset center / Align center
      title: Quisque eget magna nec nunc scelerisque
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text

  # HEADING + FOOTING
  - type: paragraph-list
    ui:
      grid: medium
      offset: center
    heading:
      surtitle: Surtitle
      title: Grid medium / Offset center / Heading + footing
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere nec at eros.
        text: Nulla placerat ipsum pulvinar mauris lacinia.
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
    footing:
      ctas:
        - url: /contact/
          text: Nous contacter

  # THEME
  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: light
    heading:
      surtitle: Grid container / Column 2 / Theme light
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true
  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: highlight
    heading:
      surtitle: Grid container / Column 2 / Theme highlight
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true
  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: accent
    heading:
      surtitle: Grid container / Column 2 / Theme accent
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true

  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: dark
    heading:
      surtitle: Grid container / Column 2 / Theme dark
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true

  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: neutral
    heading:
      surtitle: Grid container / Column 2 / Theme neutral
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true

  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: black
    heading:
      surtitle: Grid container / Column 2 / Theme black
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true

  - type: paragraph-list
    ui:
      grid: container
      column: 2
      theme: white
    heading:
      surtitle: Grid container / Column 2 / Theme white
    items:
      - surtitle: Surtitle
        title: Quisque eget magna nec nunc scelerisque posuere.
        text: Nulla placerat ipsum pulvinar mauris lacinia, vel consectetur sem
          ullamcorper.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
      - surtitle: Surtitle
        title: Proin ullamcorper, elit in cursus facilisis.
        text: Sed convallis enim placerat volutpat molestie.
        ctas:
          - url: /
            text: CTA text
            link: true
---
