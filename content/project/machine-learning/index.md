---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Machine Learning"
summary: ""
#authors: [Pascal Friederich, Alexander Stroh, Bradley Ladewig]
tags: []
categories: []
date: [2021-01-21T16:20:53+01:00]

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Predictions of the CNN model of a) drag coefficient $C_f$ and b) Stanton number St compared to the ground truth on a validation set."
  focal_point: "Top"
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
This is a preliminary project exploring the potential for Machine Learning in Chemical Engineering research. It is a collaboration with Alexander Stroh and Pascal Friederich with assistance from Matthias Schniewind (PhD student of Pascal Friederich).

In our preliminary work, we have shown that it is possible to create a dataset of detailed computation fluid dynamic simulations (CFD) for fluid flow through a two-dimensional channel with a range of different, largely random, pertubations to the wall structure. Using a portion of these results it is possible to train a Machine Learning (ML) model, which is then able to predict with a high degree of accuracy, the validation results (based only on the input wall structure and with no knowledge of fluid dynamics).

We aim to extend this concept to design of more complex, real-world engineering devices, which we can build and test in the laboratory. Our long-term plan is to design complex three-dimensional structures for challenging chemical engineering unit operations (such as contacting of multiple phases for intensified reactions in microfludic channels), structures which are so complex they cannot be manufactured using conventional methods and need to be printed using a metal 3D printer.

The excellent metal 3D printing design and manufacturing facilities in the IMVT will be utilised, including a Selective Laser Melting (SLM) printer and a binder jetting printer. In addition, advanced design and analysis software from Siemens is available.

Our preliminary results are available as a preprint on arXiv. [https://arxiv.org/abs/2101.08130](https://arxiv.org/abs/2101.08130)

The video below describes our work.

{{< youtube 5054M6JRIyc >}}

This project is the first collaboration between Alexander Stroh (ISTM), Pascal Friederich (IAI) and Bradley Ladewig (IMVT). We were assisted by Matthias Schniewind, PhD student of Pascal Friederich. Below we talk about how enjoyable this interdisciplinary collaboration was.

{{< youtube -dmVR7E0uxg >}}
