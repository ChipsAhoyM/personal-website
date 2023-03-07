---
title: 'Polarization Guided HDR Reconstruction via Pixel-Wise Depolarization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chu Zhou
  - Yufei Han
  - admin
  - Jin Han
  - Si Li
  - Chao Xu
  - and Boxin Shi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-03-06'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Image Processing (Early Access)
publication_short: In TIP 2023 (Early Access)

abstract: Taking photos with digital cameras often accompanies saturated pixels due to their limited dynamic range, and it is far too ill-posed to restore them. Capturing multiple low dynamic range images with bracketed exposures can make the problem less ill-posed, however, it is prone to ghosting artifacts caused by spatial misalignment among images. A polarization camera can capture four spatially-aligned and temporally-synchronized polarized images with different polarizer angles in a single shot, which can be used for ghost-free high dynamic range (HDR) reconstruction. However, real-world scenarios are still challenging since existing polarization-based HDR reconstruction methods treat all pixels in the same manner and only utilize the spatially-variant exposures of the polarized images (without fully exploiting the degree of polarization (DoP) and the angle of polarization (AoP) of the incoming light to the sensor, which encode abundant structural and contextual information of the scene) to handle the problem still in an ill-posed manner. In this paper, we propose a pixel-wise depolarization strategy to solve the polarization guided HDR reconstruction problem, by classifying the pixels based on their levels of ill-posedness in HDR reconstruction procedure and applying different solutions to different classes. To utilize the strategy with better generalization ability and higher robustness, we propose a network-physics-hybrid polarization-based HDR reconstruction pipeline along with a neural network tailored to it, fully exploiting the DoP and AoP. Experimental results show that our approach achieves state-of-the-art performance on both synthetic and real-world images.

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
url_pdf: 'https://ieeexplore.ieee.org/document/10061479'
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