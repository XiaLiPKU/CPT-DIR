---
title: "Gaussian Representation for Deformable Image Registration"
authors:
- Jihe Li*
- Fabian Zhang*
- xia_li
- Tianhao Zhang
- ye_zhang
- joachim_buhmann
date: "2024-11-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv 2024"
publication_short: "Arxiv 2024"

abstract: Deformable image registration (DIR) is a fundamental task in radiotherapy, with existing methods often struggling to balance computational efficiency, registration accuracy, and speed effectively. We introduce a novel DIR approach employing parametric 3D Gaussian control points achieving a better tradeoff. It provides an explicit and flexible representation for spatial deformation fields between 3D volumetric medical images, producing a displacement vector field (DVF) across all volumetric positions. The movement of individual voxels is derived using linear blend skinning (LBS) through localized interpolation of transformations associated with neighboring Gaussians. This interpolation strategy not only simplifies the determination of voxel motions but also acts as an effective regularization technique. Our approach incorporates a unified optimization process through backpropagation, enabling iterative learning of both the parameters of the 3D Gaussians and their transformations. Additionally, the density of Gaussians is adjusted adaptively during the learning phase to accommodate varying degrees of motion complexity. We validated our approach on the 4D-CT lung DIR-Lab and cardiac ACDC datasets, achieving an average target registration error (TRE) of 1.06 mm within a muchimproved processing time of 2.43 seconds for the DIR-Lab dataset over existing methods, demonstrating significant advancements in both accuracy and efficiency. 

# Summary. An optional shortened abstract.
summary: "This paper presented a novel deformable image registration (DIR) technique using parametric 3D Gaussian control points to model continuous spatial deformation fields effectively. By integrating transformation vectors with linear blend skinning (LBS) for voxel motion interpolation, our approach simplifies computational demands while ensuring high accuracy and efficiency. The adaptive density of Gaussian points further allows for precise handling of varying motion complexities."

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/pdf/2406.03394
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
