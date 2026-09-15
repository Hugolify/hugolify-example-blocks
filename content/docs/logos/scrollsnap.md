---
isPage: true
draft: false
title: Scrollsnap
description: Logos grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Block logos
  title: Layout scrollsnap
  text: Logos grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/logos/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/logos/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: logos
    ui:
      grid: container
      column: 3
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand)
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      scrollsnap:
        breakpoint: all
        nav: pointer
        pagination: true
    heading:
      surtitle: Grid container / Column 3 / Breakpoint all / Nav pointer / Pagination true
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 4
      scrollsnap:
        breakpoint: lg
        pagination: pointer
    heading:
      surtitle: Grid container / Column 4 / Breakpoint lg / Pagination pointer
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      scrollsnap: false
    heading:
      surtitle: Grid container / Column 3 / Breakpoint none
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: light
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme light
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: highlight
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: accent
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: dark
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: neutral
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: black
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme black
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg

  - type: logos
    ui:
      grid: container
      column: 3
      theme: white
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme white
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    items:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
---
