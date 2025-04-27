---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-12-24
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
          filename: slanted-gradient.svg
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
        Currently, my project concerns the use causal inference techniques (e.g., g-methods, debiased machine learning techniques) for the analysis of longitudinal, observational data in research in psychology and related disciplines. I take an interdisciplinary approach, combining techniques from different modeling traditions and disciplines, and studying how we can best apply them in a social science context.

        I find it important to always keep the end-users of the statistical methods (i.e., applied researchers) in mind. Therefore, I devote considerable time to the readability and comprehensibility of my academic articles; develop user-friendly applications for others to apply analytical techniques; and enjoy presenting about it at conferences and during lectures for bachelor and master students, doctoral candidates, and postdoctoral researchers.
        
        If you have questions or suggestions for collaborations (both methodological or more empirical work), or if you are interested in consultation, please do not hesitate to contact me.
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Featured Publications
      subtitle: ''
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: compact
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
        featured_only: true
    design:
      view: card
      columns: '2'
---
