---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Bayesian Spiked Laplacian Graphs"
authors: ["Leo L Duan", "admin", "Mingzhou Ding"]
date: 2023-01-01
#doi: ""

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

abstract: "In network analysis, it is common to work with a collection of graphs that exhibit hetero- geneity. For example, neuroimaging data from patient cohorts are increasingly available. A critical analytical task is to identify communities, and graph Laplacian-based meth- ods are routinely used. However, these methods are currently limited to a single network and also do not provide measures of uncertainty on the community assignment. In this work, we first propose a probabilistic network model called the “Spiked Laplacian Graph” that considers an observed network as a transform of the Laplacian and degree matrices of the network generating process, with the Laplacian eigenvalues modeled by a modified spiked structure. This effectively reduces the number of parameters in the eigenvectors, and their sign patterns allow efficient estimation of the underlying community structure. Further, the posterior distribution of the eigenvectors provides uncertainty quantification for the community estimates. Second, we introduce a Bayesian non-parametric approach to address the issue of heterogeneity in a collection of graphs. Theoretical results are estab- lished on the posterior consistency of the procedure and provide insights on the trade-off between model resolution and accuracy. We illustrate the performance of the methodology on synthetic data sets, as well as a neuroscience study related to brain activity in working memory."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Mixed-Effect Eigendecomposition", "Normalized Graph Cut", "Stiefel Manifold"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jmlr.org/papers/volume24/20-1206/20-1206.pdf
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
projects: ["2023-bayesian-laplacian"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
