---
title: "Flow-driven prediction of bluff body fluid–structure interaction"
authors:
- admin
- Juan García-Tizón
- Miguel Cid Montoya

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-10-8T00:00:00Z"
doi: "10.1016/j.jweia.2026.106613"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Wind Engineering and Industrial Aerodynamics*"
publication_short: "*J Wind Eng Ind Aerodyn*"

abstract: "Wind-resistant shape design exploration of civil engineering structures fundamentally relies on the accurate interpolation and extrapolation of bluff-body aerodynamic features. Current methodologies typically emulate global, integrated coefficients, such as flutter derivatives and admittance functions, in the frequency domain, adopting black-box models. However, they often fail to capture sudden aerodynamic transitions due to data sparsity and lack the phenomenological information inherent to the fluid–structure interaction (FSI). Wind engineering FSI problems typically deal with complex turbulent fluid fields characterized by multiple flow features and frequencies, time-varying flow domains with moving bodies, and, when designing, bluff body shape variations leading to different flow domains. This study proposes a novel deep learning strategy combining: (1) a dual-band flow superposition approach separating the prediction of flow fields for different frequency bands, (2) the BiFIS sampling strategy for shape-agnostic and accurate prediction of flow fields, and (3) a novel physics-informed FSE-U-Net architecture that conditions flow reconstruction on global physical parameters through feature-wise linear modulation (FiLM), ensuring physical consistency across variable flow regimes. The methodology is validated through the flow-driven prediction of frequency-dependent flutter derivatives using CFD-generated forced vibration flow fields of a bluff bridge deck subject to shape modifications. The code is available on GitHub."

# Summary. An optional shortened abstract.
summary: "Wind-resistant shape design exploration of civil engineering structures fundamentally relies on the accurate interpolation and extrapolation of bluff-body aerodynamic features. Current methodologies typically emulate global, integrated coefficients, such as flutter derivatives and admittance functions, in the frequency domain, adopting black-box models. However, they often fail to capture sudden aerodynamic transitions due to data sparsity and lack the phenomenological information inherent to the fluid–structure interaction (FSI). This study proposes a novel deep learning strategy combining: (1) a dual-band flow superposition approach separating the prediction of flow fields for different frequency bands, (2) the BiFIS sampling strategy for shape-agnostic and accurate prediction of flow fields, and (3) a novel physics-informed FSE-U-Net architecture that conditions flow reconstruction on global physical parameters through feature-wise linear modulation (FiLM), ensuring physical consistency across variable flow regimes."

tags:
- CFD
- Numerical Simulation
- Deep Learning
- Neural Networks
- Convolutional Networks
- URANS
- Fluid-structure Interaction
- Flow Prediction
- Image
- FiLM
- Butterworth Filter
featured: true

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://www.sciencedirect.com/science/article/pii/S0167610526002825/pdfft?md5=20b8c1ce2709a8d501824f81241ac4dd&pid=1-s2.0-S0167610526002825-main.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: https://fse-u-net.github.io
# url_slides: ''
# url_source: 'https://link.springer.com/article/10.1007/s00371-023-02972-1'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'System overview of the proposed flow prediction framework.'
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
