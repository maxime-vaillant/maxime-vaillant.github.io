---
# Leave the homepage title empty to use the site title
title: ''
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
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Engineer
          company: Inria
          company_url: ''
          company_logo: inria
          location: Lyon, France
          date_start: '2024-01-01'
          date_end: ''
        - title: Data Scientist Intern
          company: Orange Labs
          company_url: ''
          company_logo: orange
          location: Paris, France
          date_start: '2023-02-01'
          date_end: '2023-08-01'
        - title: Full Stack Developer Intern
          company: Coddity
          company_url: ''
          company_logo: coddity
          location: Paris, France
          date_start: '2021-09-01'
          date_end: '2022-02-01'
    design:
      columns: '1'
  # - block: skills
  #  content:
  #    title: Skills
  #    text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
   #   username: admin
   # design:
   #   columns: '1'
  #- block: accomplishments
  #  content:
  #    # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
  #    # Date format: https://docs.hugoblox.com/customization/#date-format
  #    date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #    items:
  #      - certificate_url: https://www.coursera.org
  #        date_end: ''
  #        date_start: '2021-01-25'
  #        description: ''
  #        icon: coursera
  #        organization: Coursera
  #        organization_url: https://www.coursera.org
  #        title: Neural Networks and Deep Learning
  #        url: ''
  #      - certificate_url: https://www.edx.org
  #        date_end: ''
  #        date_start: '2021-01-01'
  #        description: Formulated informed blockchain models, hypotheses, and use cases.
  #        icon: edx
  #        organization: edX
  #        organization_url: https://www.edx.org
  #        title: Blockchain Fundamentals
  #        url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #      - certificate_url: https://www.datacamp.com
  #        date_end: '2020-12-21'
  #        date_start: '2020-07-01'
  #        description: ''
  #        icon: datacamp
  #        organization: DataCamp
  #        organization_url: https://www.datacamp.com
  #        title: 'Object-Oriented Programming in R'
  #        url: ''
  #  design:
  #    columns: '2'
  # - block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'
  # - block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #     folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
   #     - name: All
    #      tag: '*'
    #    - name: Deep Learning
    #      tag: Deep Learning
    #    - name: Other
    #      tag: Demo
    #design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      #columns: '1'
      #view: showcase
      # For Showcase view, flip alternate rows?
      #flip_alt_rows: false
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Check all [publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      email: maxime@vaillant.dev
      phone: +33 6 58 06 12 58
      autolink: true
    design:
      columns: '2'
---
