---
title: "Symbolic Regression enabled prediction of flutter derivatives"
authors:
- Miguel Cid Montoya
- admin
- Juan García-Tizón
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-03-20T00:00:00Z"
doi: "10.1016/j.awe.2026.100107"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Advances in Wind Engineering*"
publication_short: "*AWE*"

abstract: Precisely emulating aeroelastic phenomena and fluid-structure interaction (FSI) parameters as a function of bluff body shape, largely governed by complex aerodynamics, presents a significant challenge. Moreover, the emulation of bluff body aerodynamics for design optimization is not limited to geometric variables; its dependence on key aeroelastic operational parameters, such as reduced velocity and mean angle of attack, is critical for evaluating the structure's wind-induced responses. The absence of closed-form analytical expressions makes the use of surrogate modeling and machine learning (ML) techniques essential for this task. However, a common limitation of traditional emulation methods is the a priori choice of a trend function. This selection, often guided by engineering experience, fundamentally constrains the model’s flexibility and its ability to reproduce target aeroelastic parameters or responses accurately. Symbolic Regression (SR) offers a viable alternative as a trend model-free methodology that learns from the data and determines the optimal functional form of the model, along with its associated parameters. It circumvents the need for predefined basis functions that can negatively impact predictive performance. This study proposes a two-stage SR methodology for search and refinement of discovered expressions and examines its efficacy for emulating FSI parameters, specifically focusing on predicting the flutter derivatives of a bluff bridge deck as a multivariate function of its geometric shape, reduced velocity, and angle of attack. Results show that our Symbolic Regression methodology outperforms conventional Kriging surrogates when predicting responses for unseen data samples, while simultaneously offering superior smoothness, compactness, and interpretability, thus avoiding the “black-box” approach that most surrogate models provide. These findings highlight the proposed SR strategy as a robust and promising approach for the design exploration of bluff body aerodynamics.

# Summary. An optional shortened abstract.
summary: Precisely emulating aeroelastic phenomena and fluid-structure interaction (FSI) parameters as a function of bluff body shape, largely governed by complex aerodynamics, presents a significant challenge. Symbolic Regression (SR) offers a viable alternative as a trend model-free methodology that learns from the data and determines the optimal functional form of the model, along with its associated parameters. It circumvents the need for predefined basis functions that can negatively impact predictive performance. This study proposes a two-stage SR methodology for search and refinement of discovered expressions and examines its efficacy for emulating FSI parameters, specifically focusing on predicting the flutter derivatives of a bluff bridge deck as a multivariate function of its geometric shape, reduced velocity, and angle of attack.

tags:
- CFD
- Numerical Simulation
- Symbolic Regression
- Flutter Derivative Interpolation
featured: false

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://www.sciencedirect.com/science/article/pii/S2950601826000096/pdfft?md5=abb110edf33dfa384ed96dd66642c1cc&pid=1-s2.0-S2950601826000096-main.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: https://sr-flutter.github.io
# url_slides: ''
# url_source: 'https://link.springer.com/article/10.1007/s00371-023-02972-1'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'System overview of the proposed flutter derivative interpolation framework.'
  focal_point: "Right"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
