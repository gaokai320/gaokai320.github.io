---
title: 'Understanding and Remediating Open-Source License Incompatibilities in the PyPI Ecosystem'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiwei Xu
  - Hao He
  - admin
  - Minghui Zhou

# Author notes (optional)
author_notes:

date: '2023-07-18T00:00:00Z'
doi: '10.1109/ASE56229.2023.00175'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 38th IEEE/ACM International Conference on Automated Software Engineering*
publication_short: In *ASE 2023*

abstract: |-
  The reuse and distribution of open-source software must be in compliance with its accompanying open-source license. In modern packaging ecosystems, maintaining such compliance is challenging because a package may have a complex multi-layered dependency graph with many packages, any of which may have an incompatible license. Although prior research ﬁnds that license incompatibilities are prevalent, empirical evidence is still scarce in some modern packaging ecosystems (e.g., PyPI). It also remains unclear how developers remediate the license incompatibilities in the dependency graphs of their packages (including direct and transitive dependencies), let alone any automated approaches.

  To bridge this gap, we conduct a large-scale empirical study of license incompatibilities and their remediation practices in the PyPI ecosystem. We ﬁnd that 7.27% of the PyPI package releases have license incompatibilities and 61.3% of them are caused by transitive dependencies, causing challenges in their remediation; for remediation, developers can apply one of the ﬁve strategies: migration, removal, pinning versions, changing their own licenses, and negotiation. Inspired by our ﬁndings, we propose S ILENCE , an SMT-solver-based approach to recommend license incompat- ibility remediations with minimal costs in package dependency graph. Our evaluation shows that the remediations proposed by S ILENCE can match 19 historical real-world cases (except for migrations not covered by an existing knowledge base) and have been accepted by ﬁve popular PyPI packages whose developers were previously unaware of their license incompatibilities.


# Summary. An optional shortened abstract.
summary:

tags:

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/papers/2023ASE.pdf'
url_code: 'https://figshare.com/s/1fcea61928e416533380'
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
