---
title: "Low-Rank Expectile Representations of a Data Matrix, with Application to Diurnal Heart Rates"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuge Ouyang
- Yunxuan Tang
- admin

draft: false

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-12-06T00:00:00Z"
doi: https://doi.org/10.48550/arXiv.2412.04765

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: 
 - "3"

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: Low-rank matrix factorization is a powerful tool for understanding the structure of 2-way data, and is usually accomplished by minimizing a sum of squares criterion. Expectile analysis generalizes squared-error loss by introducing asymmetry, allowing tail behavior to be elicited. Here we present a framework for low-rank expectile analysis of a data matrix that incorporates both additive and multiplicative effects, utilizing expectile loss, and accommodating arbitrary patterns of missing data. The representation can be fit with gradient-descent. Simulation studies demonstrate the accuracy of the structure recovery. Using diurnal heart rate data indexed by person-days versus minutes within a day, we find divergent behavior for lower versus upper expectiles, with the lower expectiles being much more stable within subjects across days, while the upper expectiles are much more variable, even within subjects.  

# Summary. An optional shortened abstract.
summary: ''

tags: []
categories: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2412.04765
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Row and column effects of heart rates'
  focal_point: Smart
  placement: 1
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
