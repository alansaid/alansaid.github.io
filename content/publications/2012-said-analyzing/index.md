---
title: 'Analyzing weighting schemes in collaborative filtering: Cold start, post cold
type: publication 
profile: false  start and power users'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- alan
- B.J. Jain
- S. Albayrak

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2012-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-23T22:33:30.739810Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the ACM Symposium on Applied Computing*'
publication_short: ''

doi: 10.1145/2245276.2232114

abstract: Collaborative filtering recommender systems provide their users with relevant
  items based on information from other similar users. Popular collaborative filtering
  approaches such as Pearson correlation coefficient and cosine similarity, compute
  the similarity between users based on the set of their co-rated items. However,
  similarities are commonly computed without taking the popularity of the set of two
  users' co-rated items into consideration, e.g. an item rated by very many users
  should have less impact on the similarity measure, and analogously an item rated
  by few should have a larger impact on the similarity score of two users. In this
  paper, we investigate the effects of common weighting schemes on different types
  of users, i.e. new users with few ratings (so-called cold start users), post cold
  start users, and power users. Empirical studies over two datasets have shown in
  which of these cases weighting schemes are beneficial in terms of recommendation
  quality. © 2012 ACM.

# Summary. An optional shortened abstract.
summary: ''

tags:
- cold start
- recommender systems
- user modeling
- collaborative filtering
- diversity
- popularity
- item weighting scheme
- similarity metrics

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

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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


