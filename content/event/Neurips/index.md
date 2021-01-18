---
title: NeurIPS 2020 Oral Presentation 

event: NeurIPS 2020
event_url: https://nips.cc/

location: Virtual Talk
address:
  street: ""
  city: ""
  region: ""
  postcode: ""
  country: ""

summary: An Oral Presentation on Look-Ahead MAML
abstract: "The continual learning problem involves training models with limited capacity to perform well on a set of an unknown number of sequentially arriving tasks. While meta-learning shows great potential for reducing interference between old and new tasks, the current training procedures tend to be either slow or offline, and sensitive to many hyper-parameters. In this work, we propose Look-ahead MAML (La-MAML), a fast optimisation-based meta-learning algorithm for online-continual learning, aided by a small episodic memory. Our proposed modulation of per-parameter learning rates in our meta-learning update allows us to draw connections to prior work on hypergradients and meta-descent. This provides a more flexible and efficient way to mitigate catastrophic forgetting compared to conventional prior-based methods.La-MAML achieves performance superior to other replay-based, prior-based and meta-learning based approaches for continual learning on real-world visual classification benchmarks."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-09T09:15:00Z"
date_end: "2020-12-09T09:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2020-11-30T00:00:00Z"

authors: 
- admin
- Gunshi Gupta
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Our Neurips Oral Talk on La-MAML'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/KarmeshYadav
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://nips.cc/virtual/2020/public/poster_85b9a5ac91cd629bd3afe396ec07270a.html"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- content/publication/La-MAML/index.md