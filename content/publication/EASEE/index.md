+++
title = "More Efficient Exploration with Symbolic Priors on Action Sequence Equivalences"
date = 2021-10-20T12:11:00+01:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nathan Grinsztajn", "Toby Johnstone", "Johan Ferret", "Philippe Preux"]

author_notes = ["*Equal contribution", "*Equal contribution"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["3"]

# Publication name and optional abbreviated version.
# publication = "Advances in [IEEE ADPRL](http://www.ieeessci2020.org/symposiums/adprl.html) (ADPRL 2020)"
# publication_short = "[IEEE ADPRL](http://www.ieeessci2020.org/symposiums/adprl.html)"
# publication_extra = "[spotlight -- 4% acceptance rate]"

# Abstract and optional shortened version.
abstract = """Incorporating prior knowledge in reinforcement learning algorithms is mainly an open question. Even when insights about the environment dynamics are available, reinforcement learning is traditionally used in a tabula rasa setting and must explore and learn everything from scratch.
In this paper, we consider the problem of exploiting priors about action sequence equivalence: that is, when different sequences of actions produce the same effect.
We propose a new local exploration strategy calibrated to minimize collisions and maximize new state visitations. We show that this strategy can be computed at little cost, by solving a convex optimization problem.
By replacing the usual epsilon-greedy strategy in a DQN, we demonstrate its potential in several environments with various dynamic structures."""

# Is this a selected publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
# tags = ["Source Themes"]
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "EASEE.pdf"
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

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
