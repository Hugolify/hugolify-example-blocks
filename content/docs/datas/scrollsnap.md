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
      scrollsnap:
        breakpoint: all
        nav: pointer
      grid: medium
      offset: center
      column: 4
    heading:
      surtitle: Grid medium / Column 4 / Scrollsnap all / nav pointer / Without gauges
      title: Maecenas semper urna enim
      text: "Object form, front matter only: the CMS never writes nav. Set that site-wide instead with `blocks.datas.scrollsnap.nav` (pointer) — each key is read on its own, so a block keeps overriding its breakpoint alone."
    items:
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
      - value: 20000
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
      - value: 3.5
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 90
        prefix: '+'
        suffix: '€'
      - value: 200
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
      - value: 3.5
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
        prefix: '+'
        suffix: '€'
        limit: 1000
      - value: 2000
        title: Quisque consectetur
        text: Mauris convallis ante eu nisl iaculis efficitur. Pellentesque vel
          fringilla nunc.
      - value: 3.5
        suffix: 'K'
        prefix: '$'
        title: Morbi placerat erat
        text:
          Proin sagittis faucibus tortor, rutrum facilisis erat volutpat ut. Etiam
          porta sapien eu tellus ornare tincidunt.
        limit: 100
      - text: Maecenas semper urna enim, viverra faucibus tellus bibendum sed
        title: Faucibus
        value: 900
        prefix: '+'
        suffix: '€'
        limit: 1000
      - value: 2000
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
      scrollsnap: md
      grid: container
      column: 3
    heading:
      surtitle: Grid container / Column 3 / Gauge / Color / Breakpoint md (shorthand)
      title: With gauge and automatic color
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Object form, front matter only: the CMS never writes nav nor pagination. Set that site-wide instead with `blocks.datas.scrollsnap.nav` (pointer) and `blocks.datas.scrollsnap.pagination` (true) — each key is read on its own, so a block keeps overriding its breakpoint alone."
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
      text: "Object form, front matter only: the CMS never writes pagination. Set that site-wide instead with `blocks.datas.scrollsnap.pagination` (pointer) — each key is read on its own, so a block keeps overriding its breakpoint alone."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, option Never — `ui.scrollsnap: false`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
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
