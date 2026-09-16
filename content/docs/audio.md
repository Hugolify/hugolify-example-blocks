---
isPage: true
draft: false
title: Audio
description: Add MP3 or OGG audio section.
icon: audio-lines
hero:
  surtitle: Blocks
  title: Block audio
  text: Add MP3 or OGG audio section.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/audio/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-blocks/refs/heads/main/content/docs/audio.md
      blank: true
      link: true
  ui:
    theme: light
blocks:
  - type: audio
    ui:
      grid: large
      offset: center
      align: start
    heading:
      surtitle: Grid large / Offset center / Align start / Without transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
  - type: audio
    ui:
      grid: large
      offset: center
      align: center
    heading:
      surtitle: Grid large / Offset center / Align center / Without transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
  - type: audio
    ui:
      grid: large
      offset: center
      align: end
    heading:
      surtitle: Grid large / Offset center / Align end / Without transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3

  # Transcription
  - type: audio
    ui:
      grid: container
    heading:
      surtitle: Grid container / With transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.
  - type: audio
    ui:
      grid: container
      align: center
    heading:
      surtitle: Grid container / Align center / With transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.
  - type: audio
    ui:
      grid: container
      align: end
    heading:
      surtitle: Grid container / Align end / With transcription
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.


  - type: audio
    ui:
      grid: container
      theme: accent
    heading:
      surtitle: Grid container / Theme accent
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.
  - type: audio
    ui:
      grid: container
      theme: dark
    heading:
      surtitle: Grid container / Theme dark
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.

  - type: audio
    ui:
      grid: container
      theme: light
    heading:
      surtitle: Grid container / Theme light
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.

  - type: audio
    ui:
      grid: container
      theme: highlight
    heading:
      surtitle: Grid container / Theme highlight
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.

  - type: audio
    ui:
      grid: container
      theme: neutral
    heading:
      surtitle: Grid container / Theme neutral
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.

  - type: audio
    ui:
      grid: container
      theme: black
    heading:
      surtitle: Grid container / Theme black
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.

  - type: audio
    ui:
      grid: container
      theme: white
    heading:
      surtitle: Grid container / Theme white
      title: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    audio:
      mp3: /audios/t-rex-roar.mp3
      transcription: >-
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.
---
