---
title: 'An Exploratory Study of Deep Learning Supply Chain'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Xin Tan
- admin
- Minghui Zhou
- Li Zhang

# Author notes (optional)
author_notes:

date: "2022-01-01T00:00:00Z"
doi: "10.1145/3510003.3510199"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 44th International Conference on Software Engineering*
publication_short: In *ICSE 2022*

abstract: 'Deep learning becomes the driving force behind many contemporary technologies and has been successfully applied in many fields. Through software dependencies, a multi-layer supply chain (SC) with a deep learning framework as the core and substantial down-stream projects as the periphery has gradually formed and is constantly developing. However, basic knowledge about the structure and characteristics of the SC is lacking, which hinders effective support for its sustainable development. Previous studies on software SC usually focus on the packages in different registries without paying attention to the SCs derived from a single project. We present an empirical study on two deep learning SCs: TensorFlow and PyTorch SCs. By constructing and analyzing their SCs, we aim to understand their structure, application domains, and evolutionary factors. We find that both SCs exhibit a short and sparse hierarchy structure. Overall, the relative growth of new projects increases month by month. Projects have a tendency to attract downstream projects shortly after the release of their packages, later the growth becomes faster and tends to stabilize. We propose three criteria to identify vulnerabilities and identify 51 types of packages and 26 types of projects involved in the two SCs. A comparison reveals their similarities and differences, e.g., TensorFlow SC provides a wealth of packages in experiment result analysis, while PyTorch SC contains more specific framework packages. By fitting the GAM model, we find that the number of dependent packages is significantly negatively associated with the number of downstream projects, but the relationship with the number of authors is nonlinear. Our findings can help further open the "black box" of deep learning SCs and provide insights for their healthy and sustainable development.'

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2022ICSE.pdf'
url_code: 'https://github.com/SunflowerPKU/ICSE22_SC_Data'
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
