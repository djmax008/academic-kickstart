+++
title = "Distributed Control of Inverter-Interfaced Microgrids With Bounded Transient Line Currents"
date = 2012-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jiajun Duan", "Cheng Wang", Hao Xu", "Wenxin Liu","Jian-Chun Peng", "Hui Jiang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE Transactions on Industrial Informatics"
publication_short = "In *TII*"

# Abstract and optional shortened version.
abstract = "Distributed generators (DGs) in a microgrid are tightly coupled through power lines, whose dynamics should not be ignored. If not properly handled, large transient line currents may trigger false protection even under normal operating conditions. Droop-based control adjustments also unnecessarily increase frequency and voltage oscillations. Targeting at these problems, this paper presents a distributed control solution for inverter-interfaced microgrids. The objective of primary control is to realize the desired regulations of bus voltages and frequency as well as suppression of transient line currents. The objective of secondary control is to maintain fair load sharing. At secondary control level, a consensus algorithm is introduced to calculate the references for phase angles of bus voltages based on fair load sharing and dc power flow. At primary control level, a feedback linearization based control algorithm with dynamic control bounds is designed for voltage regulation and transient line current suppression. In addition to a common reference frame, the subsystem controllers only require measurements of local and neighboring subsystems. The effectiveness of the proposed control solution is demonstrated through simulations based on both simplified and detailed models."
abstract_short = "This paper presents a distributed control solution for inverter-interfaced microgrids. "

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["Power Electronics and Microgrids"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Control Theory","Microgrid","Power Electronics"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/8263162"
url_preprint = "https://caryduan.netlify.com/publication/2018TII/08263162.pdf"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1109/TII.2018.2791988"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
