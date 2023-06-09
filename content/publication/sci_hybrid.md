+++
title = "Ten-Mega-Pixel Snapshot Compressive Imaging with a Hybrid Coded Aperture"
date = "2021-11-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[Zhihong Zhang](https://github.com/zhihongz)<sup>†</sup>", "[Chao Deng](https://scholar.google.com/citations?user=GkAO16kAAAAJ)<sup>†</sup>", "[__Yang Liu__](https://yangliu.mit.edu/)", "[Xin Yuan](https://scholar.google.com/citations?user=cS9CbWkAAAAJ)", "[Jinli Suo](https://sites.google.com/site/suojinli)<sup>✉</sup>", "[Qionghai Dai](http://media.au.tsinghua.edu.cn)"]

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
publication = "*Photonics Research*, **9** (11),  2277--2287"
publication_short = "*Photonics Research*, **9** (11),  2277--2287"

# Abstract and optional shortened version.
abstract = "High-resolution images are widely used in our everyday life; however, high-speed video capture is more challenging due to the low frame rate of cameras working at the high-resolution mode. The main bottleneck lies in the low throughput of existing imaging systems. Toward this end, snapshot compressive imaging (SCI) was proposed as a promising solution to improve the throughput of imaging systems by compressive sampling and computational reconstruction. During acquisition, multiple high-speed images are encoded and collapsed to a single measurement. Then, algorithms are employed to retrieve the video frames from the coded snapshot. Recently developed plug-and-play algorithms made the SCI reconstruction possible in large-scale problems. However, the lack of high-resolution encoding systems still precludes SCI’s wide application. Thus, in this paper, we build, to the best of our knowledge, a novel hybrid coded aperture snapshot compressive imaging (HCA-SCI) system by incorporating a dynamic liquid crystal on silicon and a high-resolution lithography mask. We further implement a PnP reconstruction algorithm with cascaded denoisers for high-quality reconstruction. Based on the proposed HCA-SCI system and algorithm, we obtain a 10-mega-pixel SCI system to capture high-speed scenes, leading to a high throughput of 4.6×10<sup>9</sup> voxels per second. Both simulation and real-data experiments verify the feasibility and performance of our proposed HCA-SCI scheme."

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
links = [{name = "project", url = "publication/sci_hybrid"},
         {name = "pdf", url = "https://arxiv.org/pdf/2106.15765"},
         {name = "code", url = "https://github.com/zhihongz/HCA-SCI"},
       # {name = "video", url = "publication/sci_hybrid/#video"},
       # {name = "highlight", url = "publication/sci_hybrid/#highlight"},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
      # {name = "supp", url = "https://doi.org/10.6084/m9.figshare.14102123.v2"},
         {name = "arXiv", url = "https://arxiv.org/abs/2106.15765"},
         {name = "doi", url = "https://doi.org/10.1364/PRJ.435256"},
         {name = "bibtex", url = "publication/sci_hybrid/#bibtex"}
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
@article{Li21SPY,
   author    = {Zhang, Zhihong and Deng, Chao and Liu, Yang and Yuan, Xin and Suo, Jinli and Dai, Qionghai},
   title     = {Ten-mega-pixel snapshot compressive imaging with a hybrid coded aperture},
   journal   = {Photonics Research},
   doi       = {10.1364/PRJ.435256},
   year      = {2021},
   month     = {11},
   volume    = {9},
   number    = {11},
   pages     = {2277--2287},
   url       = {https://doi.org/10.1364/PRJ.435256},
   publisher = {Optica Publishing Group},
   type      = {Journal Article}
}
```

