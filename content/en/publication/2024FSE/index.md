---
title: 'PyRadar: Towards Automatically Retrieving and Validating Source Code Repository Information for PyPI Packages'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Weiwei Xu
- Wenhao Yang
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2024-04-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM International Conference on the Foundations of Software Engineering*
publication_short: In *FSE 2024*

abstract: "A package’s source code repository records the development history of the package, providing indispensable information for the use and risk monitoring of the package. However, a package release often misses its source code repository due to the separation of the package’s development platform from its distribution platform. To establish the link, existing tools retrieve the release’s repository information from its metadata, which, however, suffers from two limitations: the metadata may not contain or contain wrong information. Our analysis shows that existing tools can only retrieve repository information for up to 70.5% of PyPI releases. To address the limitations, this paper proposes PyRadar, a novel framework that utilizes the metadata and source distribution to automatically retrieve and validate the repository information for PyPI releases. We start with an empirical study to compare four existing metadata-based tools on 4,227,425 PyPI releases and analyze phantom files (files appearing in the release’s distribution but not in the release’s repository) in 14,375 correct package-repository links and 2,064 incorrect links. Based on the findings, we design PyRadar with three components, i.e., Metadata-based Retriever, Source Code Repository Validator, and Source Code-based Retriever, that progressively retrieves correct source code repository information for PyPI releases. In particular, the Metadata-based Retriever combines best practices of existing tools and successfully retrieves repository information from the metadata for 72.1% of PyPI releases. The Source Code Repository Validator applies common machine learning algorithms on six crafted features and achieves an AUC of up to 0.995. The Source Code-based Retriever queries World of Code with the SHA-1 hashes of all Python files in the release’s source distribution and retrieves repository information for 90.2% of packages in our dataset with an accuracy of 0.970. Both practitioners and researchers can employ the PyRadar to better use PyPI packages."

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2024FSE.pdf'
url_code: 'https://github.com/gaokai320/PyRadar'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ''
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
