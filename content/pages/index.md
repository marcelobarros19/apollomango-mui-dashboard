---
title: Dashboard
type: Page
sections:
  - type: HeroSection
    title: Hero Title
    subtitle: 'Featuring TypeScript, Next.js, MUI v5 & Emotion'
    text: >
      This is the HeroSection component. You can visually edit this component &
      add more sections while developing locally. [Learn
      more.](https://docs.netlify.com/visual-editor/local-development/)
    actions:
      - type: Button
        label: Start Building
        url: 'https://docs.netlify.com/visual-editor/get-started/'
        size: small
        variant: outlined
        color: secondary
    image:
      type: Image
      altText: Hero section image
  - type: CardsSection
    title: Cards Section Title
    subtitle: The section subtitle
    items:
      - type: Card
        title: First Item Title
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        image:
          type: Image
          url: /images/nextjs.svg
          altText: First item image
        actions:
          - type: Button
            label: Learn more
            url: /
            size: medium
            variant: text
            color: primary
      - type: Card
        title: Second Item Title
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        image:
          type: Image
          url: /images/mui-5.svg
          altText: Second item image
        actions:
          - type: Button
            label: Learn more
            url: /
            size: medium
            variant: text
            color: primary
      - type: Card
        title: Third Item Title
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        image:
          type: Image
          url: /images/ts.svg
          altText: Third item image
        actions:
          - type: Button
            label: Learn more
            url: /
            size: medium
            variant: text
            color: primary
---
