---
title: Predicting Cyber Vulnerability Exploits with Machine Learning
type: publication 
profile: false
# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Michel Edkrantz
- alan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2015-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-23T22:33:31.229562Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Thirteenth Scandinavian Conference on Artificial Intelligence*'
publication_short: ''

doi: 10.3233/978-1-61499-589-0-48

abstract: For an information security manager it can be a daunting task to keep up
  and assess which new cyber vulnerabilities to prioritize patching first. Every day
  numerous new vulnerabilities and exploits are reported for a wide variety of different
  software configurations. We use machine learning to make automatic predictions for
  unseen vulnerabilities based on previous exploit patterns. As sources for historic
  vulnerability data, we use the National Vulnerability Database (NVD) and the Exploit
  Database (EDB). Our work shows that common words from the vulnerability descriptions,
  external references, and vendor products, are the most important features to consider.
  Common Vulnerability Scoring System (CVSS) scores and categorical parameters, and
  Common Weakness Enumeration (CWE) numbers are redundant when a large number of common
  words are used, since this information is often contained within the vulnerability
  description. Using machine learning algorithms, it is possible to get a prediction
  accuracy of 83% for binary classification. In comparison, the performance differences
  between some of the algorithms are marginal with respect to metrics such as accuracy,
  precision, and recall. The best classifier with respect to both performance metrics
  and execution time is a linear time Support Vector Machine (SVM) algorithm. We conclude
  that in order to get better predictions the data quality must be enhanced.

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
links:
- name: URL
  url: https://ebooks.iospress.nl/doi/10.3233/978-1-61499-589-0-48
---


