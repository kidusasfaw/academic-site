---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Partially observed Markov processes with spatial structure via the R package spatPomp"
authors: [Kidus Asfaw, Joonha Park, Aaron King, Edward Ionides]
date: 2021-05-03T21:44:05-04:00
doi: "https://doi.org/10.48550/arXiv.2101.01157"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-24T21:44:05-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Partially observed Markov processes with spatial structure via the R package spatPomp"
publication_short: "Partially observed Markov processes with spatial structure via the R package spatPomp"

abstract: "We address inference for a partially observed nonlinear non-Gaussian latent stochastic system comprised of interacting units. Each unit has a state, which may be discrete or continuous, scalar 
or vector valued. In biological applications, the state may represent a structured population or the abundances of a collection of species at a single location. Units can have spatial locations, allowing 
the description of spatially distributed interacting populations arising in ecology, epidemiology and elsewhere. We consider models where the collection of states is a latent Markov process, and a time 
series of noisy or incomplete measurements is made on each unit. A model of this form is called a spatiotemporal partially observed Markov process (SpatPOMP). The R package spatPomp provides an 
environment for implementing SpatPOMP models, analyzing data, and developing new inference approaches. We describe the spatPomp implementations of some methods with scaling properties suited to SpatPOMP 
models. We demonstrate the package on a simple Gaussian system and on a nontrivial epidemiological model for measles transmission within and between cities. We show how to construct user-specified 
SpatPOMP models within spatPomp."

# Summary. An optional shortened abstract.
summary: ""

tags: [Particle filter, sequential Monte Carlo, Markov process, spatiotemporal inference, metapopulation dynamics]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://doi.org/10.48550/arXiv.2101.01157"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
