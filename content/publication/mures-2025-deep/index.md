---
title: Deep learning emulation of forced vibration flows for accurate prediction of shape-dependent self-excited forces
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
abstract: Accurate prediction of aeroelastic behavior is crucial in the wind-resistant design of bridges. Hence, developing robust workflows is pivotal for determining nonlinear fluid-structure interaction parameters, particularly flutter derivatives, across varying deck shapes and reduced velocities within the chosen design domain. Traditional interpolation methods usually work in the frequency and design domains. While convenient, this approach omits useful information in the self-excited forces time series or the forced vibration flows. This investigation proposes an emulation in the space-time domain by training a deep learning (DL) model with flow fields to build a prediction workflow with enhanced accuracy. A custom auto encoder (AE) architecture is trained on flow field data, incorporating deck shape and physical constraints as inputs. To enhance performance, SDF-biased sampling prioritizes critical flow features near the bridge deck surface when obtaining flow field images. The model leverages attention mechanisms and recurrent layers to capture the complex temporal and spatial dynamics of flow fields. Skip connections further improve the resolution and accuracy of the predicted flow fields. Preliminary results show that this method can surpass the accuracy of existing image-based flow field prediction techniques, and consequently improve flutter derivative emulation.
# doi: '10.1145/3281464.3281469'
url_pdf: https://www.ntnu.edu/documents/1340831965/0/EACWE+2025+Proceedings.pdf/4f9300b0-3170-693f-bbc4-b4f3fd28955f?t=1750155312608
tags: 
- CFD
- Numerical Simulation
- Neural Networks
- Prediction
- Image
- U-Net
- CNN
- Deep Learning
image:
  caption: 'Diagram of the proposed framework.'
  focal_point: ""
  preview_only: false

---
