---
title: "2-Entity RANSAC for robust visual localization in changing environment"
authors:
- admin
- Yue Wang
- Bo Fu
- Xiaqing Ding
- Qimeng Tan
- Lei Chen
- Rong Xiong
date: "2019-11-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS*

abstract: Visual localization has attracted considerable attention due to its low-cost and stable sensor, which is desired in many applications, such as autonomous driving, inspection robots and unmanned aerial vehicles. However, current visual localization methods still struggle with environmental changes across weathers and seasons, as there is significant appearance variation between the map and the query image. The crucial challenge in this situation is that the percentage of outliers, i.e. incorrect feature matches, is high. In this paper, we derive minimal closed form solutions for 3D-2D localization with the aid of inertial measurements, using only 2 point matches or 1 point match and 1 line match. These solutions are further utilized in the proposed 2-entity RANSAC, which is more robust to outliers as both line and point features can be used simultaneously and the number of matches required for pose calculation is reduced. Furthermore, we introduce three feature sampling strategies with different advantages, enabling an automatic selection mechanism. With the mechanism, our 2-entity RANSAC can be adaptive to the environments with different distribution of feature types in different segments. Finally, we evaluate the method on both synthetic and real-world datasets, validating its performance and effectiveness in inter-session scenarios.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/8967671
url_code: 'https://github.com/slinkle/2-Entity-RANSAC'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

