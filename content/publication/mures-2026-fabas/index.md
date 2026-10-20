---
title: "FABaS: Flow activity-biased importance sampling for deep learning image-based flow compression and prediction"
authors:
- admin
- Abrahan Dopazo
- Miguel Cid Montoya

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-07-20T00:00:00Z"
doi: "10.1016/j.jweia.2026.106544"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Wind Engineering and Industrial Aerodynamics*"
publication_short: "*J Wind Eng Ind Aerodyn*"

abstract: Flow field compression is a key milestone for the feasible implementation of deep learning (DL) models at scale and the efficient storage of the flow datasets required for their training. Sampling strategies represent a fundamental step in vision-based compression techniques, directly conditioning both model accuracy and compression ratios. Their main objective is to accurately capture all necessary flow features for reproducing the phenomena of interest, which typically involves extracting wind-induced forces while simultaneously resolving flow characteristics in the near and far wakes. However, accurately identifying flow information in those regions requires conflicting sampling criteria. To address this challenge, this study proposes an importance sampling strategy guided by flow activity to automatically identify and focus on high-activity regions within the flow domain, combining Signed Distance Functions (SDFs) and vorticity fields. The proposed Flow Activity-Based Importance Sampling (FABaS) method achieves near-lossless compression ratios of 37718:1 while guaranteeing accurate reproduction of flow features, with a Mean Absolute Percentage Error (MAPE) of 0.063%, for precise surface force extraction in the boundary layer region and far wake. Consequently, this technique is a powerful tool for deep learning compression and prediction of flow field data.

# Summary. An optional shortened abstract.
summary: Flow field compression is a key milestone for the feasible implementation of deep learning (DL) models at scale and the efficient storage of the flow datasets required for their training. Sampling strategies represent a fundamental step in vision-based compression techniques, directly conditioning both model accuracy and compression ratios. Their main objective is to accurately capture all necessary flow features for reproducing the phenomena of interest, which typically involves extracting wind-induced forces while simultaneously resolving flow characteristics in the near and far wakes. However, accurately identifying flow information in those regions requires conflicting sampling criteria. To address this challenge, this study proposes an importance sampling strategy guided by flow activity to automatically identify and focus on high-activity regions within the flow domain, combining Signed Distance Functions (SDFs) and vorticity fields.

tags:
- CFD
- Numerical Simulation
- Neural Networks
- Convolutional Networks
- Transformers
- URANS
- Compression
- Image
- Sampling
- Implicit Neural Representations
- Implicit Representations
- Deep Learning
featured: false

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://www.sciencedirect.com/science/article/pii/S0167610526002138/pdfft?md5=e9faeb36380fdbb06473eee686b1267f&pid=1-s2.0-S0167610526002138-main.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: https://fabas-sampling.github.io
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
