---
title: "NeVF: Representing CFD simulations as neural flow volume fields for efficient compression, reconstruction, and analysis"
authors:
- admin
- Miguel Cid Montoya

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-06-16T00:00:00Z"
doi: "10.1016/j.cacaie.2026.100125"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer-Aided Civil and Infrastructure Engineering*"
publication_short: "*Comput-Aided Civ Infrastruct Eng*"

abstract: Computational Fluid Dynamics (CFD) simulations of civil engineering aerodynamics, which are commonly characterized by complex three-dimensional flow fields, generate massive spatiotemporal datasets, creating significant storage and computational bottlenecks that heavily constrain iterative engineering workflows. To overcome these challenges, this paper presents a novel two-stage compression framework that models three-dimensional flow field data using Neural Flow Volume Fields (NeVF). The first stage employs a distance field-biased flow importance sampling (3D BiFIS) strategy to reduce data dimensionality intelligently; this approach selectively extracts key near-wall flow information, guided by surface proximity to construct a “relaxed” image volume. Subsequently, a deep network, leveraging positional encodings and disentangled spatio-temporal attention mechanisms, highly compresses this volumetric representation. The effectiveness of the resulting flow field representation is evaluated using a comprehensive 3D Large-Eddy Simulation (LES) dataset of a bluff single-box bridge deck, characterized by complex, uncorrelated spanwise flow features. Results demonstrate high data compression rates of ∼7000:1 to ∼30,000:1 while preserving high-fidelity near-body aerodynamic flow features, enabling accurate estimation of wind-induced forces. Ultimately, our methodology streamlines efficient storage, reconstruction, and rapid analysis of exascale CFD datasets, unlocking potential new applications for deep learning emulation and data-intensive tasks, such as, uncertainty quantification and flow-driven aero-structural optimization. The neural compression code is available on GitHub.

# Summary. An optional shortened abstract.
summary: Computational Fluid Dynamics (CFD) simulations of civil engineering aerodynamics, which are commonly characterized by complex three-dimensional flow fields, generate massive spatiotemporal datasets. To overcome these challenges, this paper presents a novel two-stage compression framework that models three-dimensional flow field data using Neural Flow Volume Fields (NeVF). The first stage employs a distance field-biased flow importance sampling (3D BiFIS) strategy to reduce data dimensionality intelligently; this approach selectively extracts key near-wall flow information, guided by surface proximity to construct a “relaxed” image volume. Subsequently, a deep network, leveraging positional encodings and disentangled spatio-temporal attention mechanisms, highly compresses this volumetric representation. The effectiveness of the resulting flow field representation is evaluated using a comprehensive 3D Large-Eddy Simulation (LES) dataset of a bluff single-box bridge deck, characterized by complex, uncorrelated spanwise flow features.

tags:
- CFD
- Numerical Simulation
- Neural Networks
- Convolutional Networks
- Transformers
- LES
- Compression
- Image
- Sampling
- Implicit Neural Representations
- Implicit Representations
- Deep Learning
featured: true

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://www.sciencedirect.com/science/article/pii/S1093968726031117/pdfft?md5=e938bb1a4863999573698c8be612eb7a&pid=1-s2.0-S1093968726031117-main.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: https://nevf-cfd.github.io
# url_slides: ''
# url_source: 'https://link.springer.com/article/10.1007/s00371-023-02972-1'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'System overview of the proposed image sampling framework.'
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
