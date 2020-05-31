---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mortality in London"
subtitle: ""
summary: ""
authors: []
tags: [mortality, modelling, statistics]
categories: []
date: 2020-05-31T11:10:55+01:00
lastmod: 2020-05-31T11:10:55+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

We are looking mortality models for simulated death data using a negative binomial likelihood. The dataset is for the London borough of Hammersmith and Fulham only.

# Life expectancy over time
Firstly for the _BYM_ model.
<iframe seamless src="le_fig_BYM_nb.html" width="100%" height="500"></iframe>

And now for the _hierarcical_ model.
<iframe seamless src="le_fig_hier_nb.html" width="100%" height="500"></iframe>

Both models show a Marmot curve and non-linarity in time.

# Life expectancy map
_BYM_ map...
<iframe seamless src="le_map_BYM_nb.html" width="100%" height="500"></iframe>

and _hierarchical_ map.
<iframe seamless src="le_map_hier_nb.html" width="100%" height="500"></iframe>

Adjacent spatial units have more similar life expectancies in the BYM model than the hierarchical model, indicating more spatial smoothing.
