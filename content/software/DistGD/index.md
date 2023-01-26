---
title: DistGD
summary: A Distributed Optimization Package in R using Gradient Descent.
featured: true
tags:
  - R
 
type: project

# date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Three-node example
  focal_point: Smart
  

links:
- icon: github
  icon_pack: fab
  name: bosafoagyare/DistGD 
  url: https://github.com/bosafoagyare/DistGD
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

The goal of DistGD (Distributed Gradient Descent) is to efficiently optimize a global objective function expressed as a sum of a list of local objective functions belonging to different agents situated in a network via a cluster architecture like Spark. You supply a list of local objective functions, weights of the connections between the agents, initialize a vector initial values, and it takes care of the details, returning the optimal values. See [the github page](https://github.com/bosafoagyare/DistGD#installation) for more a vignette. 

