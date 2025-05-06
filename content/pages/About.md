---
type: PageLayout
title: About
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: The Wellsboro Art Club
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: ''
    actions:
      - type: Button
        label: Our Facebook Page
        url: '/https://www.facebook.com/WellsboroArtClub'
        icon: arrowRight
        iconPosition: right
        style: primary
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Our Links
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    colors: bg-light-fg-dark
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Items on sale
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Faux Fur Throw
        subtitle: $ 88 – $ 176
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: Cotton Knit Throws
        subtitle: $ 44.99 – $ 90
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Chunky Cotton Knit Throw
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: flex-start
      subtitle:
        textAlign: center
slug: About
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
