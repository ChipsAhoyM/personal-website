---
title: 'All-in-focus Imaging from Event Focal Stack'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hanyue Lou
  - admin
  - Yixin Yang
  - and Boxin Shi

# Author notes (optional)
author_notes:
 - 'Equal contribution'
 - 'Equal contribution'

date: '2023-03-07'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-07'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Proc. of Conference on Computer Vision and Pattern Recognition 2023
publication_short: In CVPR 2023

abstract: Traditional focal stack methods require multiple shots to capture images focused at different distances of the same scene, which cannot be applied to dynamic scenes well. Generating a high-quality all-in-focus image from a single shot is challenging, due to the highly ill-posed nature of the single-image defocus and deblurring problem. In this paper, to restore an all-in-focus image, we propose the event focal stack which is defined as event streams captured during a continuous focal sweep. Given an RGB image focused at an arbitrary distance, we explore the high temporal resolution of event streams, from which we automatically select refocusing timestamps and reconstruct corresponding refocused images with events to form a focal stack. Guided by the neighbouring events around the selected timestamps, we can merge the focal stack with proper weights and restore a sharp all-in-focus image. Experimental results on both synthetic and real datasets show superior performance over state-of-the-art methods.

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

# - name: Supp
#   url: https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660649-supp.pdf

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Lou_All-in-Focus_Imaging_From_Event_Focal_Stack_CVPR_2023_paper.pdf'
url_code: 'https://github.com/HYLZ-2019/EFS'
url_dataset: ''
url_poster: ''
url_project: 'https://hylz-2019.github.io/EFS'
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