---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:

    ### BIOGRAPHY

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


  ### EXPERIENCE

  
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: Universidade Federal do Ceará
          company_url: ''
          company_logo: 'Brasao_ufc' 
          location: Fortaleza
          date_start: '2021-10-28'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Participating in boring meetings 
              * Grading exams
              * Attending badly-designed courses on how to improve teaching habilities
        - title: Visiting Scholar
          company: Max-Planck Institut für Mathematik
          company_url: 'https://www.mpim-bonn.mpg.de'
          company_logo: 'max-planck'
          location: Bonn
          date_start: '2021-10-15'
          date_end: '2022-10-31'
          description: Research position 
        - title: Visiting Professor
          company: Universidade Federal do Ceará
          company_url: ''
          company_logo: 'Brasao_ufc'
          location: Fortaleza
          date_start: '2019-04-01'
          date_end: '2021-03-31'
          description: Research and minimal teaching
    design:
      columns: '2'


    ### PREPRINTS
  
  - block: collection
    id: preprints
    content:
      title: Preprints
      count: 5 # how many pages to display (0 = all)
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation


  ###PUBLICATIONS
  

  - block: collection
    id: publications
    content:
      title: Publications
      count: 0 # how many pages to display (0 = all)
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation


  ### Events


  - block: collection
    id: events
    content:
      title: Recent & Upcoming Events
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: list
  

  ### POSTS
  

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      count: 5 # how many pages to display (0 = all)
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
      view: compact
      columns: '2'
  

  ### POPULAR TOPICS
  

  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'

---
