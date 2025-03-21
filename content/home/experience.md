---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Recent Experience
subtitle: For complete work history refer to my [curriculum vitae](uploads/cv.pdf).

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: New Jersey Institute of Technology
    company_url: 'https://www.njit.edu/'
    company_logo:
    location: New Jersey
    date_start: '2021-05-01'
    date_end: ''
    description: Designed, implemented, and analyzed algorithms for high performance graph and data analytics. Explored the research process from literature review through algorithm design, implementation, and performance optimization. 
  
  - title: Chapel Programming Language Intern
    company: Hewlett Packard Enterprise
    company_url: 'https://chapel-lang.org/'
    company_logo:
    location:
    date_start: '2024-06-01'
    date_end: '2024-09-01'
    description: Benchmarked high-performance distributed and parallel implementations of graph generation and breadth-first search in Chapel against the Graph500 benchmark that uses C with MPI. Presented results to the Chapel development team and HPE’s High-Performance Computing Advanced Development Organization. Provided actionable feedback to enhance Chapel’s support for irregular applications like graph analytics, including recommendations for improved user support in selecting between processor and network atomics, as well as suggestions for a more flexible communication aggregation library. Integrated this work into the Arachne graph analytics framework, achieving up to 76x speedup in distributed breadth-first search over the original implementation.

  - title: Teaching Assistant
    company: New Jersey Institute of Technology
    company_url: 'https://www.njit.edu/'
    company_logo:
    location: New Jersey
    date_start: '2020-09-01'
    date_end: '2021-04-30'
    description: Instructed lab sessions for 50+ students to demonstrate the practicability of topics learned in lecture. Provided extra tutoring for 20+ students who struggled with the material presented in both lab and lecture

  - title: Data Science Intern
    company: Chubb Insurance
    company_url: 'https://www.chubb.com/us-en/'
    company_logo:
    location: New Jersey
    date_start: '2020-06-01'
    date_end: '2020-08-01'
    description: Researched machine learning classification algorithms best suited for text data.  Created an API that pulled pertinent information from databases, predicted sex given at birth for insurance leads, and returned a new table for their sales team. Managed project through Chubb’s enterprise GitHub and worked on an Agile software development schedule. Presented progress weekly to supervisor and larger data science team.

design:
  columns: '2'
---
