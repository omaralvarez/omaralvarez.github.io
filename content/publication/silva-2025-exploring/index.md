---
title: "Exploring the effects of synthetic data generation: a case study on autonomous driving for semantic segmentation"
authors:
- Manuel Silva
- Antonio Seoane
- admin
- Antonio M. López
- Jose A. Iglesias-Guitian
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-02-07T00:00:00Z"
doi: "10.1007/s00371-025-03811-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The Visual Computer*"
publication_short: "*Vis Comput*"

abstract: Rendering 3D virtual scenarios has become a popular alternative for generating per-pixel-labeled image datasets, especially in fields like autonomous driving. The approach is valuable for training neural perception models, such as semantic segmentation models, particularly when data might be scarce, expensive, or difficult to collect. However, fundamental questions persist within the research community regarding the generation and processing of these synthetic images, particularly a better understanding of the key factors influencing the performance of deep learning models trained with such synthetic images. In response, we conducted a series of experiments to elucidate the impact that common aspects involved in the generation of rendered synthetic images may have on the performance of neural semantic segmentation tasks. Our study used a recent autonomous driving synthetic dataset as our main testbed, allowing us to investigate the effect of different approaches when modeling their geometric, material, and lighting details. We also studied the impact of rendering noise, typically produced by path-tracing algorithms, as well as the impact of using different color transformations and tonemapping algorithms.

# Summary. An optional shortened abstract.
summary: Rendering 3D virtual scenarios has become a popular alternative for generating per-pixel-labeled image datasets, especially in fields like autonomous driving. The approach is valuable for training neural perception models, such as semantic segmentation models, particularly when data might be scarce, expensive, or difficult to collect. However, fundamental questions persist within the research community regarding the generation and processing of these synthetic images, particularly a better understanding of the key factors influencing the performance of deep learning models trained with such synthetic images.

tags:
- Semantic Segmentation
- Rendering
- Synthetic Data Generation
- 3D
- Autonomous Driving
- Neural Networks
- Deep Learning
featured: false

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://link.springer.com/content/pdf/10.1007/s00371-025-03811-1.pdf
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
  caption: 'Sample renders tested with different material authoring strategies.'
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
