+++
title = "Learning Auctions with Robust Incentive Guarantees"
date = 2021-12-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["with Yinglun Xu", "and Jacob Abernethy"]

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
publication = "To appear in NeurIPS 2021"
publication_short = "to appear in NeurIPS 2021"

# Abstract and optional shortened version.
abstract = "We study data corruption attacks on stochastic multi arm bandit algorithms. Existing attack methodologies assume that the attacker can observe the multi arm bandit algorithm's realized behavior which is in contrast to the adversaries modeled in the robust multi arm bandit algorithms literature. To the best of our knowledge, we develop the first data corruption attack on stochastic multi arm bandit algorithms which works without observing the algorithm's realized behavior. Through this attack, we also discover a sufficient condition for a stochastic multi arm bandit algorithm to be susceptible to adversarial data corruptions. We show that any bandit algorithm that makes decisions just using the empirical mean reward, and the number of times that arm has been pulled in the past can suffer from linear regret under data corruption attacks. We further show that various popular stochastic multi arm bandit algorithms such UCB, &epsi-greedy and Thompson Sampling satisfy this sufficient condition and are thus prone to data corruption attacks. We further analyze the behavior of our attack for these algorithms and show that using only $o(T)$ corruptions, our attack can force these algorithms to select a potentially non-optimal target arm preferred by the attacker for all but $o(T)$ rounds."

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
#url_custom = [] 

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
