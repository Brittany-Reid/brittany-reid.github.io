---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-07-24
type: landing

sections:
    #bio
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
    design:
      columns: '1'
      background:
        gradient_end: '#9e0000'
        gradient_start: '#004ba0'
        text_color_light: true

  #photo gallery
  - block: slider
    content:
      slides:
        - title: 👋 SD Lab @ NAIST
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: sd_lab.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: https://sdlab.naist.jp/en/
        - title: SANER 2025
          content: Presentation of Student Work in Montreal, Canada
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: saner2025.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
          link:
            icon: link
            icon_pack: fas
            text: See Slides
            url: '#talks'
        - title: WIREDS 2024
          content: Successful Workshop
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: wireds.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
          link:
            icon: link
            icon_pack: fas
            text: Check out the website
            url: https://wireds2024.github.io/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  #jobs
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor　・　助教
          company: Nara Institute of Science and Technology
          company_url: 'https://www.naist.jp/en/'
          company_logo: naist
          location: Nara, Japan
          date_start: '2025-04-01'
          date_end: ''
          description: |2-
              Software Design Lab　
        - title: Post-doctoral Researcher ・　博士研究員
          company: Nara Institute of Science and Technology
          company_url: 'https://www.naist.jp/en/'
          company_logo: naist
          location: Nara, Japan
          date_start: '2023-12-01'
          date_end: '2025-03-30'
          description: |2-
              Software Engineering Lab
    design:
      columns: '2'

  #featured posts
  - block: collection
    id: featured
    content:
      title: Featured Publications & Talks
      filters:
        folders:
          - publication
          - talks
        featured_only: true
    design:
      columns: '2'
      view: card

  #datasets
  - block: portfolio
    id: datasets
    headless: true
    content:
      title: Datasets
      filters:
        folders:
          - dataset
      sort_by: 'Date'
      sort_ascending: false

      # filter_button:
      # - name: All
      #   tag: '*'
      # - name: Deep Learning
      #   tag: Deep Learning
      # - name: Other
      #   tag: Demo
      #  filter_default: 0
    design:
      columns: '2'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

 #publications
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'
      view: citation

# presentations
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - talks
    design:
      columns: '2'
      view: compact


  #community engagement
  - block: accomplishments
    content:
      title: Community Engagement
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format:  Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MSR 2026
          date_start: '2026-04-12'
          description: 'Program Committee Technical Track'
          icon: msr
          organization: International Conference on Mining Software Repositories, Rio de Janeiro, Bazil
          organization_url: https://2026.msrconf.org/
          url: ''
        - title: VISSOFT 2025
          date_start: '2025-09-07'
          description: 'Program Committee'
          icon: vissoft
          organization: IEEE Working Conference on Software Visualization, Auckland, New Zealand
          organization_url: https://vissoft.io/2025/
          url: ''
        - title: SANER 2025
          date_start: '2025-03-05'
          description: 'Program Committee Main Track, RENE Track'
          icon: saner
          organization: IEEE International Conference on Software Analysis, Evolution and Reengineering, Montreal, Canada
          organization_url: https://conf.researchr.org/home/saner-2025
          url: ''
        - title: WIREDS Workshop 2024
          date_start: '2024-12-06'
          description: 'Organizing Committee'
          icon: wireds-c
          organization: International Workshop on Intertwining Research & Education on Software, Osaka, Japan
          organization_url: https://wireds2024.github.io
          url: ''
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  #awards and funding
  - block:  markdown
    content:
      title: Awards and Funding
      text: |-
        <div class="card-simple">
        <div class="article-style">
          <b>SIML 2025 Student Best Paper Award</b><br>
          <i>Bayu Fedra Abdullah, Yusuf Sulistyo Nugroho, Brittany Reid, Raula Gaikovina Kula, Kazumasa Shimari, Kenichi Matsumoto</i><br>
          For the paper "Using LLMs for Security Advisory Investigations: How Far Are We?" at the International Conference on Smart Computing, IoT, and Machine Learning (SIML) 2025<br>
        </div>
        </div>

        <div class="card-simple">
        <div class="article-style">
          <b>Nara Institute of Science and Technology, Senju Monju Project 2024</b><br>
          The NAIST Senju Monju Project provides broad support to young researchers at NAIST to initiate new research based on their own ideas.<br>
          <a href="https://cdgw3.naist.jp/en/555/">Details</a><br>
        </div>
        </div>
    design:
      columns: '2'

  #news
  - block: markdown
    content:
      title: News
      text: |-
        {{< bsky-embed username="brittanyareid.bsky.social" >}}
    design:
      columns: '2'

  #contact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: brittany.reid@naist.ac.jp
      phone: 0743-72-5318
      # appointment_url: 'https://calendly.com'
      address:
        street: 8916-5 Takayamacho
        city: Ikoma
        region: Nara
        postcode: '630-0192'
        country: Japan
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday to Friday 10:00 to 17:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '34.73204856906994'
        longitude: '135.73439311240438'  
      contact_links:
        - icon: file
          icon_pack: fas
          name: Download CV
          link: '/cv.pdf'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: false
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
