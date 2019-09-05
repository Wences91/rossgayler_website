+++
title = "scorecal - Empirical score calibration under the microscope"
date = 2019-08-30

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ross W Gayler"]

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
publication = "Presentation given at Credit Scoring and Credit Control Conference XVI, Edinburgh, Scotland, 2019-08-30"
publication_short = "CSCC 2019"

# Abstract and optional shortened version.
abstract = "Score calibration is the process of empirically determining the relationship between a score and an outcome on some population of interest, and scaling is the process of expressing that relationship in agreed units. Calibration is often treated as a simple matter and attacked with simple tools – typically, either assuming the relationship between score and log-odds is linear and fitting a logistic regression with the score as the only covariate, or dividing the score range into bands and plotting the empirical log-odds as a function of score band.\n\nBoth approaches ignore some information in the data. The assumption of a linear score to log-odds relationship is too restrictive and score banding ignores the continuity of the scores. While a linear score to log-odds relationship is often an adequate approximation, the reality can be much more interesting, with noticeable deviations from the linear trend. These deviations include large-scale non-linearity, small-scale non-monotonicity, discrete discontinuities, and complete breakdown of the linear trend at extreme scores.\n\nDetecting these effects requires a more sophisticated approach to empirically determining the score to outcome relationship. Taking a more sophisticated approach can be surprisingly tricky: the typically strong linear trend can obscure smaller deviations from linearity; detecting subtle trends requires exploiting the continuity of the scores, which can obscure discrete deviations; trends at extreme scores (out in the data-sparse tails of the distribution of scores) can be obscured by trends at less extreme scores (where there is more data); score distributions with some specific values that are relatively common can disrupt methods relying on continuity; and any modelling technique can introduce its own biases.\n\nOver the years I have developed a personal approach to these issues in score calibration and implemented them as an open source, publicly accessible R package for score calibration. I discuss these technical issues in empirical score calibration and show how they are addressed in the scorecal package."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
projects = ["score-calibration.md"]

tags = ["credit-scoring", "calibration"]

# Links (optional).
url_slides = "http://doi.org/10.5281/zenodo.3381658"
url_code = "https://doi.org/10.5281/zenodo.3381641"
# url_project = "https://github.com/rgayler/scorecal" # over-ridden by the "projects" entry
# url_pdf = "#"
# url_preprint = "#"
# url_dataset = "#"
# url_video = ""
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "GitHub repo", url = "https://github.com/rgayler/scorecal"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "cscc2019.png"
caption = ""

# More detail can easily be written below using *Markdown* and $\rm \LaTeX$ math code.
+++

Presentation DOI: [10.5281/zenodo.3381658](http://doi.org/10.5281/zenodo.3381658)  
  R notebook DOI: [10.5281/zenodo.3381641](http://doi.org/10.5281/zenodo.3381641)

