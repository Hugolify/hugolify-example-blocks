---
isPage: true
draft: false
title: Carousel
description: Image gallery as a Splide carousel, with ratio and per page settings.
icon: gallery-horizontal-end
hero:
  surtitle: Block gallery
  title: Layout carousel
  text: Image gallery as a Splide carousel, with ratio and per page settings.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/gallery/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/gallery/carousel.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1.75
    heading:
      surtitle: Grid container / Ratio 1.75
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: light
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / Theme light / 4 per page / Autoplay
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: small
      ratio: 2
      offset: center
    heading:
      surtitle: Grid small / Ratio 2 / Offset center
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        legend: Lorem
        credit: Photo de [Anders Jildén](https://unsplash.com/fr/@andersjilden?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) sur [Unsplash](https://unsplash.com/)
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: full
      ratio: .5
      carousel:
        params:
          perPage: 6
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 2
          - breakpoints: 1024
            params:
              perPage: 3
    heading:
      surtitle: Grid full / Ratio 0.5 / 6 per page / Autoplay
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1789480547/tim-stief-dH6IjhWHNQQ-unsplash_u1julm.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: highlight
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: accent
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: dark
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: neutral
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: black
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme black
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: gallery
    ui:
      layout: carousel
      grid: container
      ratio: 1
      theme: white
      carousel:
        params:
          perPage: 4
          arrows: false
          autoplay: true
          gap: 30px
        responsive:
          - breakpoints: 640
            params:
              perPage: 1
          - breakpoints: 1024
            params:
              perPage: 2
          - breakpoints: 1280
            params:
              perPage: 3
    heading:
      surtitle: Grid container / Ratio 1 / 4 per page / Autoplay / Theme white
      title: Lorem ipsum dolor sit amet.
      text: Mauris lobortis pulvinar lectus at semper.
    gallery:
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
