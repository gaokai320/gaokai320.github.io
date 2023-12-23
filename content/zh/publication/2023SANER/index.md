---
title: 'Characterize Software Release Notes of GitHub Projects: Structure, Writing Style, and Content'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jianyu Wu
- Weiwei Xu
- admin
- Jingyue Li
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2023-01-01T00:00:00Z"
doi: "10.1109/SANER56733.2023.00051"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 30th IEEE International Conference on Software Analysis, Evolution and Reengineering*
publication_short: In *SANER 2023*

abstract: 'Release notes (RNs) summarize important changes between two successive software releases to facilitate software upgrades and serve as means of communication between software and its users. However, existing research has shown that many users cannot extract the information they want from RNs effectively and efficiently due to poor structure and insufficient content. Many efforts have been devoted to categorizing documented information in RNs, however, how exactly RNs are organized, in what way RNs are written, and what is written in RNs with respect to project domains and release types remain under investigation. To bridge this knowledge gap, we manually analyzed 612 RNs from 233 top popular GitHub projects to characterize their Structure, Writing Style, and Content. We find 64.54% of RNs organize changes into hierarchical structures following three strategies, i.e., by Change Type, Affected Module, or Change Priority. And 11.60% of RNs adopt multiple strategies to present the changes. Among the three strategies to organize changes, by Change Type is mostly adopted. RNs of major releases and System Software are more likely to organize changes by Affected Module. We also find three types of Writing Styles: Expository, Descriptive, and Persuasive with increasing explanation information and manual effort, taking 30.07%, 34.80%, and 35.13% of RNs, respectively. 83.10% of RNs in System Software projects adopt the Descriptive and Persuasive writing style. For Content, we find System Software and Libraries & Frameworks projects are more likely to record Breaking Changes, while Software Tools projects emphasize Enhancements. Besides, Fixed Bugs and Security Changes are less common in RNs of major releases. Our findings not only serve practitioners with a roadmap for customizing high-quality RNs but also shed light on future research on automating RN.'

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2023SANER.pdf'
url_code: 'https://doi.org/10.6084/m9.figshare.21383280'
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
