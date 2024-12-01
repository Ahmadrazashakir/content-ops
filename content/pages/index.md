---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: My name is Ahmad
      color: text-dark
      type: TitleBlock
    subtitle: Computer Architecture and Machine Learning Enthusiast
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
        url: '/https://www.linkedin.com/in/ahmad-raza-382700238/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: GitHub
        url: '/https://github.com/Ahmadrazashakir'
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        label: Instagram
        altText: Instagram
        url: '/https://www.instagram.com/ah.mad.raza/'
        showIcon: true
        icon: instagram
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      url: /images/main-hero.svg
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
  - title:
      text: A
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
