+++
title = "MuGNet: Multi-Resolution Graph Neural Network for Segmenting Large-Scale Pointclouds"

# Date first published.
date = "2020-09-18"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Liuyue Xie", "Tomotake Furuhata", "Kenji Shimada"]

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
publication = "In *Conference on Robotics Learning 2020*. "
publication_short = "In *CoRL 2020*"

# Abstract and optional shortened version.
abstract = "In this paper, we propose a multi-resolution deep-learning architecture to semantically segment dense large-scale pointclouds. Dense pointcloud data require a computationally expensive feature encoding process before semantic segmentation. Previous work has used different approaches to drastically downsample from the original pointcloud so common computing hardware can be utilized. While these approaches can relieve the computation burden to some extent, they are still limited in their processing capability for multiple scans. We present MuGNet, a memory-efficient, end-to-end graph neural network framework to perform semantic segmentation on large-scale pointclouds. We reduce the computation demand by utilizing a graph neural network on the preformed pointcloud graphs and retain the precision of the segmentation with a bidirectional network that fuses feature embedding at different resolutions. Our framework has been validated on benchmark datasets including Stanford Large-Scale 3D Indoor Spaces Dataset(S3DIS) and Virtual KITTI Dataset. We demonstrate that our framework can process up to 45 room scans at once on a single 11 GB GPU while still surpassing other graph-based solutions for segmentation on S3DIS with an 88.5% (+3%) overall accuracy and 69.8% (+7.7%) mIOU accuracy."
abstract_short = "In this paper, we propose a multi-resolution deep-learning architecture to semantically segment dense large-scale pointclouds."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2009.08924.pdf"
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
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "mugnet.png"
caption = "MuGNet Network Overview"

+++

Further details on your publication can be written here using *Markdown* for formatting. This text will be displayed on the Publication Detail page.
