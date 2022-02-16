---
title: "Pre-training Entity Relation Encoder with Intra-span and Inter-span Information"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yijun Wang
- admin
- Yuanbin Wu
- Junchi Yan
- Peng Gao
- Guotong Xie

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Empirical Methods in Natural Language Processing*
publication_short: In *EMNLP*

abstract: In this paper, we integrate span-related information into pre-trained encoder for entity relation extraction task. Instead of using general-purpose sentence encoder (e.g., existing universal pre-trained models), we introduce a span encoder and a span pair encoder to the pre-training network, which makes it easier to import intra-span and inter-span information into the pre-trained model. To learn the encoders, we devise three customized pre-training objectives from different perspectives, which target on tokens, spans, and span pairs. In particular, a span encoder is trained to recover a random shuffling of tokens in a span, and a span pair encoder is trained to predict positive pairs that are from the same sentences and negative pairs that are from different sentences using contrastive loss. Experimental results show that the proposed pre-training method outperforms distantly supervised pre-training, and achieves promising performance on two entity relation extraction benchmark datasets (ACE05, SciERC).

# Summary. An optional shortened abstract.
summary: 

tags: [joint entity relation extraction, pre-training objective, contrastive learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2020.emnlp-main.132.pdf'
url_code: 'https://github.com/Receiling/PSPE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://slideslive.com/38939251'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}} -->
<!-- Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->
<!-- {{% /callout %}} -->

<!-- {{% callout note %}} -->
<!-- Create your slides in Markdown - click the *Slides* button to check out the example. -->
<!-- {{% /callout %}} -->

[\[review\]](./review.txt)
[\[rebuttal\]](./rebuttal.txt)

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
