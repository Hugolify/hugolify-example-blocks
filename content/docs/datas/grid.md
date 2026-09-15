---
isPage: true
draft: false
title: Grid
description: Add some datas in columns (with gauge or not).
icon: layout-grid
hero:
  surtitle: Blocks datas
  title: Layout grid
  text: Add some datas in columns (with gauge or not).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/datas/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/datas/grid.md
      blank: true
      link: true
blocks:
  - type: datas
    ui:
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color
      title: With gauge and automatic color
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: ''
        suffix: '%'
        limit: 100
      - value: 45
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        suffix: '%'
        limit: 100
      - value: 66
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
        suffix: '%'
    show_color: true
    show_gauge: true

  - type: datas
    ui:
      grid: container
      column: 3
      theme: light
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Theme light
      title: With gauge and automatic color
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: ''
        suffix: '%'
        limit: 100
      - value: 45
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        suffix: '%'
        limit: 100
      - value: 66
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
        suffix: '%'
    show_color: true
    show_gauge: true

  - type: datas
    ui:
      grid: full
      column: 4
      theme: dark
    heading:
      surtitle: Grid full / Column 4 / Gauge / Theme dark
      title: With gauge
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
        prefix: '+'
        suffix: '€'
        limit: 1000
      - value: 200000
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        limit: 250000
      - value: 3.5
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
    show_color: false
    show_gauge: true

  - type: datas
    ui:
      grid: large
      column: 3
      theme: accent
    heading:
      surtitle: Grid large / Column 3 / Theme accent
      title: Without gauges
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
        prefix: '+'
        suffix: '€'
        limit: 1000
      - value: 200000
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        limit: 250000
      - value: 3.5
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
    show_color: false
    show_gauge: false

  - type: datas
    ui:
      grid: container
      column: 4
      theme: highlight
    heading:
      surtitle: Grid container / Column 4 / Theme highlight
      title: Without gauges
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
        prefix: '+'
        suffix: '€'
        limit: 1000
      - value: 200000
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        limit: 250000
      - value: 3.5
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
      - value: 390
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
    show_color: false
    show_gauge: false

  - type: datas
    ui:
      grid: container
      column: 3
      theme: neutral
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Theme neutral
      title: With gauge and automatic color
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: ''
        suffix: '%'
        limit: 100
      - value: 45
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        suffix: '%'
        limit: 100
      - value: 66
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
        suffix: '%'
    show_color: true
    show_gauge: true

  - type: datas
    ui:
      grid: container
      column: 3
      theme: black
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Theme black
      title: With gauge and automatic color
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: ''
        suffix: '%'
        limit: 100
      - value: 45
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        suffix: '%'
        limit: 100
      - value: 66
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
        suffix: '%'
    show_color: true
    show_gauge: true

  - type: datas
    ui:
      grid: container
      column: 3
      theme: white
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Theme white
      title: With gauge and automatic color
      text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: ''
        suffix: '%'
        limit: 100
      - value: 45
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
        suffix: '%'
        limit: 100
      - value: 66
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
        suffix: '%'
    show_color: true
    show_gauge: true
---
