---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: About me
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
        - title: Environment and Sustainability Advisor.
          company: Crossroads International.
          company_url: 'https://cintl.org/'
          company_logo: org-x
          location:  Montreal, Canada.
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
      
  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: false
        exclude_past: false
    design:
      columns: '2'
      view: citation
         
    design:
      columns: '2'
      view: compact
      
    design:
      # Choose a layout view
      view: compact
      columns: '2'
    
    
  - block: portfolio
    id: posts
    content:
      title: awards
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - project
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
      
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 15

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: DFKI
    company_url: 'https://www.dfki.de/web/forschung/forschungsbereiche/data-science-und-ihre-anwendungen'
    company_logo: org-gc
    location: Germany
    date_start: '2022-11-15'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Studying the tensions between fairness and the right to erasure in the context of machine learning (i.e machine unlearning).
        * Advised by [Prof. Seth Flaxman]('https://sethrf.com/') and [Prof Sebastian vollmer]('https://sebastian.vollmer.ms/').
  - title: Research Intern
    company: Mila-Quebec AI Institute
    company_url: 'https://mila.quebec/en/'
    company_logo: org-gc
    location: Montreal, Canada
    date_start: '2021-10-04'
    date_end: '2022-04-30'
    description: |2-
        Responsibilities include:
        
        * Studying the tensions between fairness and the right to erasure in the context of machine learning (i.e machine unlearning).
        * Advised by Prof. Golnoosh Farnadi and Dr. Ulrich Aivodji.

  - title: Research Intern
    company: Vector Institute
    company_url: 'https://vectorinstitute.ai/'
    company_logo: org-x
    location: Toronto, Canada
    date_start: '2021-05-04'
    date_end: '2021-09-04'
    description: |2-
        Responsibilities include:
        
        * Working on a project related to the idea of fairwashing where we try to detect if the interpretable model provided by the company is the exact
          one or it is a fake fair model (paper accepted @ Neurips 2022).
        * Advised by Prof. Nicolas Papernot.

  - title: Teaching and Reseach Assistance 
    company: African Master in Machine Intelligence (AMMI-Senegal)
    company_url: 'https://aimsammi.org/'
    company_logo: org-x
    location: Senegal
    date_start: '2020-01-01'
    date_end: '2021-11-30'
    description: |2-
        Responsibilities include:
        
        * Teaching Machine Learning for a class of about 40 students and engaged in different groups of research in a variety of Machine Learning topics.
        * Advised by Moustapha Cisse.

  - title: Research Intern
    company: Vector Institute
    company_url: 'https://vectorinstitute.ai/'
    company_logo: org-x
    location: Toronto, Canada
    date_start: '2019-09-04'
    date_end: '2019-12-28'
    description: |2-
        Responsibilities include:
        
        * Work on Multimodal using memory shared to learn the single representation for the objects.
        * Engage in all parts of the research process including reading relevant literature, running experiments and writing results.
        * Advised by Prof. Sanja Fidler.

design:
  columns: '2'
---
