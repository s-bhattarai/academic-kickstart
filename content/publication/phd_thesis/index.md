+++
title = "Satellite clock time offset prediction in global navigation satellite systems"
date = 2015-04-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["S. Bhattarai"]

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
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "Ph.D. thesis, University College London"
publication_short = "Ph.D. thesis, UCL"

# Abstract and optional shortened version.
abstract = "In an operational sense, satellite clock time offset prediction (SCTOP) is a fundamental requirement in global navigation satellite systems (GNSS) technology. SCTOP uncertainty is a significant component of the uncertainty budget of the basic GNSS pseudorange measurements used in standard (i.e not high-precision), single-receiver applications. In real-time, this prediction uncertainty contributes directly to GNSS-based positioning, navigation and timing (PNT) uncertainty. In short, GNSS performance in intrinsically linked to satellite clock predictability. Now, satellite clock predictability is affected by two factors: (i) the clock itself (i.e. the oscillator, the frequency standard etc.) and (ii) the prediction algorithm. This research focuses on aspects of the latter. Using satellite clock data---spanning across several years, corresponding to multiple systems (GPS and GLONASS) and derived from real measurements---this thesis first presents the results of a detailed study into the characteristics of GNSS satellite clocks. This leads onto the development of strategies for modelling and estimating the time-offset of those clocks from system time better, with the final aim of predicting those offsets better. The satellite clock prediction scheme of the International GNSS Service (IGS) is analysed, and the results of this prediction scheme are used to evaluate the performance of new methods developed herein. The research presented in this thesis makes a contribution to knowledge in each of the areas of characterisation, modelling and prediction of GNSS satellite clocks. Regarding characterisation of GNSS satellite clocks, the space-borne clocks of GPS and GLONASS are studied. In terms of frequency stability (and thus predictability) it is generally the case that the GPS clocks out-perform GLONASS clocks at prediction lengths ranging from several minutes up to one day ahead. There are three features in the GPS clocks---linear frequency drift, periodic signals and complex underlying noise processes---that are not observable in the GLONASS clocks. The standard clock model does not capture these features. This study shows that better prediction accuracy can be obtained by an extension to the standard clock model. The results of the characterisation and modelling study are combined in a Kalman filter framework, set up to output satellite clock predictions at a range of prediction intervals. In this part of the study, only GPS satellite clocks are considered. In most, but not all cases, the developed prediction method outperforms the IGS prediction scheme, by between 10% to 30%. The magnitude of the improvement is mainly dependent upon clock type."
abstract_short = "This thesis present a series of four studies investigating the behaviour and performance of GNSS satellite clocks."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["phd"]

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
url_pdf = "http://discovery.ucl.ac.uk/1464288/"
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
doi = ""

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
