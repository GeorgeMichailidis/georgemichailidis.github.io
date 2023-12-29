---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Bayesian nested LASSO for mixed frequency regression models"
authors: ["Satyajit Ghosh", "Kshitij Khare", "admin"]
date: 2023-09-01
doi: "https://doi.org/10.1214/22-AOAS1718"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-25T00:00:00Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Annals of Applied Statistics"
publication_short: ""

abstract: "Even though many time series are sampled at different frequencies, their joint evolution is usually modeled and analyzed at a common low frequency. The mixed data sampling (MIDAS) framework was developed to enable joint modeling of mixed frequency temporally evolving data with GDP forecasting as a key motivating application. In this paper we develop a fully Bayesian method to jointly estimate both the appropriate lag as well as the regression coefficients in linear models wherein the response is measured at a lower frequency than the predictors. This is accomplished through a novel prior distribution, coined the Bayesian nested lasso (BNL), that leads to principled selection of the lag of the predictors, reduces the effective number of model parameters through sparsity induced by the lasso component and finally incorporates desirable decay patterns over time lags in the magnitude of the corresponding regression coefficients. Further, it is easy to obtain samples from the posterior distribution due to the closed form expressions for the conditional distributions of the model parameters. Numerical results, obtained from synthetic and macroeconomic data, illustrate the good performance of the proposed Bayesian framework in parameter selection and estimation and in the key task of GDP forecasting."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Mixed-Frequency Data", "Bayesian nested Lasso", "Nowcasting"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://projecteuclid.org/journals/annals-of-applied-statistics/volume-17/issue-3/The-Bayesian-nested-lasso-for-mixed-frequency-regression-models/10.1214/22-AOAS1718.short?tab=ArticleLink
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
projects: ["2023-bayesian-nested"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
