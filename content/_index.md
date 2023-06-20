---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
editable: true

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: Programming
  #        description: "**Python**, R, bash, git, LaTeX"
  #        icon: code
  #        icon_pack: fa
  #      - name: "Brain Modelling"
  #        description: MNE
  #        icon: brain
  #        icon_pack: custom
  #      - name: Eye Movements Modelling
  #        description: Integration with Large Language Models
  #        icon: eye
  #        icon_pack: custom
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Head Teaching Assistant
          company: Technion
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-03-0'
          date_end: '2023-09-30'
          description: |2-
            * Courses: Probability, Correctness Guarantees for Software, Cognition in Information Visualization
        - title: Data Analyst
          company: Outbrain
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2019-11-01'
          date_end: '2021-01-30'
          description: |2-
            * Student position in the Recommendations R&D group. Analyzed an enormous amount of data for supporting product related decisions and solutions. Used different analytics tools, such as complex SQL queries and dashboards.
        - title: Intelligence Officer (Captain)
          company: IDF Intelligence Corps
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2017-10-01'
          date_end: '2011-11-01'
          description: |2-
            * Military service at the Research and Analysis Department. Leading and running research and analysis team. Strategical, operational, tactical and technical in depth analysis of complex issues based on diverse information.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  - block: collection
    content:
      count: 10
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me at:
      # Contact (add or remove contact options as necessary)
      email: <first_name>.<last_name>(at)campus.technion.ac.il
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
