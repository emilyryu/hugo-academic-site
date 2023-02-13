---
title: "Calibrated Recommendations for Users with Decaying Attention"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jon Kleinberg
- admin
- Eva Tardos

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2023-02-07T00:00:00Z"
doi: "10.48550/ARXIV.2302.03239"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv preprint

abstract: Recommendation systems capable of providing diverse sets of results are a focus of increasing importance, with motivations ranging from fairness to novelty and other aspects of optimizing user experience. One form of diversity of recent interest is _calibration_, the notion that personalized recommendations should reflect the full distribution of a user's interests, rather than a single predominant category --- for instance, a user who mainly reads entertainment news but also wants to keep up with news on the environment and the economy would prefer to see a mixture of these genres, not solely entertainment news. Existing work has formulated calibration as a subset selection problem; this line of work observes that the formulation requires the unrealistic assumption that all recommended items receive equal consideration from the user, but leaves as an open question the more realistic setting in which user attention decays as they move down the list of results. <br /> <br /> In this paper, we consider calibration with decaying user attention under two different models. In both models, there is a set of underlying genres that items can belong to. In the first setting, where items are represented by fine-grained mixtures of genre percentages, we provide a $(1-1/e)$-approximation algorithm by extending techniques for constrained submodular optimization. In the second setting, where items are coarsely binned into a single genre each, we surpass the $(1-1/e)$ barrier imposed by submodular maximization and give a $2/3$-approximate greedy algorithm. Our work thus addresses the problem of capturing ordering effects due to decaying attention, allowing for the extension of near-optimal calibration from recommendation _sets_ to recommendation _lists_.


# Summary. An optional shortened abstract.
summary: We study _calibrated recommendations_ for users whose attention decays over the course of a ranked list, meaning that not all recommended items receive equal consideration. For a _distributional_ model of genres, we extend tools from submodular optimization to provide a $(1-1/e)$-approximation algorithm to calibration. For a _discrete_ model of genres, we show that the natural greedy algorithm is a $2/3$-approximation. Our work thus addresses the problem of capturing ordering effects due to decaying attention, allowing for the extension of near-optimal calibration from recommendation _sets_ to recommendation _lists_. <br /> (This paper incorporates and supersedes our earlier paper on [ordered submodularity](https://arxiv.org/abs/2203.00233).)

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2302.03239.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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