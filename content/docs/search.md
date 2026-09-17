---
isPage: true
draft: false
title: Search
description: Add search section
icon: search
hero:
  surtitle: Blocks
  title: Block search
  text: Add search section.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/search/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/search.md
      blank: true
      link: true
  ui:
    align: center
    theme: light

blocks:
  - type: alert
    ui:
      grid: container
    state: danger
    text: Can not use in docs section because there is already search in header
  - type: search
    ui:
      grid: container
    heading:
      surtitle: Grid container
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: light
    heading:
      surtitle: Grid container / Theme light
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: highlight
    heading:
      surtitle: Grid container / Theme highlight
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: accent
    heading:
      surtitle: Grid container / Theme accent
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: dark
    heading:
      surtitle: Grid container / Theme dark
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: neutral
    heading:
      surtitle: Grid container / Theme neutral
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: black
    heading:
      surtitle: Grid container / Theme black
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

  - type: search
    ui:
      grid: container
      theme: white
    heading:
      surtitle: Grid container / Theme white
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
---
