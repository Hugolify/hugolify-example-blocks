---
isPage: true
draft: false
title: Grid
description: Add comparison section with prices, arguments and CTA.
icon: layout-grid
hero:
  surtitle: Block comparison
  title: Layout grid
  text: Add comparison section with prices, arguments and CTA.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/comparison/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/comparison/grid.md
      blank: true
      link: true
  ui:
    align: center
    theme: light
blocks:
  - type: comparison
    ui:
      grid: container
    heading:
      surtitle: Grid container / 3 items
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      grid: container
    heading:
      surtitle: Grid container / 2 items
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      align: center
      grid: container
    heading:
      surtitle: Grid container / align center / 2 items
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      align: end
      grid: container
    heading:
      surtitle: Grid container / align end
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: accent
    heading:
      surtitle: Grid container / Theme accent
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: light
    heading:
      surtitle: Grid container / Theme light
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: highlight
    heading:
      surtitle: Grid container / Theme highlight
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: neutral
    heading:
      surtitle: Grid container / Theme neutral
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: black
    heading:
      surtitle: Grid container / Theme black
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit

  - type: comparison
    ui:
      grid: container
      theme: white
    heading:
      surtitle: Grid container / Theme white
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        arguments:
          - text: Lorem ipsum dolor
          - text: Praesent condimentum nibh erat
          - text: Vestibulum ex metus
          - text: Consectetur adipiscing elit
---
