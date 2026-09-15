---
isPage: true
draft: false
title: Scrollsnap
description: Latest grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Block latest
  title: Layout scrollsnap
  text: Latest grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/latest/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/latest/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: latest
    ui:
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand)

  - type: latest
    ui:
      scrollsnap:
        breakpoint: all
        nav: pointer
        pagination: true
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint all / Nav pointer / Pagination true

  - type: latest
    ui:
      scrollsnap:
        breakpoint: lg
        pagination: pointer
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint lg / Pagination pointer

  - type: latest
    ui:
      scrollsnap: false
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint none

  - type: latest
    ui:
      theme: light
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme light

  - type: latest
    ui:
      theme: highlight
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme highlight

  - type: latest
    ui:
      theme: accent
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme accent

  - type: latest
    ui:
      theme: dark
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme dark

  - type: latest
    ui:
      theme: neutral
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme neutral

  - type: latest
    ui:
      theme: black
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme black

  - type: latest
    ui:
      theme: white
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme white
---
