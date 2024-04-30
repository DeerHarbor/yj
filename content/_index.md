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
 - block: features
    content:
     title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
         icon_pack: fab
      - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
          - title: PhD Student
    company: King’s College London
    company_url: ''
    company_logo: kcl
    location: London, UK
    date_start: '2023-09-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        * Major: Forensic and Neurodevelopmental Sciences
        * Supervisor: [Professor Andre Strydom](https://www.kcl.ac.uk/people/professor-andre-strydom), [Doctor Rory Sheehan](https://www.kcl.ac.uk/people/rory-sheehan)
  - title: Master Student
    company: Queen Mary University of London 
    company_url: ''
    company_logo: QMUL
    location: London, UK
    date_start: '2021-09-01'
    date_end: '2022-09-01'
    description: |2-
        Responsibilities include:

        * Major: Mental Health: Psychological Therapies

  - title: Professor assistant 
    company: The First Affiliated Hospital of University of South China 
    company_url: ''
    company_logo: org-x
    location: Hunan, China
    date_start: '2019-09-01'
    date_end: '2022-04-07'
    description: |2-
        Responsibilities include:
        
        * Outpatient service
        * Psychological assessment 
        * Medicine instruction
        * Medical records
    
  - title: Master Student
    company: University of Aberdeen 
    company_url: ''
    company_logo: abd
    location: Scotland, UK
    date_start: '2020-09-01'
    date_end: '2021-09-01'
    description: |2-
        Responsibilities include:

        * Major: Psychological Studies
       
  - title: Intern 
    company: Hengjiakang Mental Rehabilitation Hospital
    company_url: ''
    company_logo: org-a
    location: Hunan, China
    date_start: '2020-09-01'
    date_end: '2021-09-01'
    description: |2-
        Responsibilities include:
        
        * Writing medical records
        * Daily psychological counselling
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
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
        - name:Clinical psychology
          tag: Clinical psychology
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#     title: Gallery
 #     subtitle: ''
   #   text: |-
  #      {{< gallery album="demo" >}}
 #   design:
 #     columns: '1'



  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
 #    text: |-
 #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
 #     # Contact (add or remove contact options as necessary)
    email: yajing.zhou@kcl.ac.uk
    phone: +44 7547416604
   #   appointment_url: 'https://calendly.com'
  address:
    street: 16 De Crespigny Park
    city: London
    region: United Kingdom
    postcode: 'SE5 8AF'
    country: United Kingdom
    country_code: HK
  coordinates:
    latitude: '51.47047891085169'
    longitude: ' -0.08979993835722354'
  directions: Room M1.09, IoPPN main building, Denmark Hill Campus, King’s College London
  #  office_hours:
 #       - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
 #         link: 'https://twitter.com/Twitter'
 #       - icon: skype
  #        icon_pack: fab
  #        name: Skype Me
 #         link: 'skype:echo123?call'
   #     - icon: video
  #        icon_pack: fas
#          name: Zoom Me
   #       link: 'https://zoom.com'
   #  Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
