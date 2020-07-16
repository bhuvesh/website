+++
title = "Learning Auctions with Robust Incentive Guarantees"
date = 2019-09-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["with Jacob Abernethy", "Rachel Cummings", "Jamie Morgenstern", "and Samuel Taggart"]

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
publication = "NeurIPS, 2019 <br> Preliminary version accepted at Learning in Presence of Strategic Behavior, EC 2019"
publication_short = "NeurIPS 2019"

# Abstract and optional shortened version.
abstract = "We study the problem of learning Bayesian-optimal revenue-maximizing auctions. The classical approach to maximizing revenue requires a known prior distribution on the demand of the bidders, although recent work has shown how to replace the knowledge of a prior distribution with a polynomial sample. However, in an online setting, when buyers can participate in multiple rounds, standard learning techniques are susceptible to strategic overfitting: bidders can improve their long-term wellbeing by manipulating the trajectory of the learning algorithm in earlier rounds. For example, they may be able to strategically adjust their behavior in earlier rounds to achieve lower, more favorable future prices. Such non-truthful behavior can hinder learning and harm revenue.  In this paper, we combine tools from differential privacy, mechanism design, and sample complexity to give a repeated auction that (1) learns bidder demand from past data, (2) is approximately revenue-optimal, and (3) strategically robust, as it incentivizes bidders to behave truthfully."

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
url_custom = [{name = "pdf", url = "http://bhuveshkumar.com/pdf/learning_auctions.pdf"},{name = "NeurIPS", url = "http://papers.nips.cc/paper/9334-learning-auctions-with-robust-incentive-guarantees"}, {name = "Poster", url = "http://bhuveshkumar.com/pdf/LearnAuction_poster.pdf"}]

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
