---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: iAR package
      tag: iAR
    - name: Astro-Statistics
      tag: Astro-Statistics
    - name: Public Health
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    email: felipe.elorrieta@usach.cl
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
