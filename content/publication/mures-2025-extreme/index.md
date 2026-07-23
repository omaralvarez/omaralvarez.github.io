---
title: Extreme compression of URANS flow data
authors:
- admin
- Miguel Cid Montoya
- Sumit Verma
- Ashustosh Mishra
date: '2025-06-19'
publishDate: '2025-06-19T10:13:39.568534Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 9th European-African Conference on Wind Engineering*'
publication_short: 'In *EACWE*'
abstract: The rise of exascale supercomputing has motivated an increase in high-fidelity CFD simulations, yielding massive datasets that can pose a problem for conventional data management and analysis pipelines. The detail in these simulations, often involving complex, non-linear turbulent flows, is essential for fueling innovations in fields like wind or aerospace engineering. The amount of data these simulations produce can overwhelm storage systems and negatively affect post-processing workflows, including iterative procedures such as design space exploration, optimization, and uncertainty quantification. This work proposes a novel sampling method harnessing the Signed Distance Function (SDF) concept and implicit compression based on neural networks for URANS CFD simulation data. Designed to alleviate the abovementioned problems, our approach achieves compression ratios of approximately 17000:1, reducing simulation data size from roughly 600 GB to 36 MB while maintaining low reproduction errors (in most cases below 0.5%). Given that image sampling is a fundamental step for any image-based flow field prediction model, the proposed SDF-based sampling method can significantly improve the accuracy and efficiency of such models, helping any application that relies on precise flow field predictions.
# doi: '10.1145/3281464.3281469'
# url_pdf: https://ruc.udc.es/dspace/bitstream/handle/2183/32255/Padron_Emilio_2018_In-transit_analysis_Apache_flink.pdf
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
image:
  caption: 'Diagram of the proposed framework.'
  focal_point: ""
  preview_only: false

---
