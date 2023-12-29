---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A multi-task encoder-dual-decoder framework for mixed frequency data prediction"
authors: ["Jiahe Lin", "admin"]
date: 2023-09-10
doi: "https://doi.org/10.1016/j.ijforecast.2023.08.003"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Forecasting"
publication_short: ""

abstract: "Mixed-frequency data prediction tasks are pertinent in various application domains, in which one leverages progressively available high-frequency data to forecast/nowcast the low-frequency ones. Existing methods in the literature tailored to such tasks are mostly linear in nature; depending on the specific formulation, they largely rely on the assumption that the (latent) processes that govern the dynamics of the high- and low-frequency blocks of variables evolve at the same frequency, either the low or the high one. This paper develops a neural network-based multi-task shared-encoder-dual-decoder framework for joint multi-horizon prediction of both the low- and high-frequency blocks of variables, wherein the encoder/decoder modules can be either long short-term memory or transformer ones. It addresses forecast/nowcast tasks in a unified manner, leveraging the encoder–decoder structure that can naturally accommodate the mixed-frequency nature of the data. The proposed framework exhibited competitive performance when assessed on both synthetic data experiments and two real datasets of US macroeconomic indicators and electricity data."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Mixed Frequency Data Prediction", "Deep Neural Networks", "Multi-Task Learning"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S016920702300078X?ref=pdf_download&fr=RR-2&rr=8049c32e9d1ec348
url_code: https://github.com/GeorgeMichailidis/multi-task-mixed-freq

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
projects: ["2023-mixed-frequency-DNN"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
