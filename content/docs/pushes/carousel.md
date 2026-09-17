---
isPage: true
draft: false
title: Carousel
description: Pushes as a Splide carousel, with arrows, pagination and autoplay.
icon: gallery-horizontal-end
hero:
  surtitle: Block pushes
  title: Layout carousel
  text: Pushes as a Splide carousel, with arrows, pagination and autoplay.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/pushes/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/pushes/carousel.md
      blank: true
      link: true
  ui:
    align: center
    theme: light
blocks:
  - type: pushes
    ui:
      layout: carousel
      grid: container
      carousel:
        params:
          autoplay: true
          gap: 3rem
          arrow: true
          pagination: true
          perPage: 2
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid container / Autoplay / 2 per page / Arrows / Pagination
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.

  - type: pushes
    ui:
      layout: carousel
      grid: container
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid container / Arrows / Pagination
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: light
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Theme light / Arrows / Pagination
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: highlight
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: accent
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: dark
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: neutral
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: black
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme black
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''

  - type: pushes
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: white
      carousel:
        params:
          arrow: true
          pagination: true
        responsive:
          - breakpoints: 640
            params:
              arrows: false
              gap: 0
              perPage: 1
    heading:
      surtitle: Grid medium / Offset center / Arrows / Pagination / Theme white
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          darken: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - ui:
          card: true
          offset: center
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
---
