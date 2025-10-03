---
title: 'The Hidden Cost of Defaults in Recommender System Evaluation'
type: publication
profile: false

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hannah Berling
- Robin Svahn
- alan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-09-25'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-25T00:00:00.076957Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the Nineteenth ACM Conference on Recommender Systems *RecSys*'
publication_short: ''

doi: ''

abstract: "Hyperparameter optimization is critical for improving the performance of recommender systems, yet its implementation is often treated as a neutral or secondary concern. In this work, we shift focus from model benchmarking to auditing the behavior of RecBole, a widely used recommendation framework. We show that RecBole’s internal defaults, particularly an undocumented early-stopping policy, can prematurely terminate Random Search and Bayesian Optimization. This limits search coverage in ways that are not visible to users. Using six models and two datasets, we compare search strategies and quantify both performance variance and search path instability. Our findings reveal that hidden framework logic can introduce variability comparable to the differences between search strategies. These results highlight the importance of treating frameworks as active components of experimental design and call for more transparent, reproducibility-aware tooling in recommender systems research. We provide actionable recommendations for researchers and developers to mitigate hidden configuration behaviors and improve the transparency of hyperparameter tuning workflows."


# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
- icon: 'arxiv'
  icon_pack: ai
  name: preprint
  url: https://arxiv.org/abs/2508.21180
- icon: 'open-access'
  icon_pack: ai
  name: ACM
  url: https://dl.acm.org/doi/full/10.1145/3705328.3759321
- icon: doi
  name: DOI
  icon_pack: ai
  url: https://doi.org/10.1145/3705328.3759321


# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

