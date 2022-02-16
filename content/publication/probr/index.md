---
title: "Probabilistic Graph Reasoning for Natural Proof Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xinbo Zhang
- Jiangjie Chen
- Chun Gan
- Yuanbin Wu
- Jiaze Chen
- Hao Zhou 
- Lei Li

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Findings of Association for Computational Linguistics*
publication_short: In *Findings of ACL*

abstract: In this paper, we investigate the problem of reasoning over natural language statements.  Prior neural based approaches do not explicitly consider the inter-dependency among answers and their proofs. In this paper, we propose PROBR, a novel approach for joint answer prediction and proof generation. PROBR defines a joint probabilistic distribution over all possible proof graphs and answers via an induced graphical model. We then optimize the model using variational approximation on top of neural textual representation. Experiments on multiple datasets under diverse settings (fully supervised, few-shot and zero-shot evaluation) verify the effectiveness of PROBR, e.g., achieving 10%-30% improvement on QA accuracy in few/zero-shot evaluation. Our codes and models can be found at https://github.com/changzhisun/PRobr/.

# Summary. An optional shortened abstract.
summary: 

tags: [reasoning over natural languge, probabilistic reasoning, proof generation, variational approximation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2021.findings-acl.277.pdf'
url_code: 'https://github.com/changzhisun/PRobr'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'publication/probr/slides.pdf'
url_source: ''
url_video: ''

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
[\[blog\]](https://mp.weixin.qq.com/s/JQoiQeLEnOhj-GBWmGaCvQ)

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
