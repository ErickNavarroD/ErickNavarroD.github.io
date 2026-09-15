---
title: "Advancing Pediatric and Longitudinal DNA Methylation Studies with CellsPickMe, an Integrated Blood Cell Deconvolution Method"
authors:
- Maggie P. Fu
- Karlie Edwards
- Erick I. Navarro-Delgado
- Sarah M. Merrill
- Negusse T. Kitaba
- Chaini Konwar
- Piush Mandhane
- Elinor Simons
- Padmaja Subbarao
- Theo J. Moraes
- John W. Holloway
- Stuart E. Turvey
- Michael S. Kobor
author_notes:
- ""
date: "2025-04-24T00:00:00Z"
doi: "https://doi.org/10.1101/2025.04.22.649907"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*bioRxiv*"
publication_short: ""

abstract: Prospective birth cohorts offer the potential to interrogate the relation between early life environment and embedded biological processes such as DNA methylation (DNAme). These association studies are frequently conducted in the context of blood, a heterogeneous tissue composed of diverse cell types. Accounting for this cellular heterogeneity across samples is essential, as it is a main contributor to inter-individual DNAme variation. Integrated blood cell deconvolution of pediatric and longitudinal birth cohorts poses a major challenge, as existing methods fail to account for the distinct cell population shift between birth and adolescence. In this paper, we critically evaluated the reference-based deconvolution procedure and optimized its prediction accuracy for longitudinal birth cohorts using DNAme data from the Canadian Healthy Infant Longitudinal Development (CHILD) cohort. The optimized algorithm, CellsPickMe, integrates cord and adult references and picks DNAme features for each population of cells with machine learning algorithms. It demonstrated improved deconvolution accuracy in cord, pediatric, and adult blood samples compared to existing benchmark methods. CellsPickMe supports blood cell deconvolution across early developmental periods under a single framework, enabling cross-time-point integration of longitudinal DNAme studies. Given the increased resolution of cell populations predicted by CellsPickMe, this R package empowers researchers to explore immune system dynamics using DNAme data in population studies across the life course.

# Summary. An optional shortened abstract.
summary: CellsPickMe, an R package for reference-based blood cell deconvolution from DNA methylation data that integrates cord and adult references, improving accuracy in cord, pediatric and adult blood samples for longitudinal birth cohort studies.

tags:
- Epigenetics
- DNA methylation
- Cell type deconvolution
- R package
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.04.22.649907v1.full.pdf
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
