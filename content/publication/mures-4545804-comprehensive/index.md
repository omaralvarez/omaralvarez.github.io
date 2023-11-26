---
title: A Comprehensive Handball Dynamics Dataset for Game Situation Classification
authors:
- Omar A. Mures
- Javier Taibo
- Emilio J. Padrón
- Jose A. Iglesias-Guitian
date: 2023-01-01
publishDate: '2023-11-26T10:00:39.613677Z'
publication_types:
- article-journal
publication: '*Data in Brief*'
publication_short: '*Data Br.*'
abstract: 'This article presents a comprehensive dataset of labeled game situations obtained from multiple professional handball matches, which corresponds to the research paper entitled \“PlayNet: Real-time Handball Play Classification with Kalman Embeddings and Neural Networks\”. The dataset encompasses approximately 11 hours of footage from five handball games played in two different arenas, resulting in around 1 million data frames. Each frame has been meticulously labeled using seven distinct game situation classes (left and right attacks, left and right transitions, left and right penalties, and timeouts). Notably, the dataset does not contain video frames, but provides a synthetic normalized representation of each frame. This representation includes information about player, referee, and ball positions, as well as player and referee velocities, for every labeled game situation. We obtained said details automatically by using an object detector to infer the positions of players, referees, and the ball in each frame. After tracking the detected agent positions across frames, the extracted coordinates underwent normalization through a \"bird\'s eye\" perspective transform, ensuring that the data remained unaffected by variations in camera configurations across different arenas. Finally, a Kalman filter was applied to improve the robustness of player positions and derive their velocities. The labeling process was performed by domain experts employing a custom system designed to annotate game situations, considering the play type and its contextual setting. In conclusion, researchers can utilize this dataset for several purposes: game analysis, automated broadcasting, or game summarization. Furthermore, this dataset can contribute to a broader understanding of the relationship between player dynamics and game situations, shedding light on the level of granularity required for accurately classifying them.'
doi: 'https://doi.org/10.1016/j.dib.2023.109848'
url_preprint: 'https://www.sciencedirect.com/science/article/pii/S2352340923009101/pdfft?md5=d4ae3ab5ae2a12fc2e36feb70504ca3f&pid=1-s2.0-S2352340923009101-main.pdf'
tags: 
- Sports
- Kalman Filter
- Players
- Ball
- Position
- Velocity
- Normalized
- Game Situation
- Dataset
image:
  caption: 'Dataset game situation examples.'
  focal_point: ""
  preview_only: false

---
