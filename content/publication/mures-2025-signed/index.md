---
title: "Signed distance function-biased flow importance sampling for implicit neural compression of flow fields"
authors:
- admin
- Miguel Cid Montoya

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-07-02T00:00:00Z"
doi: "10.1111/mice.13526"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-1T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer-Aided Civil and Infrastructure Engineering*"
publication_short: "*Comput-Aided Civ Infrastruct Eng*"

abstract: The rise of exascale supercomputing has motivated an increase in high-fidelity computational fluid dynamics (CFD) simulations. The detail in these simulations, often involving shape-dependent, time-variant flow domains and low-speed, complex, turbulent flows, is essential for fueling innovations in fields like wind, civil, automotive, or aerospace engineering. However, the massive amount of data these simulations produce can overwhelm storage systems and negatively affect conventional data management and postprocessing workflows, including iterative procedures such as design space exploration, optimization, and uncertainty quantification. This study proposes a novel sampling method harnessing the signed distance function (SDF) concept, SDF-biased flow importance sampling (BiFIS) and implicit compression based on implicit neural network representations for transforming large-size, shape-dependent flow fields into reduced-size shape-agnostic images. Designed to alleviate the above-mentioned problems, our approach achieves near-lossless compression ratios of approximately 17000:1, reducing the size of a bridge aerodynamics forced-vibration simulation from roughly 600 GB to about 36 MB while maintaining low reproduction errors, in most cases below 0.5% which is unachievable with other sampling approaches. Our approach also allows for real-time analysis and visualization of these massive simulations and does not involve decompression preprocessing steps that yield full simulation data again. Given that image sampling is a fundamental step for any image-based flow field prediction model, the proposed BiFIS method can significantly improve the accuracy and efficiency of such models, helping any application that relies on precise flow field predictions. The BiFIS code is available on GitHub.

# Summary. An optional shortened abstract.
summary: The rise of exascale supercomputing has motivated an increase in high-fidelity computational fluid dynamics (CFD) simulations. The detail in these simulations, often involving shape-dependent, time-variant flow domains and low-speed, complex, turbulent flows, is essential for fueling innovations in fields like wind, civil, automotive, or aerospace engineering. However, the massive amount of data these simulations produce can overwhelm storage systems and negatively affect conventional data management and postprocessing workflows, including iterative procedures such as design space exploration, optimization, and uncertainty quantification. This study proposes a novel sampling method harnessing the signed distance function (SDF) concept, SDF-biased flow importance sampling (BiFIS) and implicit compression based on implicit neural network representations for transforming large-size, shape-dependent flow fields into reduced-size shape-agnostic images.

tags:
- CFD
- Numerical Simulation
- Neural Networks
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
url_pdf: https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/mice.13526
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
