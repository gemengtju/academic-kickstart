---
title: "A Fast Convolutional Self-attention Based Speech Dereverberation Method for Robust Speech Recognition"
authors:
- Nan Li
- admin
- Longbiao Wang
- Jianwu Dang
date: "2019-12-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "ICONIP 2019"
publication_short: ""

abstract: Speech dereverberation based on deep learning has recently gained a remarkable success with the substantial improvement of speech recognition for the accuracy in the distant speech recognition task. However, environmental mismatches due to noise and reverberation may result in performance degradation when the features (e.g. MFCCs) are simply fed into a speech recognition system without feature enhancement. To address the problem, we propose a new speech dereverberation approach based on the deep convolution and self-attention mechanisms to enhance the MFCC-based feature in distant signals. The deep convolutional component used in this approach can efficiently exploit the frequency-temporal context patterns, and the multi-head self-attention mechanism can obtain the complete time-domain cues to enhance the temporal context. Meanwhile, the bottleneck features trained on a clean corpus are utilized as teacher signals, because they contain relevant cues to phoneme classification and the mapping is performed with the objective of suppressing noise and reverberation. Extensive experimental results on the REVERB challenge corpus demonstrate that our proposed approach outperforms all the competitors, reducing about 17% relative word error rate (WER) compared with the deep neural network (DNN) baseline method.

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: true

links:
url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-36718-3_25'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
