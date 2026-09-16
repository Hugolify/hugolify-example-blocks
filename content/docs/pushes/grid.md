---
isPage: true
draft: false
title: Grid
description: Pushes in a 1 or 2 column grid, with card, darken, offsets and themes.
icon: layout-grid
hero:
  surtitle: Block pushes
  title: Layout grid
  text: Pushes in a 1 or 2 column grid, with card, darken, offsets and themes.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/pushes/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/pushes/grid.md
      blank: true
      link: true
  ui:
    theme: light
blocks:

  - type: pushes
    ui:
      grid: container
      column: 1
    heading:
      surtitle: Grid container / Column 1 / Card / Item offset start
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
    heading:
      surtitle: Grid container / Column 1 / Card / Item offset end
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
    heading:
      surtitle: Grid container / Column 1 / Card / Item offset center
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
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

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset start / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          darken: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset end / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          darken: true
          offset: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset center / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
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

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Item offset start / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Item offset end / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Item offset center / Darken
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
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


  - type: pushes
    ui:
      grid: medium
      column: 1
      offset: center
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset start / Item vertical start
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
          vertical_align: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      column: 1
      offset: center
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset end / Item vertical start
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: end
          vertical_align: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset start / Item vertical end
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
          vertical_align: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Card / Item offset end / Item vertical end
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: end
          vertical_align: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Darken / Item offset start / Item vertical start
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: start
          vertical_align: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Darken / Item offset end / Item vertical start
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: end
          vertical_align: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Darken / Item offset start / Item vertical end
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: start
          vertical_align: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      offset: center
      column: 1
    heading:
      surtitle: Grid medium / Offset center / Column 1 / Darken / Item offset end / Item vertical end
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: false
          darken: true
          offset: end
          vertical_align: end
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
          link: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 2
    heading:
      surtitle: Grid container / Column 2 / Item offset start / Darken
      title: Lorem ipsum dolor sit amet.
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - ui:
          darken: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - ui:
          darken: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
          link: true
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.

  - type: pushes
    ui:
      grid: container
      column: 2
    heading:
      surtitle: Grid container / Column 2 / Card
      title: Lorem ipsum dolor sit amet.
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
          link: true
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.

  - type: pushes
    ui:
      grid: container
      column: 2
    heading:
      surtitle: Grid container / Column 2 / Without image
      title: Lorem ipsum dolor sit amet.
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - ui:
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - ui:
          offset: center
        cta:
          blank: false
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.

  - type: pushes
    ui:
      grid: container
      column: 1
    heading:
      surtitle: Grid container / Column 1 / Card / Video item
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        video:
          mp4: https://57fec860-25f5-48e3-a3f5-d58e0c572935.mdnplay.dev/shared-assets/videos/flower.mp4
          webm: https://57fec860-25f5-48e3-a3f5-d58e0c572935.mdnplay.dev/shared-assets/videos/flower.webm
          autoplay: true
          controls: false
          loop: true

  - type: pushes
    ui:
      grid: container
    heading:
      surtitle: Grid container
      title: Lorem ipsum dolor sit amet.
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - ui:
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.

  - type: pushes
    ui:
      grid: container
      column: 2
    heading:
      surtitle: Grid container / Column 2 / Without image / Custom colors
      title: Lorem ipsum dolor sit amet.
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - ui:
          offset: start
          background_color: '#A90940'
          color: '#FFFFFF'
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - ui:
          offset: center
          background_color: '#56f6bf'
          color: '#000000'
        cta:
          blank: false
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: accent
    heading:
      surtitle: Grid container / Column 1 / Card / Theme accent
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: dark
    heading:
      surtitle: Grid container / Column 1 / Card / Theme dark
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: light
    heading:
      surtitle: Grid container / Column 1 / Card / Theme light
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: full
      column: 1
    heading:
      surtitle: Grid full / Column 1 / Card
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: medium
      column: 1
      offset: center
    heading:
      surtitle: Grid medium / Column 1 / Offset center / Card
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: highlight
    heading:
      surtitle: Grid container / Column 1 / Card / Theme highlight
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: neutral
    heading:
      surtitle: Grid container / Column 1 / Card / Theme neutral
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: black
    heading:
      surtitle: Grid container / Column 1 / Card / Theme black
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: pushes
    ui:
      grid: container
      column: 1
      theme: white
    heading:
      surtitle: Grid container / Column 1 / Card / Theme white
      title: Lorem ipsum dolor sit amet.
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - ui:
          card: true
          offset: start
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
