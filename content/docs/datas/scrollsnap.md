---
isPage: true
draft: false
title: Scrollsnap
description: Datas grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Blocks datas
  title: Layout scrollsnap
  text: Datas grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/datas/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/datas/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: datas
    ui:
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand)
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
      scrollsnap:
        breakpoint: all
        nav: pointer
        pagination: true
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint all / Nav pointer / Pagination true
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
      scrollsnap:
        breakpoint: lg
        pagination: pointer
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint lg / Pagination pointer
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
      scrollsnap: false
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint none
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
      theme: light
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme light
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
      theme: highlight
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme highlight
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
      theme: accent
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme accent
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
      theme: dark
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme dark
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
      theme: neutral
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme neutral
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
      theme: black
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme black
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
      theme: white
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand) / Theme white
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
