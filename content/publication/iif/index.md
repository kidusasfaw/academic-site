---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Bagged filters for partially observed interacting systems"
authors: [Edward Ionides, Kidus Asfaw, Joonha Park, Aaron King]
date: 2020-07-24T21:44:05-04:00
doi: "10.1080/01621459.2021.1974867"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-24T21:44:05-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bagged filters for partially observed interacting systems"
publication_short: "Bagged filters for partially observed interacting system"

abstract: "Statistical inference for high-dimensional partially observed, nonlinear, stochastic processes is a methodological challenge with applications including spatiotemporal analysis of epidemiological and ecological systems. Standard particle filter algorithms, which provide an effective approach for general low-dimensional partially observed Markov processes, suffer from a curse of dimensionality that limits their applicability beyond low-dimensional systems. We show that many independent Monte Carlo calculations, none of which, by itself, attempts to solve the filtering problem, can be combined to give a global filtering solution that theoretically beats the curse of dimensionality under weak coupling conditions. The independent Monte Carlo calculations are called islands, and the corresponding algorithm is called a basic island filter (BIF). Carrying out an operation called adapted simulation on each island results in a variant called an adapted simulation island filter (ASIF). Adapted simulation can be implemented using a Monte Carlo technique called intermediate resampling to give the ASIF-IR algorithm which has improved theoretical and empirical scaling. Our focus is on evaluation of the likelihood function, but our algorithms and theory are also pertinent to latent state estimation. We demonstrate our methodology on coupled population dynamics arising in the epidemiology of infectious disease. In this context, our methods retain the generality of particle filter algorithms while scaling to systems an order of magnitude larger."

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

url_pdf: "https://doi.org/10.1080/01621459.2021.1974867"
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
