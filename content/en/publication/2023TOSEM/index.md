---
title: 'Characterizing Deep Learning Package Supply Chains in PyPI: Domains, Clusters, and Disengagement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Runzhi He
- Bing Xie
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2023-12-18T00:00:00Z"
doi: "10.1145/3640336"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Software Engineering and Methodology*
publication_short: In *TOSEM*

abstract: 'Deep learning (DL) frameworks have become the cornerstone of the rapidly developing DL field. Through installation dependencies specified in the distribution metadata, numerous packages directly or transitively depend on DL frameworks, layer after layer, forming DL package supply chains (SCs), which are critical for DL frameworks to remain competitive. However, vital knowledge on how to nurture and sustain DL package SCs is still lacking. Achieving this knowledge may help DL frameworks formulate effective measures to strengthen their SCs to remain competitive and shed light on dependency issues and practices in the DL SC for researchers and practitioners. In this paper, we explore the domains, clusters, and disengagement of packages in two representative PyPI DL package SCs to bridge this knowledge gap. We analyze the metadata of nearly six million PyPI package distributions and construct version-sensitive SCs for two popular DL frameworks: TensorFlow and PyTorch. We find that popular packages (measured by the number of monthly downloads) in the two SCs cover 34 domains belonging to eight categories. Applications, Infrastructure, and Sciences categories account for over 85% of popular packages in either SC and TensorFlow and PyTorch SC have developed specializations on Infrastructure and Applications packages respectively. We employ the Leiden community detection algorithm and detect 131 and 100 clusters in the two SCs. The clusters mainly exhibit four shapes: Arrow, Star, Tree, and Forest with increasing dependency complexity. Most clusters are Arrow or Star, while Tree and Forest clusters account for most packages (Tensorflow SC: 70.7%, PyTorch SC: 92.9%). We identify three groups of reasons why packages disengage from the SC (i.e., remove the DL framework and its dependents from their installation dependencies): dependency issues, functional improvements, and ease of installation. The most common reason in TensorFlow SC is dependency incompatibility and in PyTorch SC is to simplify functionalities and reduce installation size. Our study provides rich implications for DL framework vendors, researchers, and practitioners on the maintenance and dependency management practices of PyPI DL SCs.'

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2023TOSEM.pdf'
url_code: 'https://github.com/gaokai320/PyPI-DLSC'
url_dataset: 'https://zenodo.org/record/8079662'
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
