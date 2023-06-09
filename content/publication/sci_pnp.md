+++
title = "Plug-and-Play Algorithms for Large-Scale Snapshot Compressive Imaging"
date = "2020-06-13"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[Xin Yuan](https://scholar.google.com/citations?user=cS9CbWkAAAAJ)", "[__Yang Liu__](https://yangliu.mit.edu/)",  "[Jinli Suo](https://sites.google.com/site/suojinli)", "[Qionghai Dai](http://media.au.tsinghua.edu.cn)"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)* **[Oral]**, 1447-1457"
publication_short = "in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)* **[Oral]**, 1447-1457"

# Abstract and optional shortened version.
abstract = "Snapshot compressive imaging (SCI) aims to capture the high-dimensional (usually 3D) images using a 2D sensor (detector) in a single snapshot. Though enjoying the advantages of low-bandwidth, low-power and low-cost, applying SCI to large-scale problems (HD or UHD videos) in our daily life is still challenging. The bottleneck lies in the reconstruction algorithms; they are either too slow (iterative optimization algorithms) or not flexible to the encoding process (deep learning based end-to-end networks). In this paper, we develop fast and flexible algorithms for SCI based on the plug-and-play (PnP) framework. In addition to the widely used PnP-ADMM method, we further propose the PnP-GAP (generalized alternating projection) algorithm with a lower computational workload and prove the *global convergence* of PnP-GAP under the SCI hardware constraints. By employing deep denoising priors, we first time show that PnP can recover a UHD color video ($3840\\times 1644\\times 48$ with PNSR above 30dB) from a snapshot 2D measurement. Extensive results on both simulation and real datasets verify the superiority of our proposed algorithm."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
# url_pdf = "https://arxiv.org/pdf/2003.13654"
# url_preprint = "https://arxiv.org/abs/2003.13654"
# url_code = "https://github.com/liuyang12/PnP-SCI"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "project", url = "publication/sci_pnp"},
         {name = "pdf", url = "https://arxiv.org/pdf/2003.13654"},
         {name = "code", url = "https://github.com/liuyang12/PnP-SCI"},
       # {name = "video", url = ""},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
         {name = "supp", url = "https://openaccess.thecvf.com/content_CVPR_2020/supplemental/Yuan_Plug-and-Play_Algorithms_for_CVPR_2020_supplemental.zip"},
         {name = "arXiv", url = "https://arxiv.org/abs/2003.13654"},
         {name = "doi", url = "https://doi.org/10.1109/CVPR42600.2020.00152"},
         {name = "bibtex", url = "publication/sci_pnp/#bibtex"}
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
@inproceedings{Yuan20PnPSCI,
   author    = {Yuan, Xin and Liu, Yang and Suo, Jinli and Dai, Qionghai},
   title     = {Plug-and-Play Algorithms for Large-scale Snapshot Compressive Imaging},
   booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
   doi       = {10.1109/CVPR42600.2020.00152},
   year      = {2020},
   month     = {6},
   pages     = {1447 -- 1457},
   arxiv     = {2003.13654},
   url       = {https://doi.org/10.1109/CVPR42600.2020.00152},
   publisher = {IEEE/CVF},
   type      = {Conference Proceedings}
}
```


