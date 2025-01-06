---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: >-
      I’m a digital artist, Entrepreneur, and a bunch of other impressive titles
      and buzz words.
    subtitle: >-
      This is my info—I’m sharing it all this with ya’ll to impress you with all
      the hard work I’ve done in the past few years. Once you’re impressed, you
      can continue to scroll down to see more details and credentials about me.
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
        fontStyle: italic
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Link
        label: Learn more
        altText: ''
        url: /abc
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
      - type: Link
        label: Learn more
        altText: ''
        url: /abc
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: logo one
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: logo two
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: logo three
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: logo four
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: logo five
        caption: Caption of the image
        elementId: ''
    colors: colors-a
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
---
