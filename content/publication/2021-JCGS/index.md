---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Fast and Scalable Algorithm for Detection of Structural Breaks in Big VAR Models"
authors: ["Abolfazl Safikhani", "Yue Bai", "admin"]
date: 2021-08-02
doi: "https://doi.org/10.1080/10618600.2021.1950005"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational and Graphical Statistics"
publication_short: ""

abstract: "Many real time series datasets exhibit structural changes over time. A popular model for capturing their temporal dependence is that of vector autoregressions (VAR), which can accommodate structural changes through time evolving transition matrices. The problem then becomes to both estimate the (unknown) number of structural break points, together with the VAR model parameters. An additional challenge emerges in the presence of very large datasets, namely on how to accomplish these two objectives in a computational efficient manner. In this article, we propose a novel procedure which leverages a block segmentation scheme (BSS) that reduces the number of model parameters to be estimated through a regularized least-square criterion. Specifically, BSS examines appropriately defined blocks of the available data, which when combined with a fused lasso-based estimation criterion, leads to significant computational gains without compromising on the statistical accuracy in identifying the number and location of the structural breaks. This procedure is further coupled with new local and exhaustive search steps to consistently estimate the number and relative location of the break points. The procedure is scalable to big high-dimensional time series datasets with a computational complexity that can achieve O(sqrt-n),where n is the length of the time series (sample size), compared to an exhaustive procedure that requires O(n) steps. Extensive numerical work on synthetic data supports the theoretical findings and illustrates the attractive properties of the procedure. Finally, an application to a neuroscience dataset exhibits its usefulness in applications. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["High-dimensional time series", "Block segmentation", "Piecewise stationarity"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.tandfonline.com/doi/full/10.1080/10618600.2021.1950005
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
projects: ["2021-JCGS"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
