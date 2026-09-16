---
isPage: true
draft: false
title: Scrollsnap
description: Comparison grid turning into a horizontal scroll-snap carousel below a breakpoint.
icon: move-horizontal
hero:
  surtitle: Block comparison
  title: Layout scrollsnap
  text: Comparison grid turning into a horizontal scroll-snap carousel below a breakpoint.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/comparison/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/comparison/scrollsnap.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: comparison
    ui:
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand)
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      scrollsnap:
        breakpoint: all
        nav: pointer
        pagination: true
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint all / Nav pointer / Pagination true
      title: Duis nisl odio, blandit vel quam eget
      text: "Object form, front matter only: the CMS never writes nav nor pagination. Set that site-wide instead with `blocks.comparison.scrollsnap.nav` (pointer) and `blocks.comparison.scrollsnap.pagination` (true) — each key is read on its own, so a block keeps overriding its breakpoint alone."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      scrollsnap:
        breakpoint: lg
        pagination: pointer
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint lg / Pagination pointer
      title: Duis nisl odio, blandit vel quam eget
      text: "Object form, front matter only: the CMS never writes pagination. Set that site-wide instead with `blocks.comparison.scrollsnap.pagination` (pointer) — each key is read on its own, so a block keeps overriding its breakpoint alone."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      scrollsnap: false
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint none
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, option Never — `ui.scrollsnap: false`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: light
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme light
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: highlight
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme highlight
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: accent
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme accent
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: dark
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme dark
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: neutral
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme neutral
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: black
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme black
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA

  - type: comparison
    ui:
      theme: white
      scrollsnap: md
      grid: container
    heading:
      surtitle: Grid container / 3 items / Breakpoint md (shorthand) / Theme white
      title: Duis nisl odio, blandit vel quam eget
      text: "Editable in the CMS with the « Horizontal scroll » select, which writes the breakpoint alone — `ui.scrollsnap: md`."
    items: 
      - title: Lorem ipsum dolor
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 39
        arguments:
          - text: Lorem ipsum dolor
            icon: users
          - text: Praesent condimentum nibh erat
            icon: house
          - text: Vestibulum ex metus
            icon: user
          - text: Consectetur adipiscing elit
            icon: mail
        cta:
          url: "#"
          text: CTA
      - title: Consectetur
        text: Vestibulum ex metus, rhoncus non diam vitae.
        badge: Recommended
        is_highlighted: true
        offer:
          price: 99
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
      - title: Aenean commodo
        text: Vestibulum ex metus, rhoncus non diam vitae.
        offer:
          price: 199
        arguments:
          - text: Lorem ipsum dolor
            icon: link
          - text: Praesent condimentum nibh erat
            icon: building
          - text: Vestibulum ex metus
            icon: key
          - text: Consectetur adipiscing elit
            icon: tree-pine
        cta:
          url: "#"
          text: CTA
---
