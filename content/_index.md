---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: R
  #        description: 90%
  #        icon: r-project
  #        icon_pack: fab
  #      - name: Statistics
  #        description: 100%
  #        icon: chart-line
  #        icon_pack: fas
  #      - name: Photography
  #        description: 10%
  #        icon: camera-retro
  #        icon_pack: fas
  - block: experience
    content:
      title: Research experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Develop and validate a comprehensive genetic risk prediction model for AD that includes both common and low frequency/rare genetic variants.
          company: With Corinne Engelman and Jason Fletcher
          company_url: ''
          #company_logo: org-gc
          location: University of Wisconsin-Madison
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
              Dissertation work. Built a comprehensive genetic prediction model by integrating common and rare genetic variants. Demonstrated the feasibility of this framework to extend our ability to make genetic predictions in Alzheimer's.
        - title: Early life SES (critical period and self-reported SES) modifies genetic propensity of AD on cognition in older age
          company: With Corinne Engelman and Jason Fletcher
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2022-07-01'
          date_end: '2022-03-31'
          description: Dissertation work. Two-stage analyses. Using longitudinal data, the stage one analysis explored how self-reported socioeconomic status can modify the genetic propensity on later life cognition decline. The second stage analysis leveraged a natural experimental framework. It examined whether and how economic conditions during the critical period can modify the genetic propensity of AD on later life cognition decline using longitudinal questionnaire data, state-level macroeconomic administrative indicators, and geographical data.
        - title: Mid-to-Late Life Healthy Lifestyle Modifies Genetic Risk for Longitudinal Cognitive Aging among Asymptomatic Individuals from the Wisconsin Registry for Alzheimer’s Prevention
          company: With Corinne Engelman and Jason Fletcher
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2022-01-01'
          date_end: '2022-06-30'
          description: Dissertation work. This work uses WRAP data to explore how the mid-to-late life modifiable behaviors individually and synergetically modify the genetic propensity of AD on the late-life cognitive decline during AD’s preclinical stage. The findings from this study have been replicated in the Health and Retirement Study.
        - title: Apolipoprotein E moderates the association between Non-APOE Polygenic Risk Score for Alzheimer’s Disease and Aging on Preclinical Cognitive Function
          company: With Corinne Engelman
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2021-07-01'
          date_end: '2021-12-31'
          description: This work uses WRAP data to explore how the APOE ε4 carrier status modifies the effects of currently known genetic variants of AD on the late-life global and domain-specific cognitive decline during AD’s preclinical stage. The findings from this study have been replicated in the Health and Retirement Study.
        - title: Effect of Pathway-specific Polygenic Risk Scores for Alzheimer's Disease (AD) on Rate of Change in Cognitive Function and AD-related Biomarkers among Asymptomatic Individuals
          company: With Corinne Engelman
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2021-01-01'
          date_end: '2021-06-30'
          description: This work uses WRAP data to explore the potential of pathway-specific PRS in predicting cognition and AD-related biomarkers during the preclinical stage of Alzheimer's after considering uncertainties in the gene-pathway assignment. Findings from this study have been replicated in W-ADRC.
        - title: Early Life Exposures, Gene-Environment Interactions, and Cognition in Old Age
          company: With Jason Fletcher
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2020-07-01'
          date_end: '2021-01-01'
          description: This work used HRS data and instrumental variable approach to explore how early exposure to pneumonia morbidity and mortality can affect adult cognitive decline. We also investigated whether early-life exposure to pneumonia morbidity and mortality can modify the genetic propensity of cognition on later-life cognitive decline.
        - title: Bald is Beautiful?  Life course outcomes for individuals at high genetic risk for male pattern
          company: With Jason Fletcher
          company_url: ''
          #company_logo: org-x
          location: University of Wisconsin-Madison
          date_start: '2019-10-01'
          date_end: '2020-06-30'
          description: Extensive literature shows that higher attractiveness is associated with socioeconomic success in the US and many other countries.  We combine this question with a novel use of genetic data to examine one dimension of attractiveness, male patterned baldness, and its associations with educational attainment, adult income, cognition, and adult neighborhood socioeconomic status in the UKBB by applying a sibling fixed analysis and also produce both “reduced form” and two-stage least square analyses.  
        - title: Childhood socioeconomic status moderates genetic predisposition for peak smoking
          company: With Titus Galama
          company_url: ''
          #company_logo: org-x
          location: University of Southern California
          date_start: '2019-01-01'
          date_end: '2019-06-30'
          description: Smoking is the leading cause of preventable disease and death in the U.S., and it is strongly influenced by genetic predisposition and childhood socioeconomic status (SES). Using genetic variants exhibiting credible and robust associations with smoking, we construct polygenic risk scores (PGS) and evaluate whether childhood SES mediates genetic risk in determining peak-cigarette consumption in adulthood.  
    design:
      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: recent
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
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      #subtitle:
      #ext: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: yxu459@wisc.edu
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: 1007H WARF
        city: Madison
        region: WI
        postcode: '53713'
        country: United States
        country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    #design:
    #  columns: '2'
---
