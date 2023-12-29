---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DAdam: A Consensus-Based Distributed Adaptive Gradient Method for Online Optimization"
authors: ["Parvin Nazari", "Davoud Ataee Tarzanagh", "admin"]
date: 2022-12-07
doi: "https://doi.org/10.1109/TSP.2022.3223214"

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

abstract: "Adaptive optimization methods, such as AdaGrad , RMSProp , and Adam , are widely used in solving large-scale machine learning problems. A number of schemes have been proposed in the literature aiming at parallelizing them, based on communications between peripheral nodes with a central node, but incur high communications cost. To address this issue, we develop a novel consensus-based distributed adaptive moment estimation method ( DAdam ) for online optimization over a decentralized network that enables data parallelization, as well as decentralized computation. The method is particularly useful, since it can accommodate settings where access only to local data is permitted. Further, as established theoretically in this work, it can outperform centralized adaptive algorithms, for certain classes of loss functions used in machine learning applications. We analyze the convergence properties of the proposed algorithm and provide a regret bound on the convergence rate of adaptive moment estimation methods in both online convex and non-convex settings. Empirical results demonstrate that DAdam exhibits also good performance in practice and compares favorably to competing online optimization methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Decentralized optimization", "Online Learning", "Regret bound", "Adaptive methods"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/9973382
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
projects: ["2022-DADAM"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
