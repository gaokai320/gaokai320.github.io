---
title: 'On the Variability of Software Engineering Needs for Deep Learning: Stages, Trends, and Application Types'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zhixing Wang
- Audris Mockus
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2022-03-20T00:00:00Z"
doi: "10.1109/TSE.2022.3163576"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions of Software Engineering*
publication_short: In *TSE*

abstract: 'The wide use of Deep learning (DL) has not been followed by the corresponding advances in software engineering (SE) for DL. Research shows that developers writing DL software have specific development stages (i.e., SE4DL stages) and face new DL-specific problems. Despite substantial research, it is unclear how DL developers’ SE needs for DL vary over stages, application types, or if they change over time. To help focus research and development efforts on DL-development challenges, we analyze 92,830 Stack Overflow (SO) questions and 227,756 READMEs of public repositories related to DL. Latent Dirichlet Allocation (LDA) reveals 27 topics for the SO questions where 19 (70.4%) topics mainly relate to a single SE4DL stage, and eight topics span multiple stages. Most questions concern Data Preparation and Model Setup stages. The relative rates of questions for 11 topics have increased, for eight topics decreased over time. Questions for the former 11 topics had a lower percentage of accepting an answer than the remaining questions. LDA on README files reveals 16 distinct application types for the 227k repositories. We apply the LDA model fitted on READMEs to the 92,830 SO questions and find that 27% of the questions are related to the 16 DL application types. The most asked question topic varies across application types, with half primarily relating to the second and third stages. Specifically, developers ask the most questions about topics primarily relating to Data Preparation (2nd) stage for four mature application types such as Image Segmentation , and topics primarily relating to Model Setup (3rd) stage for four application types concerning emerging methods such as Transfer Learning . Based on our findings, we distill several actionable insights for SE4DL research, practice, and education, such as better support for using trained models, application-type specific tools, and teaching materials.'

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2022TSE.pdf'
url_code: 'https://github.com/gaokai320/SE4DL'
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
