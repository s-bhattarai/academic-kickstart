+++
title = "Fast solar radiation pressure modelling with ray tracing and multiple reflections"
date = 2018-05-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Z. Li, M. Ziebart, S. Bhattarai, D. Harrison, S. Grey"]

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
abstract = "Physics based SRP (Solar Radiation Pressure) models using ray tracing methods are powerful tools when modelling the forces on complex real world space vehicles. Currently high resolution (1 mm) ray tracing with secondary intersections is done on high performance computers at UCL (University College London). This study introduces the BVH (Bounding Volume Hierarchy) into the ray tracing approach for physics based SRP modelling and makes it possible to run high resolution analysis on personal computers. The ray tracer is both general and efficient enough to cope with the complex shape of satellites and multiple reflections (three or more, with no upper limit). In this study, the traditional ray tracing technique is introduced in the first place and then the BVH is integrated into the ray tracing. Four aspects of the ray tracer were tested for investigating the performance including runtime, accuracy, the effects of multiple reflections and the effects of pixel array resolution.Test results in runtime on GPS IIR and Galileo IOV (In Orbit Validation) satellites show that the BVH can make the force model computation 30-50 times faster. The ray tracer has an absolute accuracy of several nanonewtons by comparing the test results for spheres and planes with the analytical computations. The multiple reflection effects are investigated both in the intersection number and acceleration on GPS IIR, Galileo IOV and Sentinel-1 spacecraft. Considering the number of intersections, the 3rd reflection can capture 99.12%, 99.14%, and 91.34% of the total reflections for GPS IIR, Galileo IOV satellite bus and the Sentinel-1 spacecraft respectively. In terms of the multiple reflection effects on the acceleration, the secondary reflection effect for Galileo IOV satellite and Sentinel-1 can reach 0.2 nm/s2 and 0.4 nm/s2 respectively. The error percentage in the accelerations magnitude results show that the 3rd reflection should be considered in order to make it less than 0.035%. The pixel array resolution tests show that the dimensions of the components have to be considered when choosing the spacing of the pixel in order not to miss some components of the satellite in ray tracing. This paper presents the first systematic and quantitative study of the secondary and higher order intersection effects. It shows conclusively the effect is non-negligible for certain classes of misson."
abstract_short = "This study introduces the Bounding Volume Hierachy structure in an algorithm for computing solar radiation pressure for spacecraft based on a ray-tracing approach, demonstrating that this make the computations run 30-50 times faster. This speedup allows us to investigate accelerations arising radiation-surface interactions, where the radiation is reflected radiation from the spacecraft itself. We show that the effects of secondary and higher-order reflected radiation are non-negligible in certain classes on mission."

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
tags = ["radiation-force-modelling", "pod", "gnss","ray-tracing","srp"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S0273117718301595?via%3Dihub"
url_preprint = "http://discovery.ucl.ac.uk/id/eprint/10047585"
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
doi = "10.1016/j.asr.2018.02.019"

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
