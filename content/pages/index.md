---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: This is Ahmad
      color: text-dark
      type: TitleBlock
    subtitle: A Computer Architecture and Machine Learning Enthusiast
    text: >
      I am an Embedded System Designer and a Machine Learning Enthusiast. I
      specialize in developing Embedded Systems, integrating real-time
      processing, and hardware-software co-design, combined with expertise in
      applying machine learning to edge devices for intelligent automation and
      data-driven solutions
    actions:
      - type: Link
        label: LinkedIn
        altText: LinkedIn
        url: 'https://www.linkedin.com/in/ahmad-raza-382700238/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: GitHub
        url: 'https://github.com/Ahmadrazashakir'
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        label: Instagram
        altText: Instagram
        url: 'https://www.instagram.com/ah.mad.raza/'
        showIcon: true
        icon: instagram
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      url: /images/DSC_25222.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Hello there!
      color: text-primary
      type: Badge
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
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Social Media Management
        tagline: Feature 1
        subtitle: Increase your reach
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Business Consulting
        tagline: Feature 2
        subtitle: Be in good company
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Business consulting
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
