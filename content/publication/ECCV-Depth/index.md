+++
title = "Disentangling Object Motion and Occlusion for Unsupervised Multi-frame Monocular Depth"

# Date first published.
date = "2022-03-29"

# Authors. Comma separated list, e.g. `["Ziyue Feng", "Longlong Jing", "Peng Yin", "Yingli Tian", "Bing Li"]`.
authors = ["Ziyue Feng", "Liang Yang", "Longlong Jing", "Haiyan Wang", "Yingli Tian", "Bing Li"]

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
publication = "European Conference on Computer Vision"
publication_short = "In ECCV 2022"

# Abstract and optional shortened version.
abstract = "**[ECCV 2022]** Solve the dynamic object problem in multi-frame monocular depth prediction."
abstract_short = "Conventional self-supervised monocular depth prediction methods are based on a static environment assumption, which leads to accuracy degradation in dynamic scenes due to the mismatch and occlusion problems introduced by object motions. Existing dynamic-object-focused methods only partially solved the mismatch problem at the training loss level. In this paper, we accordingly propose a novel multi-frame monocular depth prediction method to solve these problems at both the prediction and supervision loss levels. Our method, called DynamicDepth, is a new framework trained via a self-supervised cycle consistent learning scheme. A Dynamic Object Motion Disentanglement (DOMD) module is proposed to disentangle object motions to solve the mismatch problem. Moreover, novel occlusion-aware Cost Volume and Re-projection Loss are designed to alleviate the occlusion effects of object motions. Extensive analyses and experiments on the Cityscapes and KITTI datasets show that our method significantly outperforms the state-of-the-art monocular depth prediction methods, especially in the areas of dynamic objects. Our code will be made publicly available."

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
url_pdf = "https://arxiv.org/pdf/2203.15174.pdf"
url_preprint = "https://arxiv.org/abs/2203.15174"
url_code = "https://github.com/AutoAILab/DynamicDepth"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/Gg6pLvFDdc4"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

tags = ["deep learning", "depth prediction"]

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption 😄"

+++

Further details on your publication can be written here using *Markdown* for formatting. This text will be displayed on the Publication Detail page.
