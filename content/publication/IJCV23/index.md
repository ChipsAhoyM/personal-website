---
title: 'Deblurring Low-Light Images with Events'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chu Zhou
  - admin
  - Jin Han
  - Jinxiu Liang
  - Chao Xu
  - Gang Cao
  - and Boxin Shi

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-02-06'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: International Journal of Computer Vision
publication_short: In IJCV 2023

abstract: Modern image-based deblurring methods usually show degenerate performance in low-light conditions since the images often contain most of the poorly visible dark regions and a few saturated bright regions, making the amount of effective features that can be extracted for deblurring limited. In contrast, event cameras can trigger events with a very high dynamic range and low latency, which hardly suffer from saturation and naturally encode dense temporal information about motion. However, in low-light conditions existing event-based deblurring methods would become less robust since the events triggered in dark regions are often severely contaminated by noise, leading to inaccurate reconstruction of the corresponding intensity values. Besides, since they directly adopt the event-based double integral model to perform pixel-wise reconstruction, they can only handle low-resolution grayscale active pixel sensor images provided by the DAVIS camera, which cannot meet the requirement of daily photography. In this paper, to apply events to deblurring low-light images robustly, we propose a unified two-stage framework along with a motion-aware neural network tailored to it, reconstructing the sharp image under the guidance of high-fidelity motion clues extracted from events. Besides, we build an RGB-DAVIS hybrid camera system to demonstrate that our method has the ability to deblur high-resolution RGB images due to the natural advantages of our two-stage framework. Experimental results show our method achieves state-of-the-art performance on both synthetic and real-world images.
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
url_pdf: 'https://link.springer.com/article/10.1007/s11263-023-01754-5'
url_code: 'https://github.com/ChipsAhoyM/Deblurring-Low-Light-Images-with-Events'
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