---
title: "Pitch Synchronized Relative Phase with Peak Error Detection For Noise-robust Speaker Recognition"
authors:
- admin
- Longbiao Wang
- Seiichi Nakagawa
- Yuta Kawakami
- Jianwu Dang
- Xiangang Li
date: "2018-11-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: Speaker extraction aims to extract the target speech signal from a multi-talker environment given a target speaker's reference speech. We recently proposed a time-domain solution, SpEx, that avoids the phase estimation in frequency-domain approaches. Unfortunately, SpEx is not fully a time-domain solution since it performs time-domain speech encoding for speaker extraction, while taking frequency-domain speaker embedding as the reference. The size of the analysis window for time-domain and the size for frequency-domain input are also different. Such mismatch has an adverse effect on the system performance. To eliminate such mismatch, we propose a complete time-domain speaker extraction solution, that is called SpEx+. Specifically, we tie the weights of two identical speech encoder networks, one for the encoder-extractor-decoder pipeline, another as part of the speaker encoder. Experiments show that the SpEx+ achieves 0.8dB and 2.1dB SDR improvement over the state-of-the-art SpEx baseline, under different and same gender conditions on WSJ0-2mix-extr database respectively.

# Summary. An optional shortened abstract.
summary: Speaker extraction aims to extract the target speech signal from a multi-talker environment given a target speaker's reference speech. We recently proposed a time-domain solution, SpEx, that avoids the phase estimation in frequency-domain approaches.

tags:
- Time Domain, 
- Speaker Extraction
- Weight-shared Speech Encoder
- Multi-scale
- Multi-task Learning
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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

