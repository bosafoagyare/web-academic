---
title: "A Simulation Study on High Dimensional Shrinkage Feature
Selection Using MCMC Methods"

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

date: "2023-26-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-26-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: 
 - "4"

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: Linear regression sometimes present us with the problem of 
 high dimensionality –especially when the covariates, p is far greater than
 the sample size, n. A frequentist approach to tackling such problems include
 adopting shrinkage methods via penalization. However, penalization methods
 present yet another challenge of quantifying parameter uncertainties.
 Bayesian approach gives us the power to quantity parameters via estimating
 the posterior distribution for such parameters using Markov Chain
 Monte Carlo (MCMC) techniques. With such high dimensional shrinkage methods,
 we need super fast MCMC algorithms that are efficient and 
 computationally relative inexpensive. In this simulation study, 
 we compare and show that the two-Block Gibbs samplers (2BG) is a more efficient
 state of the art MCMC algorithm relative to the three-Block Gibbs samplers (3BG)
 method in estimating the posterior distributions of two commonly used
 Bayesian shrinkage models, viz: the Bayesian Lasso (BL) and the Spike-and-Slab
 shrinkage priors. Our criteria for evaluation include the one-lag autocorrelation
 and the average effective sample size per second, Neff/T. Consequently,
 we apply these methods on the protein expression genetics data from the
 National cancer Institute. 

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

url_pdf: 'osafoagyare-bayesianshrikage-2023.pdf'
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
