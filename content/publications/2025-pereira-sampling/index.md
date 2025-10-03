---
title: 'On the Reliability of Sampling Strategies in Offline Recommender Evaluation'
type: publication
profile: false

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Bruno L Pereira
- alan
- Rodrygo Santos

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

abstract: "Offline evaluation plays a central role in benchmarking recommender systems when online testing is impractical or risky. However, it is susceptible to two key sources of bias: exposure bias, where users only interact with items they are shown, and sampling bias, introduced when evaluation is performed on a subset of logged items rather than the full catalog. While prior work has proposed methods to mitigate sampling bias, these are typically assessed on fixed logged datasets rather than for their ability to support reliable model comparisons under varying exposure conditions or relative to true user preferences. In this paper, we investigate how different combinations of logging and sampling choices affect the reliability of offline evaluation. Using a fully observed dataset as ground truth, we systematically simulate diverse exposure biases and assess the reliability of common sampling strategies along four dimensions: sampling resolution (recommender model separability), fidelity (agreement with full evaluation), robustness (stability under exposure bias), and predictive power (alignment with ground truth). Our findings highlight when and how sampling distorts evaluation outcomes and offer practical guidance for selecting strategies that yield faithful and robust offline comparisons."


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
  url: https://arxiv.org/abs/2508.05398
- icon: 'open-access'
  icon_pack: ai
  name: ACM
  url: https://dl.acm.org/doi/full/10.1145/3705328.3748086
- icon: doi
  name: DOI
  icon_pack: ai
  url: https://doi.org/10.1145/3705328.3748086


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

