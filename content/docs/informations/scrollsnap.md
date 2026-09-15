---
isPage: true
draft: false
title: Scrollsnap
description: Informations grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Block informations
  title: Layout scrollsnap
  text: Informations grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/informations/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/informations/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: informations
    ui:
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand)
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
      scrollsnap:
        breakpoint: all
        nav: pointer
        pagination: true
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint all / Nav pointer / Pagination true
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
      scrollsnap:
        breakpoint: lg
        pagination: pointer
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint lg / Pagination pointer
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
      scrollsnap: false
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint none
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
      theme: light
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme light
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
      theme: highlight
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme highlight
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
      theme: accent
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme accent
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
      theme: dark
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme dark
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
      theme: neutral
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme neutral
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
      theme: black
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme black
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
      theme: white
      scrollsnap: md
      grid: container
      column: 4
    heading:
      surtitle: Grid container / Column 4 / With icons / Breakpoint md (shorthand) / Theme white
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
---
