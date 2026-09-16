---
isPage: true
draft: false
title: Scrollsnap
description: Pushes grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Block pushes
  title: Layout scrollsnap
  text: Pushes grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/pushes/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/pushes/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: pushes
    ui:
      grid: container
      column: 3
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand)
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
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
      text: "Object form, front matter only: the CMS never writes nav nor pagination. Set that site-wide instead with `blocks.pushes.scrollsnap.nav` (pointer) and `blocks.pushes.scrollsnap.pagination` (true) — each key is read on its own, so a block keeps overriding its breakpoint alone."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 4
      scrollsnap:
        breakpoint: lg
        pagination: pointer
    heading:
      surtitle: Grid container / Column 4 / Breakpoint lg / Pagination pointer
      title: Lorem ipsum dolor sit amet.
      text: "Object form, front matter only: the CMS never writes pagination. Set that site-wide instead with `blocks.pushes.scrollsnap.pagination` (pointer) — each key is read on its own, so a block keeps overriding its breakpoint alone."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: light
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme light
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: highlight
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: accent
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: dark
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: neutral
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: black
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme black
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 3
      theme: white
      scrollsnap: md
    heading:
      surtitle: Grid container / Column 3 / Breakpoint md (shorthand) / Theme white
      title: Lorem ipsum dolor sit amet.
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items:
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - ui:
          card: true
          offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
