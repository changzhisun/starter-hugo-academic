---
title: "BiGCNN:Bidirectional Gated Convolutional Neural Network for Chinese Named Entity Recognition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tianyang Zhao
- Haoyan Liu
- Qianhui Wu
- admin
- Dongdong Zhan 
- Zhoujun Li.

date: "2020-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Database Systems for Advanced Applications*
publication_short: In *DASFAA*

abstract: Recent advances on Chinese named entity recognition(NER) are mostly based on the recurrent neural network (RNN). Since RNNs are limited in parallel processing, some works apply the convolutional neural network (CNN) to perform NER. However, existing CNN-based models fail to explicitly distinguish the preceding and subsequent contexts, so they are difficult to handle cases that are sensitive to the location of the contexts. Moreover, they pay equal attention to the context within a convolution kernel, while not all the information is useful for semantic understanding. In this paper, we propose a novel CNN-based model, Bidirectional Gated Convolutional Neural Network (BiGCNN), to differentiate the entity-related information between preceding and subsequent contexts and filter out the convolution information adaptively. By incorporating automatic segmentation and glyph information, BiGCNN outperforms state-of-the-art models on four Chinese NER datasets. Additionally, benefiting from the parallelism processing, the proposed method enjoys higher training and testing efficiency, e.g., 12.04 times faster than RNN-based models, while with better performance.


# Summary. An optional shortened abstract.
summary: 

tags: [Chinese named entity recognition, bidirectional gated convolutional neural network, glyph information]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/bigcnn/bigcnn.pdf'
url_code: ''
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


<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
