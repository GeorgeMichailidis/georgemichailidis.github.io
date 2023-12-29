---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sequential change-point detection in high-dimensional Gaussian graphical models"
authors: ["Hossein Keshavarz", "admin", "Yves Atchade"]
date: 2020-06-01

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Machine Learning Research"
publication_short: "JMLR"

abstract: "High dimensional piecewise stationary graphical models represent a versatile class for mod- elling time varying networks arising in diverse application areas, including biology, eco- nomics, and social sciences. There has been recent work in offline detection and estimation of regime changes in the topology of sparse graphical models. However, the online setting remains largely unexplored, despite its high relevance to applications in sensor networks and other engineering monitoring systems, as well as financial markets. To that end, this work introduces a novel scalable online algorithm for detecting an unknown number of abrupt changes in the inverse covariance matrix of sparse Gaussian graphical models with small delay. The proposed algorithm is based upon monitoring the conditional log-likelihood of all nodes in the network and can be extended to a large class of continuous and discrete graphical models. We also investigate asymptotic properties of our procedure under certain mild regularity conditions on the graph size, sparsity level, number of samples, and pre- and post-changes in the topology of the network. Numerical works on both synthetic and real data illustrate the good performance of the proposed methodology both in terms of computational and statistical efficiency across numerous experimental settings."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Sequential change-point detection", "Gaussian graphical model", "Asymptotic analysis"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jmlr.org/papers/volume21/18-410/18-410.pdf
#url_code: 

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
projects: ["2020-sequential-change-pt"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
