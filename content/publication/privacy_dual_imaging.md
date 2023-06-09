+++
title = "Imaging Privacy Threats from an Ambient Light Sensor"
date = "2022-12-31"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[__Yang Liu__](https://yangliu.mit.edu/)<sup>✉</sup>", "[Gregory W. Wornell](http://allegro.mit.edu/~gww/)", "[William T. Freeman](https://billf.mit.edu/)",  "[Frédo Durand](http://people.csail.mit.edu/fredo/)<sup>✉</sup>"]

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
publication = "[*submitted*]"
publication_short = "[*submitted*]"

# Abstract and optional shortened version.
abstract = "The prevalence of smart devices makes privacy a major issue, since embedded sensors can play an unfortunate role in leaking users’ information. Prior work has explored the potential privacy threats of such passive sensors in isolation or combined in certain scenarios. These attacks either require user permissions to access sensors or resolve limited information. We explore the degree to which the combined access to the ambient light sensor used for brightness adjustment as well as to the display may enable the capture of images of the environment without requiring access to a device's camera. In our scenario, the screen displays a known video sequence and the ambient light sensor captures the resulting intensity variation of the known sequence reflected off the scene in front of the screen. Because of the low-sensitivity and quantization of ambient light sensors, we formulate a version of ghost imaging or single-pixel imaging in the case of heavy quantization and solve it to reconstruct an image from the perspective of the screen using ℓ*<sub>p</sub>*-norm dequantizer and a deep denoiser as natural image prior. We demonstrate imaging privacy threats due to an ambient light sensor for touch-detection-, specularity-, occluder-based imaging information leakage, using either an Android tablet or an experimental setup. The resulting image resolution as well as the acquisition speed is limited, and some scenarios require constrained configurations (*e.g.*, mirror orientation for specular objects), but our demonstrations confirm the plausibility of the threats. Our goal is to raise awareness of potential security/privacy threats post by the combination of passive and active components, and promote the development of ways to mitigate them."

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
links = [{name = "project", url = "publication/privacy_dual_imaging"},
         # {name = "pdf", url = "https://arxiv.org/pdf/2101.04822"},
         {name = "code", url = "https://github.com/liuyang12/privacy-dual-imaging"},
       {name = "video", url = "publication/privacy_dual_imaging/#video"},
       {name = "highlight", url = "publication/privacy_dual_imaging/#highlight"},
       # {name = "slides", url = ""},
       # {name = "poster", url = ""},
      # {name = "supp", url = "files/desci_tpami_video_supp.zip"},
         # {name = "arXiv", url = "https://arxiv.org/abs/2101.04822"},
         # {name = "doi", url = "https://doi.org/10.1109/TPAMI.2021.3099035"},
         {name = "bibtex", url = "publication/privacy_dual_imaging/#bibtex"}
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

## Video
Initial Poster video at [ICCP 2021](https://iccp2021.iccp-conference.org/).   
<iframe width="720" height="405" src="https://www.youtube.com/embed/PoEFci3csLc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Highlight
Research [Spotlight](https://cap.csail.mit.edu/engage/spotlights/yang-liu) by [MIT CSAIL](https://www.csail.mit.edu/) in April 2022. Thanks [Matt](https://www.csail.mit.edu/person/matthew-busekroos) and [Nate](https://www.csail.mit.edu/person/nathan-caldwell) for neat production!   
<iframe width="720" height="405" src="https://www.youtube.com/embed/8-cyA-LJB4A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## bibtex
```markdown
@article{Liu22PDI,
   author    = {Liu, Yang and Wornell, Gregory W. and Freeman, William T. and Durand, Fr{\'e}do},
   title     = {Imaging Privacy Threats from an Ambient Light Sensor},
   year      = {2022},
   month     = {12},
   type      = {Journal Article}
}
```

