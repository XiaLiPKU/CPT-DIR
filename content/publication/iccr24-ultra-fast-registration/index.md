---
title: 'Neural Graphics Primitives-based Deformable Image Registration for On-the-fly Motion Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - xia_li
  - Fabian Zhang
  - muheng_li
  - damien_weber
  - tony_lomax
  - joachim_buhmann
  - ye_zhang

date: '2024-07-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on the use of Computers in Radiation therapy
publication_short: ICCR 2024

abstract: "Intra-fraction motion in radiotherapy is commonly modeled using deformable image registration (DIR). However, existing methods often struggle to balance speed and accuracy, limiting their applicability in clinical scenarios. This study introduces a novel approach that harnesses Neural Graphics Primitives (NGP) to optimize the displacement vector field (DVF). Our method leverages learned primitives, processed as splats, and interpolates within space using a shallow neural network. Uniquely, it enables self-supervised optimization at an ultra-fast speed, negating the need for pre-training on extensive datasets and allowing seamless adaptation to new cases. We validated this approach on the 4D-CT lung dataset DIR-lab, achieving a target registration error (TRE) of 1.15±1.15 mm within a remarkable time of 1.77 seconds. Notably, our method also addresses the sliding boundary problem, a common challenge in conventional DIR methods."

# Summary. An optional shortened abstract.
summary: "In this study, we have successfully integrated NGP into DIR, a novel contribution that significantly enhances the accuracy and efficiency of medical image alignment as demonstrated on the DIR-lab dataset. The NGPDIR framework exhibits robust performance across various metrics, particularly in landmark alignment precision and the accommodation of anatomical sliding boundaries. This advancement not only propels the DIR field forward but also opens new avenues for real-time clinical applications, potentially transforming patient care with its rapid, reliable imaging capabilities."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Session Link
  url: https://iccr2024.org/schedule.html#session12

url_pdf: 'https://arxiv.org/pdf/2402.05568'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ultra-fast registration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
