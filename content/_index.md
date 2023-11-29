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
        - title: AI Researcher & Data Engineer
          company: Motius GmbH
          company_url: 'https://www.motius.com/'
          company_logo: motius
          location: Munich
          date_start: '2021-05-17'
          date_end: '2023-09-30'
          description: |2-
              * Collaborated in a dynamic research environment, contributing hands-on expertise in Python.
              * Engineered advanced deep learning architectures using PyTorch Lightning and TensorFlow.
              * Worked on the FunKI research project, leveraging deep learning frameworks to explore and optimize 5G network performance.
              * Implemented anomaly detection techniques for enhanced diagnostics in ultrasound images.
              * Contributed significantly to the 6G SKY research project, focusing on the explainability, interpretability, and robustness of deep learning networks.
              * Spearheaded the replacement/migration of relational databases to cloud infrastructure (AWS, GCP).
              * Executed tasks in DWH, ETL, and Big Data domains.
    
        - title: Data Engineer
          company: Incuda GmbH
          company_url: 'https://www.incuda.net/'
          company_logo: incuda
          location: Munich
          date_start: '2020-10-07'
          date_end: '2021-05-13'
          description: |2-
              * Implemented and optimized end-to-end ETL processes, emphasizing extraction, CDC, load, recycle management, dimension management, and key management.
              * Enhanced frameworks for classical DWH architecture, improving efficiency with large datasets.
              * Assisted in documentation, analysis, quality assurance, testing, and operational aspects of ETL processes.
    
        - title: Senior Data Engineer
          company: Vodafone
          company_url: 'https://www.vodafone.com/'
          company_logo: vodafone
          location: Istanbul
          date_start: '2019-06-01'
          date_end: '2020-09-26'
          description: |2-
              * Led the ETL workflow and processes as part of the DWH Reengineering project, designing and developing DevOps CI/CD pipeline and migration flows.
              * Developed productivity tools and automation, reviewed designs and code, and contributed to data preparation for datamining.
              * Leveraged cloud services on AWS and GCP to gather data from OLTP systems, ensuring scalability and efficiency.
              * Employed cloud-based optimization techniques on AWS and GCP to improve the efficiency and performance of database queries and processes.
    
        - title: Senior Data Engineer
          company: Garanti BBVA Technology
          company_url: 'https://www.garantibbvateknoloji.com.tr/'
          company_logo: garanti
          location: Munich
          date_start: '2016-07-07'
          date_end: '2019-05-13'
          description: |2-
              * Managed ETL architecture, optimizing data processing for operational data.
              * Improved database performance through property optimization and mapping enhancements on ODI.
              * Developed finance applications using RDBMS systems (Oracle Database, IBM DB2) and Java for efficient data manipulation in multichannel communication.
    design:
      columns: '1'
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Data Engineering
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
  - block: collection
    id: publications
    content:
      title: Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        #exclude_featured: true
    design:
      columns: '1'
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
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: mervekarali93@gmail.com
      # Automatically link email and phone or display as text?
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
      columns: '1'
---
