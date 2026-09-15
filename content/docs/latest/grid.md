---
isPage: true
draft: false
title: Grid
description: Add latest items section (posts, projects, publications, casestudies…).
icon: layout-grid
hero:
  surtitle: Block latest
  title: Layout grid
  text: Add latest items section (posts, projects, publications, casestudies…).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/latest/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/latest/grid.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: latest
    ui:
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts

  - type: latest
    ui:
      grid: container
      theme: light
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme light

  - type: latest
    ui:
      grid: container
      theme: highlight
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme highlight

  - type: latest
    ui:
      grid: container
      theme: accent
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme accent

  - type: latest
    ui:
      grid: container
      theme: dark
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme dark

  - type: latest
    ui:
      grid: container
      theme: neutral
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme neutral

  - type: latest
    ui:
      grid: container
      theme: black
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme black

  - type: latest
    ui:
      grid: container
      theme: white
    section: posts
    heading:
      surtitle: Grid container / Posts / Theme white
---
