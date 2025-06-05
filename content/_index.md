---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. in Ecology (expected)
          company: Tsinghua University
          company_url: 'https://www.tsinghua.edu.cn/'
          company_logo: THU
          location: Beijing, China
          date_start: '2025-09-01'
          date_end: '2029-06-01'
          description: |2-
              <p>
                <ul>
                    <li>Future Scholar Scholarship of THU (2024)</li>
                </ul>
              </p>
        - title: M.S. in Geography (expected)
          company: University of Chinese Academy of Sciences
          company_url: 'https://www.ucas.ac.cn/'
          company_logo: UCAS
          location: Beijing, China
          date_start: '2022-09-01'
          date_end: '2025-07-20'
          description: |2-
              <p>
                <ul>
                    <li>National Scholarship (2024)</li>
                    <li>Outstanding Graduate of Beijing (2025)</li>
                    <li>Outstanding Graduate of UCAS (2025)</li>
                    <li>Outstanding Graduate of IGSNRR (2025)</li>
                    <li>IGSNRR Director's Scholarship (2023, 2024, 2025)</li>
                </ul>
              </p>
        - title: B.S. in Geography
          company: Northeast Normal University
          company_url: 'https://www.nenu.edu.cn/'
          company_logo: NENU
          location: Changchun, China
          date_start: '2018-09-01'
          date_end: '2022-06-17'
          description: |2-
              <p>
                  <ul>
                      <li>National Scholarship (2020)</li>
                      <li>Outstanding Graduate of NENU (2022)</li>
                      <li>NENU President's Scholarship (2019, 2021 and 2022)</li>
                      <li>Special Prizes in the National College Students GIS Application Skills Competition (2020)</li>
                  </ul>
              </p>
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
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
      title: Posts
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
 # - block: markdown
 #   id: gallery
 #   content:
 #     title: Gallery
 #     subtitle: "I'm an photography enthusiast, and here are some photos I took on my trip. I hope you like them too!️️️️ ❤️❤️❤️"
 #     text: |-
 #       {{< gallery album="photos" >}}
 #   design:
 #     columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
#      text: |-
#        You're welcome to leave me a message!
      email: wu_xiaoran@outlook.com
 #    phone: +86 15258545595
      address:
        street: Room C404-2, 11A, Datun Road, Chaoyang District
        city: Beijing
        postcode: CN 100101
        country: China
        country_code: CN
      # Automatically link email and phone or display as text?
#      autolink: true
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---
