---
# Leave the homepage title empty to use the site title
title: ""
date: 2026-11-13
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # Introduction: photo, name, role, affiliations, links, bio, interests.
  # Profile data and introduction text (`bio:`) live in `data/authors/admin.yaml`.
  # (Setting `content.text` here would REPLACE the bio.)
  # `show_about_heading` and `show_education` are added by the local override in
  # `layouts/_partials/hbx/blocks/resume-biography-3/block.html`.
  - block: resume-biography-3
    content:
      username: admin
      headings:
        interests: Interests
      # The "Download CV" button, experience and education are on the CV page (`content/cv.md`).
    design:
      show_about_heading: false # hide the "Professional Summary" heading
      show_education: false # education is shown on the CV page
      # Section padding [top, right, bottom, left]. Theme default is 6rem top and bottom.
      spacing:
        padding: ['1.5rem', '0', '3rem', '0']
      avatar:
        size: large
        shape: circle
      name:
        size: md # xs | sm | md | lg | xl
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
      biography:
        style: "max-width: 70ch;"
---
