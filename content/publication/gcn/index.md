---
title: "Joint Type Inference on Entities and Relations via Graph Convolutional Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yeyun Gong
- Yuanbin Wu
- Ming Gong
- Daxing Jiang
- Man Lan 
- Shiliang Sun
- Nan Duan

date: "2019-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Association for Computational Linguistics*
publication_short: In *ACL*

abstract: We develop a new paradigm for the task of joint entity relation extraction. It first identifies entity spans, then performs a joint inference on entity types and relation types. To tackle the joint type inference task, we propose a novel graph convolutional network (GCN) running on an entity-relation bipartite graph. By introducing a binary relation classification task, we are able to utilize the structure of entity-relation bipartite graph in a more efficient and interpretable way. Experiments on ACE05 show that our model outperforms existing joint models in entity performance and is competitive with the state-of-the-art in relation performance.

# Summary. An optional shortened abstract.
summary: 

tags: [joint entity relation extraction, graph convoluational network]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/P19-1131.pdf'
url_code: 'https://github.com/changzhisun/AntNRE/tree/master/joint_entrel_gcn'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
