---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Temporal Point Processes and Smart Broadcasting"
summary: "Project that explores various algorithms in temporal point processes. Also explores one potential use-case in smart broadcasting of messages."
authors: ["Ayan Majumdar"]
tags: ["Data Science"]
categories: []
date: 2020-08-20T11:07:28+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Image courtesy [ICML '18 tutorial](http://learning.mpi-sws.org/tpp-icml18/)"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The project comprises studying various algorithms to analyze temporal point processes, including Hawkes algorithm, RedQueen, Smart Poisson. 
I look at the sampling and fitting of some of these algorithms, specifically the Hawkes process in an efficient way using Ogata's thinning method.

Finally, I apply these techniques to a use-case to solve the problem of smart broadcasting of messages by users of a social network.
The goal is to find optimal moments for users to post messages in order to have maximum exposure for their followers.
The solution is to use such temporal point processes to fit the whole message posting scenario.
Then, we sample from this process to find optimal times to broadcast.

**This project was completed as part of the Human-centred Machine Learning course at Saarland University.**
