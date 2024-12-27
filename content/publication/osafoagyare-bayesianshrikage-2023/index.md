---
title: "Enhancing Computational Efficiency in High-Dimensional Bayesian Analysis: Applications to Cancer Genomics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

draft: false

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-04-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-26-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: 
 - "3"

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: In this study, we present a comprehensive evaluation of the Two-Block Gibbs (2BG) sampler as a robust alternative to the traditional Three-Block Gibbs (3BG) sampler in Bayesian shrinkage models. Through extensive simulation studies, we demonstrate that the 2BG sampler exhibits superior computational efficiency and faster convergence rates, particularly in high-dimensional settings where the ratio of predictors to samples is large. We apply these findings to real-world data from the NCI-60 cancer cell panel, leveraging gene expression data to predict protein expression levels. Our analysis incorporates feature selection, identifying key genes that influence protein expression while shedding light on the underlying genetic mechanisms in cancer cells. The results indicate that the 2BG sampler not only produces more effective samples than the 3BG counterpart but also significantly reduces computational costs, thereby enhancing the applicability of Bayesian methods in high-dimensional data analysis. This contribution extends the understanding of shrinkage techniques in statistical modeling and offers valuable insights for cancer genomics research. 

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

url_pdf: https://arxiv.org/abs/2410.16741
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
  caption: 'MCMC traceplot and density'
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
