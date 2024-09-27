---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: "\U0001F680 Are you ready to kickstart your career?"
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: |
      GradAccelerate Program (GAP) will equip you with the skills,
      experience, and industry connections you need to launch a
      successful career. Let’s make your future in tech happen, together.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: form-data
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-32
            - pr-32
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 0
          borderRadius: large
          justifyContent: center
          margin:
            - mr-24
            - ml-24
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        alignItems: center
        justifyContent: center
      text:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      text: Key Incentives
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Explore key incentives(right suitable subtitle here)
    items:
      - type: FeaturedItem
        title: Flexible Learning
        subtitle: ''
        text: >
          Benefit from a hybrid learning model that allows you to balance your
          studies with work or other commitments.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Global Exposure
        subtitle: ''
        text: >
          Engage in virtual global collaborations and gain insights into
          international tech trends and best practices.
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Networking Opportunities
        subtitle: ''
        text: >
          Connect with industry professionals, potential employers, and fellow
          GAP participants.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
      - type: FeaturedItem
        title: Entrepreneurial Support
        subtitle: ''
        text: >
          Explore your entrepreneurial aspirations with access to resources and
          a network of like-minded individuals.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Industry-Recognized Certification
        subtitle: ''
        text: >
          Earn a valuable certificate upon program completion, validating your
          acquired skills.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Career Placement Support
        subtitle: ''
        text: >
          Access a dedicated career placement team offering resume reviews,
          interview preparation, and job placement assistance.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    actions: []
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/Screenshot from 2024-09-26 18-14-15.png
        altText: eva
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/9d72c6c6743dc0577c3d60c8e9e277b7.webp
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Diverse Learning Tracks
      color: text-primary
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
      - content/data/product-management/business-analytics.json
      - content/data/artificial-intelligence/machine-learning.json
    actions: []
    variant: four-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: flex-start
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: >-
        Don't wait—secure your spot in the next cohort and start your journey
        today!
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: |+
      <div style="text-align: center"></div>

    actions:
      - type: Button
        label: Register Today
        altText: Register Today!
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      altText: Unblock your team boost your time to production preview
      elementId: ''
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: col
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      text:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Improved Student Experience
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Personal GrowthPersonal Growth
        tagline: ''
        subtitle: >-
          Challenge yourself to step outside your comfort zone and develop
          valuable life skills.
        text: ''
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
            flexDirection: row
      - type: FeaturedItem
        title: Enhanced Employability
        tagline: ''
        subtitle: Acquire valuable skills and experiences that employers actively seek.
        text: ''
        image:
          type: ImageBlock
          altText: Background alt text
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
            flexDirection: row
      - type: FeaturedItem
        title: Cultural Enrichment
        tagline: ''
        subtitle: >-
          Immerse yourself in different cultures to broaden your perspective and
          foster intercultural understanding.
        text: ''
        image:
          type: ImageBlock
          altText: Background alt text
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
            flexDirection: row
      - type: FeaturedItem
        title: Career Exploration
        tagline: ''
        subtitle: >-
          Gain practical experience and explore potential career paths to make
          informed choices.Gain practical experience and explore potential
          career paths to make informed choices.
        text: ''
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
            flexDirection: row
    actions: []
    variant: small-list
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Elevate Your Education
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Fully Funded Scholarships
        subtitle: ''
        text: >
          Discover the path to your dreams with our fully funded scholarships.
          We believe in empowering students to succeed.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Early Bird Discount
        subtitle: ''
        text: >
          Secure your spot and benefit from a 50% discount on program fees when
          you register early. Don't miss out on this opportunity!
        image:
          type: ImageBlock
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
      - type: FeaturedItem
        title: Program Fee
        subtitle: ''
        text: >
          Our program fee is 180,000 PKR, offering a comprehensive and valuable
          learning experience.
        image:
          type: ImageBlock
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: >-
        Don’t miss out on these opportunities. Take advantage of our
        scholarships and discounts now!
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: |+
      <div style="text-align: center"></div>

    actions:
      - type: Button
        label: Secure Your Spot
        altText: Secure Your Spot
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      altText: Unblock your team boost your time to production preview
      elementId: ''
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: col
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      text:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Eligibility Criteria
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Academic Standing
        tagline: ''
        subtitle: ''
        text: >
          Maintain a strong academic record, demonstrating a commitment to
          learning. Minimum GPA requirements may apply.
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
            flexDirection: row
      - type: FeaturedItem
        title: Course Completion
        tagline: ''
        subtitle: ''
        text: >
          Complete specific prerequisite courses relevant to the program's focus
          area. Ensure a strong foundation in essential knowledge.
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
            flexDirection: row
      - type: FeaturedItem
        title: Interest & Motivation
        tagline: ''
        subtitle: ''
        text: >
          Exhibit a genuine interest and passion for the program's field,
          displaying a proactive mindset and eagerness to learn.
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
            flexDirection: row
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Simplified Application Process
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Submit Application
        tagline: ''
        subtitle: >-
          Submit your application form online. Be sure to include all the
          required documents and information.
        text: ''
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Background alt text
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
            flexDirection: row
      - type: FeaturedItem
        title: Review & Evaluation
        tagline: ''
        subtitle: >-
          Our expert team will thoroughly review your application based on your
          academic background, skills, and experience.
        text: ''
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Background alt text
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
            flexDirection: row
      - type: FeaturedItem
        title: Interview
        tagline: ''
        subtitle: >-
          Selected candidates will be invited for an interview to assess their
          suitability for the program and discuss their aspirations.
        text: ''
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Background alt text
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
            flexDirection: row
      - type: FeaturedItem
        title: Notification & Acceptance
        tagline: ''
        subtitle: >-
          Following the interview process, successful applicants will receive an
          official notification of acceptance into the program.
        text: ''
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
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
            flexDirection: row
    actions: []
    variant: two-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Ready to Take the Leap?
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: |+
      <div style="text-align: center"></div>

    actions:
      - type: Button
        label: Apply Now
        altText: Apply Now
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      altText: Unblock your team boost your time to production preview
      elementId: ''
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: col
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      text:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Invite & Earn a Gift Card!
      color: text-dark
    subtitle: >-
      Invite your friends to join GAP and earn a chance to win a gift card! The
      more friends you refer, the better your chances!
    text: |+
      #### **How it works:**

      *   Share GAP with your friends.
      *   Have them enter your name and email on the application form.
      *   Get a chance to win with every referral!

    actions:
      - type: Button
        label: Share on WhatsApp
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        altText: Share on WhatsApp
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-neutral-fg-dark
    styles:
      self:
        alignItems: center
  - type: CarouselSection
    subtitle: What GAPIANS Are Saying
    items:
      - type: FeaturedItem
        title: >-
          "GAP’s hands-on approach and diverse tracks transformed my career in
          just few weeks."
        tagline: ''
        subtitle: '- Adrian K.'
        text: ''
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
      - type: FeaturedItem
        title: >-
          "The support from GAP’s career team was outstanding. I secured a job
          immediately after graduating!"
        tagline: ''
        subtitle: '- Anique'
        text: ''
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
      - type: FeaturedItem
        title: >-
          "Thanks to GAP, I’ve transitioned into digital marketing with a solid
          foundation and real-world skills."
        tagline: ''
        subtitle: '- Tony'
        text: ''
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
      - type: FeaturedItem
        title: '"GAP gave me the skills and confidence to land my dream job in tech!"'
        tagline: ''
        subtitle: '- Muhammad Muzammil '
        text: ''
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
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Learn from the Best in the Field
      color: text-dark
    subtitle: ''
    text: >+
      *   Receive mentorship from seasoned specialists dedicated to your success
      and skill development.


      *   Engage with instructors who are at the forefront of their industries
      and understand current trends.


      *   Develop skills through practical lessons taught by experts who have
      navigated the challenges of the field.

    actions: []
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: GenericSection
    title:
      type: TitleBlock
      text: >-
        Ready to learn from industry leaders and advance your career? Take the
        next step with GAP.
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: |+
      <div style="text-align: center"></div>

    actions:
      - type: Button
        label: Join GAP Today
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      altText: Unblock your team boost your time to production preview
      elementId: ''
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: col
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      text:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: FAQs
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: What is the GradAccelerate Program?
        subtitle: ''
        text: >
          GradAccelerate Program aka GAP is a intensive program designed to
          equip participants with tech skills, hands-on experience, and industry
          connections for a successful career.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Who is the GAP for?
        subtitle: ''
        text: >
          GAP is tailored for final-year students, recent graduates, and
          professionals seeking to pivot into tech. It’s perfect for anyone
          eager to launch or advance their career in the technology sector.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: How long is the GAP program?
        subtitle: ''
        text: >
          The GAP program spans 16 weeks, providing intensive training and
          hands-on learning in your chosen track.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
      - type: FeaturedItem
        title: Is this a physical or online program?
        subtitle: ''
        text: >
          GAP is a fully online program, allowing you to participate from
          anywhere with flexibility and convenience.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: What will I study in GAP?
        subtitle: ''
        text: >
          You’ll gain in-depth knowledge and hands-on experience in your chosen
          track, whether it’s Full-stack Development, UX/UI Design, AI/ML, or
          more, preparing you for real-world tech challenges.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Who will teach us in GAP?
        subtitle: ''
        text: >
          GAP is taught by seasoned industry professionals and expert
          instructors, bringing years of real-world experience to help you
          master the skills needed for a successful tech career.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: What are the program timings?
        subtitle: ''
        text: >
          The program runs five days a week, offering 25 to 35 hours of learning
          and hands-on projects each week, depending on your task completion.
          The flexible schedule allows you to adapt your workload based on
          progress, ensuring a balance between learning and practical
          applications.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: How many students will be enrolled in one batch?
        subtitle: ''
        text: >
          Each batch is limited to 6-12 students, ensuring personalised
          attention and support.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: What qualifications are required to join GAP?
        subtitle: ''
        text: >
          You need to have completed a minimum of 16 years of education, with a
          keen interest in technology and innovation.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Is there an interview process for admission?
        subtitle: ''
        text: >
          Yes, shortlisted candidates will be invited for an interview to assess
          their skills, motivation, and suitability for the program.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Are scholarships available for GAP?
        subtitle: ''
        text: >
          Yes, we offer fully funded scholarships and early bird discounts. Ask
          us! 
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: What benefits do I get if I refer a friend to GAP?
        subtitle: ''
        text: >
          By referring a friend to join GAP, you get a chance to win a gift card
          when they apply and mention your name and email in their application
          form.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
    actions: []
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
  - type: ImageGallerySection
    subtitle: Brands That Trust Devkind
    images:
      - type: ImageBlock
        url: /images/a99369a399ee512d0d29543ec778c857 (1).webp
        altText: EVA
        elementId: ''
      - type: ImageBlock
        url: /images/9111b4007768f62441c1448a90e2de72.webp
        altText: John Frieda
        elementId: ''
      - type: ImageBlock
        url: /images/8c14893e8055bd9813c8baabcfbd377e.webp
        altText: NED
        elementId: ''
      - type: ImageBlock
        url: /images/ab42b303d25c208e54ebb354ba35aed3.webp
        altText: fairway
        elementId: ''
      - type: ImageBlock
        url: /images/9d72c6c6743dc0577c3d60c8e9e277b7.webp
        altText: Table Top Games
        elementId: ''
      - type: ImageBlock
        url: /images/7c7d01f9b9245eb3224f6cfeabaddb38.webp
        altText: Burt's Bees
        elementId: ''
      - type: ImageBlock
        url: /images/046c8a201eecd0c0c0c37c171facb9ef.webp
        altText: perfect Events
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    badge:
      type: Badge
      label: Our clients hire the best—and we prepare you to be just that.
      color: text-primary
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
