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

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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

      text: "Object form, front matter only: the CMS never writes nav nor pagination. Set that site-wide instead with `blocks.latest.scrollsnap.nav` (pointer) and `blocks.latest.scrollsnap.pagination` (true) — each key is read on its own, so a block keeps overriding its breakpoint alone."
  - type: latest
    ui:
      scrollsnap:
        breakpoint: lg
        pagination: pointer
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint lg / Pagination pointer

      text: "Object form, front matter only: the CMS never writes pagination. Set that site-wide instead with `blocks.latest.scrollsnap.pagination` (pointer) — each key is read on its own, so a block keeps overriding its breakpoint alone."
  - type: latest
    ui:
      scrollsnap: false
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint none

      text: "Editable in the CMS with the « Horizontal scroll » select, option Never — `ui.scrollsnap: false`."
  - type: latest
    ui:
      theme: light
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme light

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: highlight
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme highlight

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: accent
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme accent

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: dark
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme dark

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: neutral
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme neutral

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: black
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme black

      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
  - type: latest
    ui:
      theme: white
      scrollsnap: md
      grid: container
    section: posts
    heading:
      surtitle: Grid container / Posts / Breakpoint md (shorthand) / Theme white
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
---
