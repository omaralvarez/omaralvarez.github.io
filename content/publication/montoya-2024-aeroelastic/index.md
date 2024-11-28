---
title: "Aeroelastic force prediction via temporal fusion transformers"
authors:
- Miguel Cid Montoya
- Ashustosh Mishra
- Sumit Verma
- admin
- Carlos E. Rubio‐Medrano
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-11-28T00:00:00Z"
doi: "10.1007/s00371-023-02972-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer-Aided Civil and Infrastructure Engineering*"
publication_short: "*Comput-Aided Civ Infrastruct Eng*"

abstract: Aero-structural shape design and optimization of bridge decks rely on accurately estimating their self-excited aeroelastic forces within the design domain. The inherent nonlinear features of bluff body aerodynamics and the high cost of wind tunnel tests and computational fluid dynamics (CFD) simulations make their emulation as a function of deck shape and reduced velocity challenging. State-of-the-art methods address deck shape tailoring by interpolating discrete values of integrated flutter derivatives (FDs) in the frequency domain. Nevertheless, more sophisticated strategies can improve surrogate accuracy and potentially reduce the required number of samples. We propose a time domain emulation strategy harnessing temporal fusion transformers (TFTs) to predict the self-excited forces time series before their integration into FDs. Emulating aeroelastic forces in the time domain permits the inclusion of time-series amplitudes, frequencies, phases, and other properties in the training process, enabling a more solid learning strategy that is independent of the self-excited forces modeling order and the inherent loss of information during the identification of FDs. TFTs' long- and short-term context awareness, combined with their interpretability and enhanced ability to deal with static and time-dependent covariates, make them an ideal choice for predicting unseen aeroelastic forces time series. The proposed TFT-based metamodel offers a powerful technique for drastically improving the accuracy and versatility of wind-resistant design optimization frameworks.

# Summary. An optional shortened abstract.
summary: Aero-structural shape design and optimization of bridge decks rely on accurately estimating their self-excited aeroelastic forces within the design domain. The inherent nonlinear features of bluff body aerodynamics and the high cost of wind tunnel tests and computational fluid dynamics (CFD) simulations make their emulation as a function of deck shape and reduced velocity challenging. We propose a time domain emulation strategy harnessing temporal fusion transformers (TFTs) to predict the self-excited forces time series before their integration into FDs.

tags:
- CFD
- Numerical Simulation
- Neural Networks
- Aeroelastic Force Interpolation
- Time Series
- Temporal Fusion Transformers
- Deep Learning
featured: true

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/mice.13381
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://link.springer.com/article/10.1007/s00371-023-02972-1'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'System overview of the proposed aeroelastic force interpolation framework.'
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
