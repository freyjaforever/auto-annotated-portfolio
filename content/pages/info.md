---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/featured-Image3.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      ## Hello I'm Freyja. I solve your tech problems for cheap. i'm like just a
      girl whos around to answer questions and stuff. 


      And keep your internet presence squeaky clean and presentable.

    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    media:
      type: ImageBlock
      url: /images/Screen Shot 2024-03-04 at 12.02.34 PM.png
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/Untitled.png
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/alan+jergens+decorative+finish+logo+black+flat.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/Hana_Golden_.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/Camp Lee copy.png
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/Screen Shot 2024-09-28 at 9.31.32 AM.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    spacing: 23
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    title: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: Wordpress
      - type: Label
        label: SquareSpace
      - type: Label
        label: Cargo
        url: ''
      - type: Label
        label: HTML5
        url: ''
      - type: Label
        label: SEO
        url: ''
      - type: Label
        label: CSS
        url: ''
      - type: Label
        label: SSL Security
        url: ''
      - type: Label
        label: Adobe Suite
        url: ''
      - type: Label
        label: Blender
        url: ''
      - type: Label
        label: Canva
        url: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.gg/grrg8Wn7'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://instagram.com/freyjaacassi'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        elementId: ''
        styles:
          self:
            textAlign: left
        actions:
          - type: Link
            label: Tiktok
            altText: ''
            url: 'https://www.tiktok.com/@xo__freyja?_t=8q6Ikrjkp4Q&_r=1'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: ''
    title: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      <freyja4evr@gmail.com>
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: 'Let’s talk... '
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - type: EmailFormControl
          name: email-address
          label: Email
          hideLabel: true
          placeholder: your email address here
          width: full
          isRequired: false
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: your message here
          width: full
          isRequired: false
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
