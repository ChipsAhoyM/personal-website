---
title: 'A Residual Learning Approach to Deblur and Generate High Frame Rate Video with an Event Camera'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haoyu Chen
  - admin
  - Boxin Shi
  - Yizhou Wang
  - and Tiejun Huang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-08-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Multimedia
publication_short: In TMM 2022

abstract: Event cameras are bio-inspired cameras that can measure the intensity change asynchronously with high temporal resolution. One of the advantages of event cameras is that they suffer less from motion blur than traditional frame cameras when recording daily scenes with fast-moving objects. In this paper, we formulate the deblurring task on traditional cameras directed by events to be a residual learning one, and propose corresponding network architectures for effective learning of deblurring and high frame rate video generation tasks. We first train a modified U-Net network to restore a sharp image from a blurry image using the corresponding events. Then we train another similar network by replacing the downsampling blocks with blocks of the convolutional long short-term memory (ConvLSTM) to recurrently generate high frame rate video using the restored sharp image and part of the events. Benefitting from the blur-free events and the proposed learning strategy, the experimental results show that the proposed method outperforms state-of-the-art methods for generating sharp images and high frame rate videos.

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
url_pdf: 'https://ci.idm.pku.edu.cn/Chen_TMM22.pdf'
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