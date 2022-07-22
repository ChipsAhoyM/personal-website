---
title: 'NEST: Neural Event Stack for Event-based Image Enhancement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chu Zhou
  - Hanyue Lou
  - and Boxin Shi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-10-23'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-7-20'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc. of European Conference on Computer Vision 2022*
publication_short: In *ECCV 2022*

abstract: Event cameras demonstrate unique characteristics such as high temporal resolution, low latency, and high dynamic range to improve performance for various image enhancement tasks. However, event streams cannot be applied to neural networks directly due to their sparse nature. To integrate events into traditional computer vision algorithms, an appropriate event representation is desirable, while existing voxel grid and event stack representations are less effective in encoding motion and temporal information. This paper presents a novel event representation named Neural Event STack (NEST), which satisfies physical constraints and encodes comprehensive motion and temporal information sufficient for image enhancement. We apply our representation on multiple tasks, which achieves superior performance on image deblurring and image super-resolution than state-of-the-art methods on both synthetic and real datasets. And we further demonstrate the possibility to generate high frame rate videos with our novel event representation.

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
url_pdf: 'https://ci.idm.pku.edu.cn/Teng_ECCV22d.pdf'
url_code: 'https://github.com/ChipsAhoyM/NEST'
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