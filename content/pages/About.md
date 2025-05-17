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
        url: 'https://www.facebook.com/WellsboroArtClub/'
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Our Links
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Registration for our Annual Plein Air Festival
        subtitle: Pre-Register
        actions:
          - type: Button
            label: Register
            altText: ''
            url: /
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
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
        title: Our Vendor Application
        subtitle: An Application for Vendors who want a spot on The Green
        actions:
          - type: Button
            label: Vendors
            altText: ''
            url: >-
              https://form.123formbuilder.com/6829848/vendor-application-form?fbclid=IwY2xjawKHEo5leHRuA2FlbQIxMABicmlkETFpYldsVVpQZ2dQaW5RTmx6AR4yiNAgGz7bXY8_gDhX_hVJgbl8Za61vV0LBiLJW6OjqsLlS2kmlzLwrsksag_aem_k72Cugxl_9auZGHIqZ1b
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: The Plein Air Painters of Pennsylvania
        subtitle: 'A Facebook page Dedicated to Plein Air '
        actions:
          - type: Button
            label: Facebook
            altText: ''
            url: '/https://www.facebook.com/groups/1807989056040803/'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Six Keys to Painting Trees with Character and Dimension
        tagline: ''
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          type: ImageBlock
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    elementId: Our Links
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
