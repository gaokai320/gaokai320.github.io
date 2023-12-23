---
title: 'Demystifying Software Release Note Issues on GitHub'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jianyu Wu
- Hao here
- Wenxin Xiao
- admin
- Minghui Zhou

# Author notes (optional)
author_notes:

date: "2022-03-09T00:00:00Z"
doi: "10.1145/3524610.3527919"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 30th International Conference on Program Comprehension*
publication_short: In *ICPC 2022*. <b style="color:red;">🏆ACM SIGSOFT杰出论文奖</b>

abstract: 'Release notes (RNs) summarize main changes between two consecutive software versions and serve as a central source of information when users upgrade software. While producing high quality RNs can be hard and poses a variety of challenges to developers, a comprehensive empirical understanding of these challenges is still lacking. In this paper, we bridge this knowledge gap by manually analyzing 1,731 latest GitHub issues to build a comprehensive taxonomy of RN issues with four dimensions: Content, Presentation, Accessibility, and Production. Among these issues, nearly half (48.47\%) of them focus on Production; Content, Accessibility, and Presentation take 25.61\%, 17.65\%, and 8.27\%, respectively. We find that: 1) RN producers are more likely to miss information than to include incorrect information, especially for breaking changes; 2) improper layout may bury important information and confuse users; 3) many users find RNs inaccessible due to link deterioration, lack of notification, and obfuscate RN locations; 4) automating and regulating RN production remains challenging despite the great needs of RN producers. Our taxonomy not only pictures a roadmap to improve RN production in practice but also reveals interesting future research directions for automating RN production.'

# Summary. An optional shortened abstract.
summary:

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2022ICPC.pdf'
url_code: 'https://doi.org/10.6084/m9.figshare.18777650'
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
