---
title: "Spectrograms Fusion with Minimum Difference Masks Estimation for Monaural Speech Dereverberation"
authors:
- Hao Shi
- Longbiao Wang
- admin
- Sheng Li
- Jianwu Dang
date: "2020-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICASSP 2020"
publication_short: ""

abstract: Spectrograms fusion is an effective method for incorporating complementary speech dereverberation systems. Previous linear spectrograms fusion by averaging multiple spectrograms shows outstanding performance. However, various systems with different features cannot apply this simple method. In this study, we design the minimum difference masks (MDMs) to classify the time-frequency (T-F) bins in spectrograms according to the nearest distances from labels. Then, we propose a two-stage nonlinear spectrograms fusion system for speech dereverberation. First, we conduct a multi-target learning-based speech dereverberation front-end model to get spectrograms simultaneously. Then, MDMs are estimated to take the best parts of different spectrograms. We are using spectrograms in the first stage and MDMs in the second stage to recombine T-F bins. The experiments on the REVERB challenge show that a strong feature complementarity between spectrograms and MDMs. Moreover, the proposed framework can consistently and significantly improve PESQ and SRMR, both real and simulated data, e.g., an average PESQ gain of 0.1 in all simulated data and an average SRMR gain of 1.22 in all real data.

# Summary. An optional shortened abstract.
summary: 

tags:
- Time Domain, 
- Speaker Extraction
- Weight-shared Speech Encoder
- Multi-scale
- Multi-task Learning
featured: true

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9054661'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
slides: example
---

