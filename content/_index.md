---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-09-17
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: skye.png #cornered-stairs.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Currently, my project concerns the use causal inference techniques (e.g., g-methods, debiased machine learning techniques) for the analysis of longitudinal, observational data in psychological research. 

        I find it important to always keep the end-users of the statistical methods (i.e., applied researchers) in mind. Therefore, I devote considerable time to the readability and comprehensibility of my academic articles; develop user-friendly applications for others to apply analytical techniques; and enjoy presenting about it at conferences and during lectures for bachelor and master students, doctoral candidates, and postdoctoral researchers.
        
        If you have questions or suggestions for collaborations (both methodological or more empirical work), or if you are interested in consultation, please do not hesitate to contact me.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
