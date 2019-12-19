+++
# Date this page was created.
date = 2016-04-27T00:00:00

weight = 10  # Order that this section will appear in.


# Project title.
title = "Satellite Clock Behaviour Modelling"

# Project summary to display on homepage.
summary = "Investigating and modelling the behaviour of GNSS satellite clocks on-orbit"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "gps_iir.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["phd"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "gps_iir.png"
caption = "GPS spacecraft broadcasting its signal towards Earth."

+++

In an operational sense, satellite clock time offset prediction (SCTOP) 
is a fundamental requirement in global navigation satellite systems (GNSS) 
technology. SCTOP uncertainty is a significant component of the 
uncertainty budget of the basic GNSS pseudorange measurements 
used in standard (i.e not 
high-precision), single-receiver applications. In real-time, this prediction 
uncertainty contributes directly to GNSS-based positioning, navigation and 
timing (PNT) uncertainty. In short, GNSS performance in intrinsically linked
to satellite clock predictability. Now, satellite clock predictability is 
affected by two factors: (i) the clock itself (i.e. the oscillator, the 
frequency standard etc.) and (ii) the prediction algorithm. This research
focuses on aspects of the latter.