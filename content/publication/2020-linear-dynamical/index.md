---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "System identification of high-dimensional linear dynamical systems with serially correlated output noise components"
authors: ["Jiahe Lin", "admin"]
date: 2020-08-31
doi: "https://doi.org/10.1109/TSP.2020.3020397"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Signal Processing"
publication_short: ""

abstract: "We consider identification of linear dynamical systems comprising of high-dimensional signals, where the output noise components exhibit strong serial, and cross-sectional correlations. Although such settings occur in many modern applications, such dependency structure has not been fully incorporated in existing approaches in the literature. In this paper, we explicitly incorporate the dependency structure present in the output noise through lagged values of the observed multivariate signals. We formulate a constrained optimization problem to identify the space spanned by the latent states, and the transition matrices of the lagged values simultaneously, wherein the constraints reflect the low rank nature of the state information, and the sparsity of the transition matrices. We establish theoretical properties of the estimators, and introduce an easy-to-implement computational procedure for empirical applications. The performance of the proposed approach, and the implementation procedure is evaluated on synthetic data, and compared with competing approaches, and further illustrated on a data set involving weekly stock returns of 75 US large financial institutions for the 2001-2017 period."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Alternating minimization", "Convex Optimization", "High-probability error bounds"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/9181471
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
projects: ["2020-linear-dynamical"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
