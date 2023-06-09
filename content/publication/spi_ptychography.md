+++
title = "Single-Pixel Ptychography"
date = "2021-04-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[Meng Li](https://bianlab.github.io/members.html)", "[Liheng Bian](https://bianlab.github.io/)<sup>✉</sup>", "[Guoan Zheng](https://smartimaging.uconn.edu/)", "[Andrew Maiden](https://www.sheffield.ac.uk/eee/people/academic-staff/andrew-maiden)", "[__Yang Liu__](https://yangliu.mit.edu/)", "[Yiming Li](https://bianlab.github.io/members.html)", "[Jinli Suo](https://sites.google.com/site/suojinli)", "[Qionghai Dai](http://media.au.tsinghua.edu.cn)", "Jun Zhang"]

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
publication = "*Optics Letters*, **46** (7), 1624--1627"
publication_short = "*Optics Letters*, **46** (7), 1624--1627"

# Abstract and optional shortened version.
abstract = "Ptychography is a predominant non-interferometric technique to image large complex fields but with quite a narrow working spectrum, because diffraction measurements require dense array detection with an ultra-high dynamic range. Here we report a single-pixel ptychography technique that realizes non-interferometric and non-scanning complex-field imaging in a wide waveband, where 2D dense detector arrays are not available. A single-pixel detector is placed in the far field to record the DC-only component of the diffracted wavefront scattered from the target field, which is illuminated by a sequence of binary modulation patterns. This decreases the measurements’ dynamic range by several orders of magnitude. We employ an efficient single-pixel phase-retrieval algorithm to jointly recover the field’s 2D amplitude and phase maps from the 1D intensity-only measurement sequence. No a priori object information is needed in the recovery process. We validate the technique’s quantitative phase imaging nature using both calibrated phase objects and biological samples and demonstrate its wide working spectrum with both 488-nm visible light and 980-nm near-infrared light."

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
links = [{name = "project", url = "publication/spi_ptychography"},
         {name = "pdf", url = "https://opg.optica.org/ol/viewmedia.cfm?uri=ol-46-7-1624&seq=0"},
         {name = "code", url = "https://github.com/bianlab/single-pixel-ptychography"},
       # {name = "video", url = "publication/spi_ptychography/#video"},
       # {name = "highlight", url = "publication/spi_ptychography/#highlight"},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
      {name = "supp", url = "https://doi.org/10.6084/m9.figshare.14102123.v2"},
         {name = "arXiv", url = "https://arxiv.org/abs/2003.14237"},
         {name = "doi", url = "https://doi.org/10.1364/OL.417039"},
         {name = "bibtex", url = "publication/spi_ptychography/#bibtex"}
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
   author    = {Li, Meng and Bian, Liheng and Zheng, Guoan and Maiden, Andrew and Liu, Yang and Li, Yiming and Suo, Jinli and Dai, Qionghai and Zhang, Jun},
   title     = {Single-pixel ptychography},
   journal   = {Optics Letters},
   doi       = {10.1364/OL.417039},
   year      = {2021},
   month     = {4},
   volume    = {46},
   number    = {7},
   pages     = {1624--1627},
   url       = {https://doi.org/10.1364/OL.417039},
   publisher = {Optica Publishing Group},
   type      = {Journal Article}
}
```

