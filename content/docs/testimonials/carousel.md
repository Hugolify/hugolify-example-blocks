---
isPage: true
draft: false
title: Carousel
description: Testimonials as a looping Splide carousel with centered focus.
icon: gallery-horizontal-end
hero:
  surtitle: Block testimonials
  title: Layout carousel
  text: Testimonials as a looping Splide carousel with centered focus.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/testimonials/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/testimonials/carousel.md
      blank: true
      link: true
blocks:
  - type: testimonials
    ui:
      layout: carousel
      grid: container
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay
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
      layout: carousel
      grid: container
      theme: light
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme light
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
      layout: carousel
      grid: container
      theme: highlight
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme highlight
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
      layout: carousel
      grid: container
      theme: accent
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme accent
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
      layout: carousel
      grid: container
      theme: dark
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme dark
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
      layout: carousel
      grid: container
      theme: neutral
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme neutral
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
      layout: carousel
      grid: container
      theme: black
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme black
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
      layout: carousel
      grid: container
      theme: white
      carousel:
        params:
          type: loop
          focus: center
          perPage: 5
          arrows: false
          autoplay: true
          gap: 1.5rem
          padding: 3rem
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
          - breakpoints: 1440
            params:
              perPage: 4
    heading:
      surtitle: Grid container / 5 per page / Loop / Focus center / Autoplay / Theme white
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
