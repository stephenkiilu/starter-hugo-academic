---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Environment and Sustainability Advisor
          company: Crossroads International
          company_url: 'https://cintl.org/'
          company_logo: org-gc
          location: Montreal, Canada
          date_start: '2022-09-01'
          date_end: '2023-04-01'
          description: |2-
            A mandate with the iSpace Foundation in Accra, Ghana. 
            Responsibilities include:

              * Supported the iSpace Foundation’s climate change programs.
              * Developed policies that support the iSpace Foundation’s 2021–2025 climate action agenda.
              * Conducted training and workshops to build climate change capacity for communities in Ghana.
              * Led the iSpace Foundation’s climate change research and outreach activities.
              
        - title: Data Analyst
          company: Glacier Products Limited
          company_url: 'https://dairyland.co.ke/'
          company_logo: org-x
          location: Nairobi, Kenya
          date_start: '2020-03-01'
          date_end: '2020-09-01'
          description: |2-
            Responsibilities include:
              * Worked on data analysis and reporting.
              * Conducted system audits, fleet monitoring, and tracking, and managed the freezer management system

        - title: Content Supervisor
          company: Kenya National Bureau of Statistics, KNBS
          company_url: 'https://www.knbs.or.ke/'
          company_logo: org-x
          location: Nairobi, Kenya
          date_start: '2019-08-01'
          date_end: '2019-09-01'
          description: |2-
            Responsibilities include:
              * Coordinated the enumeration exercise (census) on behalf of the KNBS director general.
              * Trained and supported field enumeration officers.
              * Worked with the local national government administrative officers (NGAOs) to ensure that the census.
            
          
    design:
      columns: '2'
         
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block:  publication
    id: publication
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: skiilu@aimsammi.org
      phone: +254 701 739 786
      address:
       # street: 450 Serra Mall
      #  city: Stanford
        region: Nairobi
        postcode: '001'
        country: Kenya
        country_code: 054
     # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/EtienneKiilu'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider

    design:
      columns: '2'
---
