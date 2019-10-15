---
title: "Toward Computational Literature Review: Refining Expert-Built Dictionaries for Automated Analysis of Academic Texts, joint with Heather Haveman"
event:
event_url:
location:
summary: ""
abstract: "We develop an general-use, inductive method of generating domain-specific dictionaries through word embedding models. Our workflow has three steps: construct (query model with seed terms to develop core dictionaries), refine (maximize dictionary coherence and distinctiveness), and validate (using unsupervised clustering and hand coding). We are optimizing our approach by varying the core dictionary size, WEM generation method (pre-trained vs. native), and dictionary application method (count-based vs. vector projection). We also compare results from two test cases: charter school websites and a corpus of academic journal articles. Our method of creating and validating new and even complex dictionaries allows researchers in diverse domains an accessible, reproducible, and valid workflow for analyzing researcher-generated themes in texts. This represents a significant improvement on the idiosyncratic, domain-restrictive approach to dictionaries used by social scientists for decades."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: ""
date_end: ""
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'workflow for computational dictionary refinement'
  focal_point: Right

links:

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---

See [my talk on an early version of this method](https://vimeo.com/denoisestudios/review/307173343/1fa72da7e5) and [our developing code on this method.](https://github.com/jhaber-zz/wem4themes)
