+++
title = "Receiver Clock Jump and Cycle Slip Correction Algorithm for Single-Frequency GNSS"
date = 2019-02-19T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. A. Momoh", "S. Bhattarai", "M. Ziebart"]

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
publication = "GPS Solutions"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We introduce a simple single-band receiver clock jump and cycle slip (CJCS) detection and correction algorithm suitable for a standalone single-frequency Global Navigation Satellite System (GNSS) receiver. The real-time algorithm involves using an adaptive time differencing technique for the generation of adaptive differenced sequences of single-frequency code and phase observations. The sequences are used for determining thresholds and for the detection and determination of a receiver clock jump and cycle slips. The cycle slip values are fixed by rounding-up float values obtained via weighted least squares adjustment, following the elimination of the receiver’s high-order clock drift at every epoch. The performance of this new technique was investigated with simulated cycle slip values and with different types of receiver clock jumps at millisecond and microsecond levels. It achieved 100% detection and correction of all types of receiver clock jumps; between 97 to 100% cycle slip detection; and between 96.9 to 100% cycle slip correction including cycle slips of ±1 cycle, for different rates of observations acquired by different fixed and mobile GNSS receivers. The algorithm thus facilitates precise timing and positioning on standalone low-cost single-frequency GNSS devices."
abstract_short = "We present a simple single-band receiver clock jump and cycle slip (CJCS) detection and correction algorithm suitable for a standalone single-frequency Global Navigation Satellite System (GNSS) receiver."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://rdcu.be/bnCsc"
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

# Digital Object Identifier (DOI)
doi = "10.1007/s10291-019-0832-4"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
