---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inference on the Change Point under a High Dimensional Covariance Shift"
authors: ["Abhishek Kaul", "Hongjin Zhang", "Konstantinos Tsampourakis", "admin"]
date: 2023-05-01
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

abstract: "We consider the problem of constructing asymptotically valid confidence intervals for the change point in a high-dimensional covariance shift setting. A novel estimator for the change point parameter is developed, and its asymptotic distribution under high dimen- sional scaling obtained. We establish that the proposed estimator exhibits a sharp Op(ψ−2) rate of convergence, wherein ψ represents the jump size between model parameters before and after the change point. Further, the form of the asymptotic distributions under both a vanishing and a non-vanishing regime of the jump size are characterized. In the former case, it corresponds to the argmax of an asymmetric Brownian motion, while in the latter case to the argmax of an asymmetric random walk. We then obtain the relationship be- tween these distributions, which allows construction of regime (vanishing vs non-vanishing) adaptive confidence intervals. Easy to implement algorithms for the proposed methodology are developed and their performance illustrated on synthetic and real data sets."

# Summary. An optional shortened abstract.
summary: ""

tags: ["High dimensional scaling", "Dynamic graphical models", "Change point"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.jmlr.org/papers/volume24/22-1122/22-1122.pdf
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
projects: ["2023-change-pt-covariate"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
