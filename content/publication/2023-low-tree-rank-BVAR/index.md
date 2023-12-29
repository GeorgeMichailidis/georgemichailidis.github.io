---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Low Tree-Rank Bayesian Vector Autoregression Models"
authors: ["Leo L Duan", "Zeyu Yuwen", "admin", "Zhengwu Zhang"]
date: 2023-09-01
#doi: "https://doi.org/10.1016/j.ijforecast.2023.08.003"

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

abstract: "Vector autoregression has been widely used for modeling and analysis of multivariate time series data. In high-dimensional settings, model parameter regularization schemes inducing sparsity yield interpretable models and achieved good forecasting performance. However, in many data applica- tions, such as those in neuroscience, the Granger causality graph estimates from existing vector autoregression methods tend to be quite dense and difficult to interpret, unless one compromises on the goodness-of-fit. To address this issue, this paper proposes to incorporate a commonly used structural assumption — that the ground-truth graph should be largely connected, in the sense that it should only contain at most a few components. We take a Bayesian approach and develop a novel tree-rank prior distribution for the regression coefficients. Specifically, this prior distribution forces the non-zero coefficients to appear only on the union of a few spanning trees. Since each span- ning tree connects p nodes with only (p − 1) edges, it effectively achieves both high connectivity and high sparsity. We develop a computationally efficient Gibbs sampler that is scalable to large sample size and high dimension. In analyzing test-retest functional magnetic resonance imaging data, our model produces a much more interpretable graph estimate, compared to popular exist- ing approaches. In addition, we show appealing properties of this new method, such as efficient computation, mild stability conditions and posterior consistency."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Graph Rank", "Structural Vector Autoregression", "Gibbs Sampling"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jmlr.org/papers/volume24/22-0360/22-0360.pdf
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
projects: ["2023-low-tree-rank-BVAR"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
