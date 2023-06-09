+++
title = "Rank Minimization for Snapshot Compressive Imaging"
date = "2019-12-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[__Yang Liu__](https://yangliu.mit.edu/)<sup>†</sup>", "[Xin Yuan](https://scholar.google.com/citations?user=cS9CbWkAAAAJ)<sup>†</sup>", "[Jinli Suo](https://sites.google.com/site/suojinli)", "[David J. Brady](https://www.optics.arizona.edu/person/david-brady)", "[Qionghai Dai](http://media.au.tsinghua.edu.cn)<sup>✉</sup>"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, **41** (12), 2990-3006"
publication_short = "*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, **41** (12), 2990-3006"

# Abstract and optional shortened version.
abstract = "Snapshot compressive imaging (SCI) refers to compressive imaging systems where multiple frames are mapped into a single measurement, with video compressive imaging and hyperspectral compressive imaging as two representative applications. Though exciting results of high-speed videos and hyperspectral images have been demonstrated, the poor reconstruction quality precludes SCI from wide applications.This paper aims to boost the reconstruction quality of SCI via exploiting the high-dimensional structure in the desired signal. We build a joint model to integrate the nonlocal self-similarity of video/hyperspectral frames and the rank minimization approach with the SCI sensing process. Following this, an alternating minimization algorithm is developed to solve this non-convex problem. We further investigate the special structure of the sampling process in SCI to tackle the computational workload and memory issues in SCI reconstruction. Both simulation and real data (captured by four different SCI cameras) results demonstrate that our proposed algorithm leads to significant improvements compared with current state-of-the-art algorithms. We hope our results will encourage the researchers and engineers to pursue further in compressive imaging for real applications."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "project", url = "publication/sci_rank_minimization"},
         {name = "pdf", url = "https://arxiv.org/pdf/1807.07837"},
         {name = "code", url = "https://github.com/liuyang12/DeSCI"},
       # {name = "video", url = ""},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
         {name = "supp", url = "files/desci_tpami_video_supp.zip"},
         {name = "arXiv", url = "https://arxiv.org/abs/1807.07837"},
         {name = "doi", url = "https://doi.org/10.1109/TPAMI.2018.2873587"},
         {name = "bibtex", url = "publication/sci_rank_minimization/#bibtex"}
         ]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++

## bibtex
```markdown
@article{Liu19DeSCI,
   author    = {Liu, Yang and Yuan, Xin and Suo, Jinli and Brady, David J. and Dai, Qionghai},
   title     = {Rank Minimization for Snapshot Compressive Imaging},
   journal   = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
   doi       = {10.1109/TPAMI.2018.2873587},
   year      = {2019},
   month     = {12},
   volume    = {41},
   number    = {12},
   pages     = {2990 -- 3006},
   url       = {https://doi.org/10.1109/TPAMI.2018.2873587},
   publisher = {IEEE},
   type      = {Journal Article}
}
```

