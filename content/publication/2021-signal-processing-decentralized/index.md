---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A decentralized adaptive momentum method for solving a class of min-max optimization problems"
authors: ["Babak Barazandeh", "Tianjian Huang", "admin"]
date: 2021-07-29
doi: "https://doi.org/10.1016/j.sigpro.2021.108245"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Signal Processing"
publication_short: ""

abstract: "Min-max saddle point games have recently been intensely studied, due to their wide range of applications, including training Generative Adversarial Networks (GANs). However, most of the recent efforts for solving them are limited to special regimes such as convex-concave games. Further, it is customarily assumed that the underlying optimization problem is solved either by a single machine or in the case of multiple machines connected in centralized fashion, wherein each one communicates with a central node. The latter approach becomes challenging, when the underlying communications network has low bandwidth. In addition, privacy considerations may dictate that certain nodes can communicate with a subset of other nodes. Hence, it is of interest to develop methods that solve min-max games in a decentralized manner. To that end, we develop a decentralized adaptive momentum (ADAM)-type algorithm for solving min-max optimization problem under the condition that the objective function satisfies a Minty Variational Inequality condition, which is a generalization to convex-concave case. The proposed method overcomes shortcomings of recent non-adaptive gradient-based decentralized algorithms for min-max optimization problems, that do not perform well in practice and require careful tuning. In this paper, we obtain non-asymptotic rates of convergence of the proposed algorithm (coined Dadam ) for finding a (stochastic) first-order Nash equilibrium point and subsequently evaluate its performance on training GANs. The extensive empirical evaluation shows that Dadam outperforms recently developed methods, including decentralized optimistic stochastic gradient for solving such min-max problems."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Non-convex min-max problems", "Distributed optimizerion", "Variational inequality", "First-order Nash equilibria"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S0165168421002826
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
projects: ["2021-signal-processing-decentralized"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
