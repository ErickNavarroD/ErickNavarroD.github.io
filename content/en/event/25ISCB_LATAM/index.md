---
title: RAMEN- Untangling gene-environment contributions to DNA methylome variability

event: International Conference on Bioinformatics 2024 ISCB-Latin America SoIBio CCBCOL
event_url: https://www.iscb.org/latam2024/home

location: CES University, Medellín, Colombia

summary: (English; 13 minutes) Oral presentation at the International Conference on Bioinformatics 2024 ISCB-Latin America SoIBio CCBCOL. 
abstract: "DNA methylation (DNAme) is an epigenetic mark that has gained attention under the Developmental Origins of Health and Disease framework due to its association with phenotypic changes and potential long-term stability. Genomic (G) and exposomic (E; totality of exposures a person experiences) differences have been reported as main sources of inter-individual DNAme variability. However, further research is needed to understand the genomic location and characteristics of regions with  variable DNAme, the degree to which genetics and environmental factors contribute to DNAme variability in these regions, and whether genetics and environment associate individually with DNAme or in combination. Here, we estimate the genome-exposome contribution to cord blood methylome variability in an integrative multi-omics analysis. 
Method: We identify genome-wide cord blood Variable Methylated Regions in two independent cohorts (CHILD and PREDO; overall n=1,662) accounting for the sparse and non-homogeneous coverage in the Illumina EPIC v1 array. To reduce the universe of compared models, we implement VMR-wise E and G variable selection procedure based on LASSO. We then fit single-variable G, E, pairwise additive (G+E) and interaction (GxE) linear models of VMR’s DNAme, and select the best one per VMR based on their AIC. To control for spurious associations, we implement a computationally fast permutation approach. 
Results: With a high percentage of winner models (59%), a higher proportion of DNAme variance explained (M = 0.22), and a full consistency across cohorts (100%), we identify genetics as a consistent main contributor to DNAme variability in cord blood usually in additive and interaction combinations with the prenatal exposome (44.4%). These results showcase the relevance of genetics in diverging DNAme patterns in early life. Furthermore, we introduce RAMEN (Regional Association of Methylome variability with Exposone and geNome; github.com/ErickNavarroD/RAMEN), a user-friendly R package for DNAme microarrays that improves the extraction of regional DNAme variability patterns and models their contributors while controlling for spurious associations expected by chance through state-of-the-art statistical techniques.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-11-12T11:00:00Z"
date_end: "2024-11-12T13:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2024-11-18T13:00:00Z"

authors: [Erick I. Navarro-Delgado]
tags: 
- Epigenetics
- Gene-environment interactions
- Software
- RAMEN

# Is this a featured talk? (true/false)
featured: true 

image:
  caption: ''
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=haDkCiJLvT0"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- genome-exposome-methylome

#Slides can be added in a few ways:

#- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using #`slides` parameter in the front matter of the talk file
#- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
#- **Embed** your slides (e.g. Google Slides) or presentation video on this page using #[shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

#Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be #added to the body of this page.
#you can also add text after the --- just like the lines above and this will be featured in the page. 
---

{{% callout note %}}
Click on the **Video** button above to watch the presentation.
{{% /callout %}}

