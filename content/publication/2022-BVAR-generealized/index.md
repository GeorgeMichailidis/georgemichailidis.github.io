---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A generalized likelihood-based Bayesian approach for scalable joint regression and covariance selection in high dimensions"
authors: ["Srijata Samanta", "Kshitij Khare", "admin"]
date: 2022-06-03
doi: "https://doi.org/10.1109/TSP.2022.3223214"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Statistics and Computing"
publication_short: ""

abstract: "The paper addresses joint sparsity selection in the regression coefficient matrix and the error precision (inverse covariance) matrix for high-dimensional multivariate regression models in the Bayesian paradigm. The selected sparsity patterns are crucial to help understand the network of relationships between the predictor and response variables, as well as the conditional relationships among the latter. While Bayesian methods have the advantage of providing natural uncertainty quantification through posterior inclusion probabilities and credible intervals, current Bayesian approaches either restrict to specific sub-classes of sparsity patterns and/or are not scalable to settings with hundreds of responses and predictors. Bayesian approaches that only focus on estimating the posterior mode are scalable, but do not generate samples from the posterior distribution for uncertainty quantification. Using a bi-convex regression-based generalized likelihood and spike-and-slab priors, we develop an algorithm called joint regression network selector (JRNS) for joint regression and covariance selection, which (a) can accommodate general sparsity patterns, (b) provides posterior samples for uncertainty quantification, and (c) is scalable and orders of magnitude faster than the state-of-the-art Bayesian approaches providing uncertainty quantification. We demonstrate the statistical and computational efficacy of the proposed approach on synthetic data and through the analysis of selected cancer data sets. We also establish high-dimensional posterior consistency for one of the developed algorithms."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bayesian regression", "spike and slab priors", "high-dimensional data"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://link.springer.com/article/10.1007/s11222-022-10102-5
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
projects: ["2022-BVAR-generalized"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
