---
isPage: true
draft: false
title: Grid
description: Add some cards informations in column. Icon, images and button are available.
icon: layout-grid
hero:
  surtitle: Block informations
  title: Layout grid
  text: Add some cards informations in column. Icon, images and button are available.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/informations/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/informations/grid.md
      blank: true
      link: true
blocks:
  - type: informations
    ui:
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons
      title: 4 columns with icons
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        icon: sun

  - type: informations
    ui:
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / With icons
      title: 3 columns with icons
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy

  - type: informations
    ui:
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons
      title: 4 columns with icons and background
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum

  - type: informations
    ui:
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With images
      title: 4 columns with images
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: large
      column: 4
      ratio: 1
      offset: center
      theme: light
    heading:
      surtitle: Grid large / Column 4 / Ratio 1 / Offset center / Theme light
      title: 4 columns with images
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: medium
      column: 4
      ratio: 1.5
      offset: center
      theme: accent
    heading:
      surtitle: Grid medium / Column 4 / Ratio 1.5 / Offset center / Theme accent
      title: 4 columns with images 
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: full
      column: 4
      theme: dark
    heading:
      surtitle: Grid full / Column 4 / Theme dark
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With logos
      title: 4 columns with logos
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true

  - type: informations
    ui:
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / Mixed media
      title: 4 columns mixed
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum

  - type: informations
    ui:
      grid: full
      column: 4
      theme: highlight
    heading:
      surtitle: Grid full / Column 4 / Theme highlight
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: full
      column: 4
      theme: neutral
    heading:
      surtitle: Grid full / Column 4 / Theme neutral
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: full
      column: 4
      theme: black
    heading:
      surtitle: Grid full / Column 4 / Theme black
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: informations
    ui:
      grid: full
      column: 4
      theme: white
    heading:
      surtitle: Grid full / Column 4 / Theme white
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
