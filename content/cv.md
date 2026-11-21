---
title: CV
date: 2026-11-13
type: landing

design:
  spacing: '5rem'

# Experience and education are read from `data/authors/admin.yaml`
# (`experience:`, `education:` and `languages:`).
sections:
  # Table of contents (right side on wide screens). Items must match the section titles.
  - block: page-toc
    content:
      items: [Experience, Education, Languages]
    design:
      spacing:
        padding: ['2rem', '0', '0', '0']

  - block: resume-experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: resume-languages
    content:
      title: Languages
      username: admin
---
