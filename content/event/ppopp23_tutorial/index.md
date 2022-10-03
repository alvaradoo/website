---
title: Interactive Large-Scale Data and Graph Analytics

event: Principles and Practice of Parallel Programming 2023
event_url: https://conf.researchr.org/home/PPoPP-2023

location:
address:
  street:
  city: Montreal
  region: Quebec
  postcode: 
  country: Canada

summary: A tutorial outlining how to use our graph algorithms for larg-scale graph and data analytics.
abstract: There is an ever-growing need for data analytical tools that can handle massive data sets. Arkouda is a Python framework with a Chapel back-end created with the intention to scale NumPy operations at scale for datasets that exceeds tens of terabytes in size. The Python front-end allows for data scientists to utilize the functionality of Arkouda to carry out expensive high-performance computing (HPC) kernels that require the usage of large distributed arrays. Arkouda is not designed with the intention to totally replace libraries like Pandas or NumPy, but rather provide the capability to handle datasets that are massive in size in a highly-scalable environment. The goal is to create an environment that is beneficial for exploratory data and graph analysis (EDA) while staying simple enough for all data scientists to be able to pick up without an issue. Recently, our group at NJIT has created a new graph analysis library based off Arkouda under the name Arachne. The purpose of this tutorial is to provide a comprehensive view of typical pipelines that can be built and integrated with Arkouda. We will first begin by introducing an overview of Arkouda for and then move to Arachne. Examples will be provided with the questions and problems data scientists may want to answer and how Arkouda and Arachne can fit in to solve said problems. We will conclude with questions and further work that our group is planning for Arachne. Both Arkouda and Arachne are open-source and found on GitHub.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-02-25T8:00:00Z'
date_end: '2023-02-26T17:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [admin, Naren Khatwani, Zhihui Du, and David Bader]
tags: [tutorial]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: https://github.com/njit-hpc-initiative/tutorial-arkouda-njit
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
