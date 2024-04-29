---
title: "Beyond Voxel-Based Methods: Continuous Motion Modeling for Enhanced Deformable Image Registration"
authors:
- xia_li
- muheng_li
- damien_weber
- tony_lomax
- joachim_buhmann
- ye_zhang
date: "2024-05-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["abstract"]

# Publication name and optional abbreviated publication name.
publication: "The European Society for Radiotherapy and Oncology"
publication_short: "ESTRO 2024"

abstract: Intra-fraction motions are commonly estimated using deformable image registration (DIR). However, the conventional voxel-based methods can compromise accuracy, especially for large changes, affecting processes like dose accumulation and 4D dose optimization. Therefore, we introduce a novel way of representing the registration process, conceptualizing it as a continuous flow in both spatial and temporal realms. This innovative model effectively addresses the inherent limitations of voxel-based discretization, while offering a robust solution to challenges posed by large deformations. Most significantly, the sliding boundary problem, a challenge for classical methods like B-splines [1], can be solved effectively. 

# Summary. An optional shortened abstract.
summary: "Our novel approach, capitalizing on the power of INR, offers a means to model motion in a continuous manner for intra-fraction motion modelling. By representing the registration process as a continuous flow, we circumvent the limitations inherent to the classic voxel-based representations, particularly the dilemma of discretization. The tangible enhancements are evident: both INR-DIR (E2E and LDD) methods consistently outperformed classic B-splines regarding TRE, MAE, landmark, and Dice coefficients. Remarkably, the registration times were slashed by more than half. One of the standout features of our LDD method is its ability to handle reverse trajectories, a capability unattainable with prior techniques. This promises more robust and versatile image registration applications in radiotherapy."

tags:
- Source Themes
featured: false

links:
- name: Session Link
  url: https://www.estro.org/Congresses/ESTRO-2024/2462/theartofmorphing-advancementsandchallengesindeform
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
