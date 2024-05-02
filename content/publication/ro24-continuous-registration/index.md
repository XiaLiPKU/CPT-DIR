---
title: "Continuous sPatial-Temporal Deformable Image Registration (CPT-DIR) for motion modelling in radiotherapy: beyond classic voxel-based methods"
authors:
- xia_li
- muheng_li
- tony_lomax
- joachim_buhmann
- ye_zhang
date: "2024-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: "Arxiv 2024"

abstract: "Background and purpose: Deformable image registration (DIR) is a crucial tool in radiotherapy for extracting and modelling organ motion. However, when significant changes and sliding boundaries are present, it faces compromised accuracy and uncertainty, determining the subsequential contour propagation and dose accumulation procedures. Materials and methods: We propose an implicit neural representation (INR)-based approach modelling motion continuously in both space and time, named Continues-sPatial-Temporal DIR (CPT-DIR). This method uses a multilayer perception (MLP) network to map 3D coordinate (x,y,z) to its corresponding velocity vector (vx,vy,vz). The displacement vectors (dx,dy,dz) are then calculated by integrating velocity vectors over time. The MLP's parameters can rapidly adapt to new cases without pre-training, enhancing optimisation. The DIR's performance was tested on the DIR-Lab dataset of 10 lung 4DCT cases, using metrics of landmark accuracy (TRE), contour conformity (Dice) and image similarity (MAE)." 

# Summary. An optional shortened abstract.
summary: "In summary, the innovative CPT-DIR approach, integrating principles of INR and LDDMM, represents a11 significant departure from traditional voxel-based methods in DIR. By adopting a paradigm of continuous motion modelling, we transcend the limitations inherent in voxel-based representations, offering a more robust, automatic and versatile solution. Leveraging spatial continuity, we effectively handle the intricacies of sliding organ boundaries, while temporal continuity alleviates the complexities associated with significant anatomical changes over time. The tangible benefits are evident in its superior performance compared to classic B-splines methods. CPT-DIR consistently achieves better performance by all kinds of evaluation matrices. Additionally, the efficiency gains are substantial, with registration times slashed by more than half." 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2405.00430'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
  - continuous registration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
