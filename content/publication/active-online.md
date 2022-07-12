+++
title = "ActiveHedge: Hedge meets Active Learning"
date = 2022-07-17T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["with Jacob Abernethy", "and Venkatesh Saligrama"]

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
publication = "International Conference on Machine Learning (ICML) 2022 <br> Also selected as oral talk at Complex Feedback in Online Learning Workshop, ICML 2022<br> Also presented at Adaptive experimental Design and Active Learning in the Real World Workshop, ICML 2022"
publication_short = "ICML 2022"

# Abstract and optional shortened version.
abstract = "We consider the classical problem of prediction with expert advice, but with an active learning twist. In this new setting, the algorithm may reorder the sequence of examples on which a prediction is made, it aims to minimize regret as usual, but it can observe only a small fraction of the true labels along the way. We consider a variant of the Hedge algorithm for this setting, and we show that under a very particular combinatorial constraint on the matrix of expert predictions we can obtain a very strong regret guarantee while querying very few labels. This constraint, which we refer to as $\\zeta $-compactness, can be viewed as a non-stochastic variant of the disagreement coefficient, another popular parameter used to reason about the sample complexity of active learning in the IID setting. We also give a polynomial time algorithm to calculate the $\\zeta $-compactness of a matrix up to an approximation factor of 3."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "pdf", url = "http://bhuveshkumar.com/pdf/learning_auctions.pdf"},{name = "NeurIPS", url = "http://papers.nips.cc/paper/9334-learning-auctions-with-robust-incentive-guarantees"}, {name = "Poster", url = "http://bhuveshkumar.com/pdf/LearnAuction_poster.pdf"}]
url_custom = [{Name = "Proceedings", url = "https://proceedings.mlr.press/v162/kumar22a.html"} ]


# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
