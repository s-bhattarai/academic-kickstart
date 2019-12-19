+++
title = "A shadow function model based on perspective projection and atmospheric effect for satellites in eclipse"
date = 2019-02-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Z. Li, M. Ziebart, S. Bhattarai, D. Harrison"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = PhD Thesis
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Advances in Space Research"
publication_short = "Adv. Space Res."

# Abstract and optional shortened version.
abstract = "Accurate Solar Radiation Pressure (SRP) modelling is critical for correctly describing the dynamics of satellites. A shadow function is a unitless quantity varying between 0 and 1 to scale the solar radiation flux at a satellite’s location during eclipses. Errors in modelling shadow function lead to inaccuracy in SRP that degrades the orbit quality. Shadow function modelling requires solutions to a geometrical problem (Earth’s oblateness) and a physical problem (atmospheric effects). This study presents a new shadow function model (PPM atm) which uses a perspective projection based approach to solve the geometrical problem rigorously and a linear function to describe the reduction of solar radiation flux due to atmospheric effects. GRACE (Gravity Recovery And Climate Experiment ) satellites carry accelerometers that record variations of non-conservative forces, which reveal the variations of shadow function during eclipses. In this study, the PPM atm is validated using accelerometer observations of the GRACE-A satellite. Test results show that the PPM atm is closer to the variations in accelerometer observations than the widely used SECM (Spherical Earth Conical Model). Taking the accelerometer observations derived shadow function as the “truth”, the relative error in PPM atm is - 0.79 % while the SECM 11.07%. The influence of the PPM atm is also shown in orbit prediction for Galileo satellites. Compared with the SECM, the PPM atm can reduce the radial orbit error RMS by 5.6 cm over a 7-day prediction. The impacts of the errors in shadow function modelling on the orbit remain to be systematic and should be mitigated in long-term orbit prediction."
abstract_short = " A shadow function scales the solar radiation flux at a satellite's location during eclipses. Here, we investigate the performance of a new shadow function model that considers the effects the Earth's oblateness and atmospheric refraction."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["radiation_force_modelling"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["radiation-force-modelling", "pod", "gnss"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S0273117718307968?via%3Dihub"
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
doi = "10.1016/j.asr.2018.10.027"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Time plots of time offsets (detrended) of four different types of GPS satellite clock from GPS Time."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
