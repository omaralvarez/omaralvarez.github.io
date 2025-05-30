---
title: "Should I render or should AI Generate? Crafting Synthetic Semantic Segmentation Datasets with Controlled Generation"
authors:
- admin
- Manuel Silva
- Manuel Lijó-Sanchez
- Emilio J. Padrón
- Jose A. Iglesias-Guitian
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-03-21T00:00:00Z"
doi: "10.1109/MCG.2025.3553494"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEE Computer Graphics and Applications*"
publication_short: "*IEEE Comput Graph Appl*"

abstract: This work explores the integration of generative AI models for automatically generating synthetic image-labeled data. Our approach leverages controllable Diffusion Models to generate synthetic variations of semantically labeled images. Synthetic datasets for semantic segmentation struggle to represent real-world subtleties, such as different weather conditions or fine details, typically relying on costly simulations and rendering. However, Diffusion Models can generate diverse images using input text prompts and guidance images, like semantic masks. Our work introduces and tests a novel methodology for generating labeled synthetic images, with an initial focus on semantic segmentation, a demanding computer vision task. We showcase our approach in two distinct image segmentation domains, outperforming traditional computer graphics simulations in efficiently creating diverse datasets and training downstream models. We leverage generative models for crafting synthetically labeled images, posing the question "Should I render or should AI generate?". Our results endorse a paradigm shift towards controlled generation models.

# Summary. An optional shortened abstract.
summary: This work explores the integration of generative AI models for automatically generating synthetic image-labeled data. Our approach leverages controllable Diffusion Models to generate synthetic variations of semantically labeled images. Synthetic datasets for semantic segmentation struggle to represent real-world subtleties, such as different weather conditions or fine details, typically relying on costly simulations and rendering. However, Diffusion Models can generate diverse images using input text prompts and guidance images, like semantic masks. Our work introduces and tests a novel methodology for generating labeled synthetic images, with an initial focus on semantic segmentation, a demanding computer vision task.

tags:
- Semantic Segmentation
- Rendering
- Synthetic Data Generation
- Diffusion Models
- 3D
- Autonomous Driving
- Neural Networks
- Deep Learning
featured: false

# links:
# - name: ""
# url: "https://link.springer.com/article/10.1007/s00371-023-02972-1"
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10937140
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
  caption: 'Overview of our approach to create new synthetic image-labeled datasets using controlled generation.'
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
