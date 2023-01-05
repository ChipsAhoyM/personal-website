---
title: 'Polarization-Aware Low-Light Image Enhancement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chu Zhou
  - admin
  - Youwei Lyu
  - Si Li
  - Chao Xu
  - and Boxin Shi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-01-03'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-03'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Proc. of the AAAI Conference on Artificial Intelligence
publication_short: In AAAI 2023

abstract: Polarization-based vision algorithms have found uses in various applications since polarization provides additional physical constraints. However, in low-light conditions, their performance would be severely degenerated since the captured polarized images could be noisy, leading to noticeable degradation in the degree of polarization (DoP) and the angle of polarization (AoP). Existing low-light image enhancement methods cannot handle the polarized images well since they operate in the intensity domain, without effectively exploiting the information provided by polarization. In this paper, we propose a Stokes-domain enhancement pipeline along with a dual-branch neural network to handle the problem in a polarization-aware manner. Two application scenarios (reflection removal and shape from polarization) are presented to show how our enhancement can improve their results.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links: 
url_pdf: 'https://ci.idm.pku.edu.cn/Zhou_AAAI23.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

#SUPP: https://papers.nips.cc/paper/2021/file/5fd0b37cd7dbbb00f97ba6ce92bf5add-Supplemental.pdf

#CODE: https://github.com/fourson/Learning-to-dehaze-with-polarization

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example


---