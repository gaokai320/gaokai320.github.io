---
title: 'How to Get It Right? A Comprehensive Analysis of Challenges and Strategies for Software Release Notes on GitHub'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jianyu Wu
- Hao He
- admin
- Wenxin Xiao
- Jingyue Li
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2024-03-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Empirical Software Engineering*
publication_short: In *EMSE*

abstract: "Release notes (RNs) refer to the technical documentation that offers users, developers, and other stakeholders comprehensive information about the changes and updates of a new software version. Producing high-quality RNs can be challenging, and it remains unknown what issues developers commonly encounter and what effective strategies can be adopted to mitigate them. To bridge this knowledge gap, we conduct a manual analysis of 1,529 latest RN-related issues in the GitHub issue tracker by using multiple rounds of open coding and construct 1) a comprehensive taxonomy of RN-related issues with four dimensions validated through three semi-structured interviews; 2) an effective framework with eight categories of strategies to overcome these challenges. The four dimensions of RN-related issues revealed by the taxonomy and the corresponding strategies from the framework include: 1) Content (419, 25.47%): RN producers tend to overlook information rather than include inaccurate details, especially for breaking changes. To address this, effective completeness validations are recommended, such as managing Pull Requests, issues, and commits related to RNs; 2) Presentation (150, 9.12%): inadequate layout may bury important information and lead to end users' confusion, which can be mitigated by employing a hierarchical structure, standardized format, rendering RNs, and folding techniques; 3) Accessibility (303, 18.42%): many users find RNs inaccessible due to link deterioration, insufficient notification, and obfuscated RN locations. This can be alleviated by adopting appropriate locations and channels (such as project websites) and standardizing link management.; 4) Production (773, 46.99%): despite the high demand from RN producers, automating and standardizing the RN production process remains challenging. Developers resolve this problem by using some mature tools on GitHub (like Release Drafter). Additionally, offering guidance, clarifying responsibilities, and distributing workloads are effective in improving collaboration within the team. Mechanisms for distributing and verifying RNs are also selected to enhance synchronization management. Our taxonomy provides a comprehensive blueprint to improve RN production in practice and also reveals interesting future research directions. "

# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2024EMSE.pdf'
url_code: 'https://figshare.com/s/b86957f784a8c872c042'
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
