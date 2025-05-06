---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: "The Wellsboro\_ \_ Art Club"
      color: text-dark
      type: TitleBlock
    subtitle: The heart of The Wellsboro Art Club
    text: |
      A place filled with dedicated Artists of all kinds of Mediums  
    actions:
      - label: Become a Member
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: About
        altText: ''
        url: /About
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/The Wellsboro Art Club.jpg
      altText: The Wellsboro Art Club
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
