---
isPage: true
draft: false
title: List
description: Testimonials stacked as a list, with grid width, offset and themes.
icon: list
hero:
  surtitle: Block testimonials
  title: Layout list
  text: Testimonials stacked as a list, with grid width, offset and themes.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/testimonials/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/testimonials/list.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: testimonials
    ui:
      layout: list
      grid: container
      theme: light
    heading:
      surtitle: Grid container / Theme light
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    ui:
      layout: list
      grid: medium
      offset: center
      theme: accent
    heading:
      surtitle: Grid medium / Offset center / Theme accent
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: testimonials
    ui:
      layout: list
      grid: small
      offset: center
      theme: dark
    heading:
      surtitle: Grid small / Offset center / Theme dark
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: testimonials
    ui:
      layout: list
      grid: container
      theme: highlight
    heading:
      surtitle: Grid container / Theme highlight
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    ui:
      layout: list
      grid: container
      theme: neutral
    heading:
      surtitle: Grid container / Theme neutral
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    ui:
      layout: list
      grid: container
      theme: black
    heading:
      surtitle: Grid container / Theme black
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    ui:
      layout: list
      grid: container
      theme: white
    heading:
      surtitle: Grid container / Theme white
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
---
