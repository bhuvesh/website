+++
title = "Accelerated Parallelizable Projection-Free Algorithm for the Nuclear-Norm Ball Constraint"
date = 2020-03-14T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["with Jun-kun Wang, "and Jacob Abernethy"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "in submission"
publication_short = "in submission"

# Abstract and optional shortened version.
abstract = "We consider smooth convex optimization over the nuclear norm ball constraint. The classical algorithm for solving this class of problems is the Frank-Wolfe method, which only needs a top eigenvector computation for its linear optimization oracle and hence avoids the expensive projection on the nuclear norm ball. However, the Frank-Wolfe method is known to have a slow $O(1/T)$ convergence rate and is notoriously hard to accelerate for the nuclear norm ball problem. In this paper, we propose an accelerated projection-free algorithm which can achieve a faster convergence rate and avoids the expensive projection that requires a full matrix decomposition. Our method relies on a different oracle from the linear optimization oracle of Frank-Wolfe, which avoids an existing lower bound result for algorithms that rely on the linear optimization oracle. Still, the cost of our oracle is similar to the cost of the linear optimization oracle of Frank-Wolfe. Furthermore, the calls to the oracle in our method are easily parallelizable and consequently another level of acceleration can be achieved by exploiting multiple computational resources, while parallelization of the calls to the oracle remains an obstacle to the Frank-Wolfe method."

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
url_custom = []

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
