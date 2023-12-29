---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On adaptive Linear–Quadratic regulators"
authors: ["Mohamad Kazem Shirani Faradonbeh", "Ambuj Tewari", "admin"]
date: 2020-07-20
doi: "https://doi.org/10.1016/j.automatica.2020.108982"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Automatica"
publication_short: ""

abstract: "Performance of adaptive control policies is assessed through the regret with respect to the optimal regulator, which reflects the increase in the operating cost due to uncertainty about the dynamics parameters. However, available results in the literature do not provide a quantitative characterization of the effect of the unknown parameters on the regret. Further, there are problems regarding the efficient implementation of some of the existing adaptive policies. Finally, results regarding the accuracy with which the system’s parameters are identified are scarce and rather incomplete.

This study aims to comprehensively address these three issues. First, by introducing a novel decomposition of adaptive policies, we establish a sharp expression for the regret of an arbitrary policy in terms of the deviations from the optimal regulator. Second, we show that adaptive policies based on slight modifications of the Certainty Equivalence scheme are efficient. Specifically, we establish a regret of (nearly) square-root rate for two families of randomized adaptive policies. The presented regret bounds are obtained by using anti-concentration results on the random matrices employed for randomizing the estimates of the unknown parameters. Moreover, we study the minimal additional information on dynamics matrices that using them the regret will become of logarithmic order. Finally, the rates at which the unknown parameters of the system are being identified are presented."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Certainty Equivalence", "Randomized algorithms", "Thompson sampling", "Adaptive policies"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S0005109820301801
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
projects: ["2020-linear-quadratic"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
