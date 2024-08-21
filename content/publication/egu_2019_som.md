+++
title = "A data driven approach for the temporal classification of heavy rainfall using Self-Organizing Maps"
date = 2019-04-10T17:19:28+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K Vantas", "E Sidiropoulos", "C Evangelides"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*European Geosciences Union General Assembly*, 2019"
publication_short = "*EGU2019*"

# Abstract and optional shortened version.
abstract = "The identification of temporal rainfall patterns is important both in hydrological studies and in water resources management. Computational methods employed for such identification are briefly reviewed with emphasis on design hyetographs. In the sequel, the computational processes of this paper are described and are summarized here as follows: Raw Pluviograph data were acquired from the Greek National Bank of Hydrological and Meteorological Information for all available stations. A Poisson process hypothesis was used for the division of the raw time series to independent rainstorm events, assuming that their inter-arrival time is distributed exponentially per station and month. Unitless Cumulative Hyetographs (UCHs) were compiled and the null hypothesis of random structures in them was tested. The applicability of Principal Components Analysis and large Self-Organizing Maps (SOM) were examined as ways to represent these data. Subsequently, a stepwise procedure that utilized SOM as a clustering technique was applied. In each step a different map was used in order to create a low dimensional view of the data and consequently a limited number of rainfall temporal distribution patterns. Finally, these temporal distribution patterns were presented in a probabilistic way. In conclusion: a) A monthly temporal pattern for the extraction of independent rainstorm events was found for Greece, b) the hypothesis that the UCHs contains random data was rejected, c) as a result of SOM analysis, a limited number of temporal rainfall patterns emerged, in terms of seasonality and different characteristics and d) the classification of the rainstorm events was made in an unsupervised manner."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["unsupervised learning", "SOM", "hyetographs", "water-resources", "design-storms"]

# Links (optional).
url_pdf = "pdf/EGU2019-10680.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://www.essoar.org/doi/abs/10.1002/essoar.10500953.1"
url_source = "https://meetingorganizer.copernicus.org/EGU2019/EGU2019-10680.pdf"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "EGU 2019", url = "https://meetingorganizer.copernicus.org/EGU2019/posters/31247"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++