---
title: "Ordered Submodularity and its Applications to Diversifying Recommendations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jon Kleinberg
- admin
- Eva Tardos

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2022-03-02T00:00:00Z"
doi: "10.48550/arXiv.2203.00233"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv preprint

abstract: A fundamental task underlying many important optimization problems, from influence maximization to sensor placement to content recommendation, is to select the optimal group of _k_ items from a larger set. Submodularity has been very effective in allowing approximation algorithms for such subset selection problems. However, in several applications, we are interested not only in the elements of a set, but also the _order_ in which they appear, breaking the assumption that all selected items receive equal consideration. One such category of applications involves the presentation of search results, product recommendations, news articles, and other content, due to the well-documented phenomenon that humans pay greater attention to higher-ranked items. As a result, optimization in content presentation for diversity, user coverage, calibration, or other objectives more accurately represents a sequence selection problem, to which traditional submodularity approximation results no longer apply. Although extensions of submodularity to sequences have been proposed, none is designed to model settings where items contribute based on their position in a ranked list, and hence they are not able to express these types of optimization problems. In this paper, we aim to address this modeling gap. Here, we propose a new formalism of _ordered submodularity_ that captures these ordering problems in content presentation, and more generally a category of optimization problems over ranked sequences in which different list positions contribute differently to the objective function. We analyze the natural ordered analogue of the greedy algorithm and show that it provides a 2-approximation. We also show that this bound is tight, establishing that our new framework is conceptually and quantitatively distinct from previous formalisms of set and sequence submodularity.

# Summary. An optional shortened abstract.
summary: We present a new formalism of _ordered submodularity_ that captures a useful class of optimization problems over ranked sequences, in which different list positions contribute differently to the objective function. We show that the natural greedy algorithm is a 2-approximation, and that this performance guarantee is tight. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2203.00233.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---