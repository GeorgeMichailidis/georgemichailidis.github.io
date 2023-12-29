---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Regularized and Smooth Double Core Tensor Factorization for Heterogeneous Data"
authors: ["Davoud Ataee Tarzanagh", "admin"]
date: 2022-09-01


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

abstract: "We introduce a general tensor model suitable for data analytic tasks for heterogeneous datasets, wherein there are joint low-rank structures within groups of observations, but also discriminative structures across different groups. To capture such complex structures, a double core tensor (DCOT) factorization model is introduced together with a family of smoothing loss functions. By leveraging the proposed smoothing function, the model accurately estimates the model factors, even in the presence of missing entries. A linearized ADMM method is employed to solve regularized versions of DCOT factorizations, that avoid large tensor operations and large memory storage requirements. Further, we establish theoretically its global convergence, together with consistency of the estimates of the model parameters. The effectiveness of the DCOT model is illustrated on several real- world examples including image completion, recommender systems, subspace clustering, and detecting modules in heterogeneous Omics multi-modal data, since it provides more insightful decompositions than conventional tensor methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Double core tensor factorization", "ADMM"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jmlr.org/papers/volume23/20-1002/20-1002.pdf
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
projects: ["2022-tensor-fac"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
