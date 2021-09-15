---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: >
      # Fifty State Suds


      To place order, please contact us with soap quantity and type (ex. 1
      Michigan Soap \*Go Blue Edition) and Venmo $5.99/soap @fiftystatesuds
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Featured Products
    icon: true
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Michigan, USA'
        text: >-
          I loved seeing this soap at gift stores near me and 
      - author:
          name: Major Payne
          location: 'Michigan, USA'
        text: >-
          This soap is awesome to use and is a great gift for friends and family!
  - type: promotion_section
    section_id: promotion_section
    title: High quality soap in the shape of your home state!
    subtitle: Only $5.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: See More
      url: /store
      style: secondary
      arrow: true
seo:
  title: 50 States Suds
  description: Soaps in the shape of states
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
template: home
---
