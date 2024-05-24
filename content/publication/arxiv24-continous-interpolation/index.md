---
title: "CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation"
authors:
- xia_li
- Runzhao Yang
- Xiangtai Li
- tony_lomax
- ye_zhang
- joachim_buhmann
date: "2024-11-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv 2024"
publication_short: "Arxiv 2024"

abstract: Motion information from 4D medical imaging offers critical insights into dynamic changes in patient anatomy for clinical assessments and radiotherapy planning and, thereby, enhances the capabilities of 3D image analysis. However, inherent physical and technical constraints of imaging hardware often necessitate a compromise between temporal resolution and image quality. Frame interpolation emerges as a pivotal solution to this challenge. Previous methods often suffer from discretion when they estimate the intermediate motion and execute the forward warping. In this study, we draw inspiration from fluid mechanics to propose a novel approach for continuously modeling patient anatomic motion using implicit neural representation. It ensures both spatial and temporal continuity, effectively bridging Eulerian and Lagrangian specifications together to naturally facilitate continuous frame interpolation. Our experiments across multiple datasets underscore the method's superior accuracy and speed. Furthermore, as a case-specific optimization (training-free) approach, it circumvents the need for extensive datasets and addresses model generalization issues. \footnote{The code will be made publicly available upon acceptance. 

# Summary. An optional shortened abstract.
summary: "In this work, we introduce a novel Continuous sPatial and Temporal (CPT) modeling approach for 4D medical image interpolation, addressing the limitations of discrete motion modeling in both spatial and temporal domains. By leveraging implicit neural representations and integrating an ODE solver, our method achieves superior accuracy and speed without requiring extensive training datasets or domain-specific fine-tuning. Through comprehensive experiments and ablation studies, we demonstrated the contributions of spatial and temporal continuity, as well as the robustness of our method across different datasets. CPT-Interp not only outperforms state-of-the-art methods but also exhibits remarkable generalization ability, making it a promising solution for clinical applications."

tags:
- Source Themes
featured: false

links:
url_pdf: 
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
