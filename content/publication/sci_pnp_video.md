+++
title = "Plug-and-Play Algorithms for Video Snapshot Compressive Imaging"
date = "2022-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[Xin Yuan](https://scholar.google.com/citations?user=cS9CbWkAAAAJ)<sup>†</sup>", "[__Yang Liu__](https://yangliu.mit.edu/)<sup>†</sup>", "[Jinli Suo](https://sites.google.com/site/suojinli)", "[Frédo Durand](http://people.csail.mit.edu/fredo/)", "[Qionghai Dai](http://media.au.tsinghua.edu.cn)"]

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
publication = "*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, **44** (10), 7093--7111"
publication_short = "*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, **44** (10), 7093--7111"

# Abstract and optional shortened version.
abstract = "We consider the reconstruction problem of video snapshot compressive imaging (SCI), which captures high-speed videos using a low-speed 2D sensor (detector). The underlying principle of SCI is to modulate sequential high-speed frames with different masks and then these encoded frames are integrated into a snapshot on the sensor and thus the sensor can be of low-speed. On one hand, video SCI enjoys the advantages of low-bandwidth, low-power and low-cost. On the other hand, applying SCI to large-scale problems (HD or UHD videos) in our daily life is still challenging and one of the bottlenecks lies in the reconstruction algorithm. Existing algorithms are either too slow (iterative optimization algorithms) or not flexible to the encoding process (deep learning based end-to-end networks). In this paper, we develop fast and flexible algorithms for SCI based on the plug-and-play (PnP) framework. In addition to the PnP-ADMM method, we further propose the PnP-GAP (generalized alternating projection) algorithm with a lower computational workload. We first employ the image deep denoising priors to show that PnP can recover a UHD color video with 30 frames from a snapshot measurement. Since videos have strong temporal correlation, by employing the video deep denoising priors, we achieve a significant improvement in the results. Furthermore, we extend the proposed PnP algorithms to the color SCI system using mosaic sensors, where each pixel only captures the red, green or blue channels. A joint reconstruction and demosaicing paradigm is developed for flexible and high quality reconstruction of color video SCI systems. Extensive results on both simulation and real datasets verify the superiority of our proposed algorithm."

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
links = [{name = "project", url = "publication/sci_pnp_video"},
         {name = "pdf", url = "https://arxiv.org/pdf/2101.04822"},
         {name = "code", url = "https://github.com/liuyang12/PnP-SCI_python"},
       # {name = "video", url = ""},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
      # {name = "supp", url = "files/desci_tpami_video_supp.zip"},
         {name = "arXiv", url = "https://arxiv.org/abs/2101.04822"},
         {name = "doi", url = "https://doi.org/10.1109/TPAMI.2021.3099035"},
         {name = "bibtex", url = "publication/sci_pnp_video/#bibtex"}
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
@article{Yuan21PnPvideo,
   author    = {Yuan, Xin and Liu, Yang and Suo, Jinli and Durand, Fr{\'e}do and Dai, Qionghai},
   title     = {Plug-and-Play Algorithms for Video
Snapshot Compressive Imaging},
   journal   = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
   doi       = {10.1109/TPAMI.2021.3099035},
   year      = {2022},
   month     = {10},
   volume    = {44},
   number    = {10},
   pages     = {7093 -- 7111},
   url       = {https://doi.org/10.1109/TPAMI.2021.3099035},
   publisher = {IEEE},
   type      = {Journal Article}
}
```

