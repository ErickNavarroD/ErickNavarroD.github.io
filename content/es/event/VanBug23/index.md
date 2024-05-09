---
title: RAMEN - an R package for modeling the genome and exposome contribution to DNA methylome variability

event: Vancouver Bioinformatics User Group meeting
event_url: https://www.vanbug.org/archive/2023/2023-09-21/

location: SFU Big Data Hub
address:
  street: Applied Sciences Building
  city: Burnaby
  region: BC
  postcode: 'V5A 0A7'
  country: Canada

summary: Presentación en la reunión mensual del Vancouver Bioinformatics User Group en septiembre de 2023. Acompañándome en la sesión, después de mí expone mi supervisora, la Dra. Keegan Korthauer, quien expone los temas de investigación que llevamos a cabo en el laboratorio.
abstract: "*Esta plática es en inglés. This talk features my work followed by a presentation of my supervisor Dr. Korthauer, who further details the research that is carried out in our lab.* DNA methylation (DNAme) is an epigenetic mark that can regulate the genome, and its variability has been associated with phenotypic changes. Studies in birth tissues suggest that genetics (G) and environmental (E) factors jointly better explain DNAme variability in most of the newborn epigenome (75-89%). However, limitations of previous works are that the prenatal environment has been represented by a small set of variables (<20). Furthermore, past methodologies can be improved by clustering proximal DNAme sites into regions that exhibit high chances of working as units, taking into account the design of the DNAme microarrays, and implementing embedded variable selection methods. Our current study addresses these gaps and estimates the contribution of G and E to DNAme variability at birth. Using cord blood samples of CHILD, a comprehensively characterized and geographically diverse Canadian cohort (n=712, 92 E variables), we aimed to 1) identify Variable Methylated Regions (VMRs) which consist of two or more highly variable and correlated probes < 1kb apart or of highly variable probes with no nearby measured CpG in the array, and 2) analyze the association of VMR DNAme levels with G across cis SNPs ≤ 1 Mb apart and E across four main dimensions of the prenatal environment (parental psychosocial, maternal health, built environment, and maternal nutrition). Our work highlights the role of G in DNAme and the importance of addressing it in epigenetic association studies jointly with environmental exposures. Furthermore, we developed an R package: Regional Association of Methylation variability with ENvironment and genotype (RAMEN; github.com/ErickNavarroD/RAMEN), which provides the community an easy-to-use pipeline to replicate our methodology in other cohorts and reproduce our findings."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-09-21T11:00:00Z"
date_end: "2023-09-21T13:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-09-21T13:00:00Z"

authors: [Erick I. Navarro-Delgado]
tags: 
- Epigenetics
- Multi-omic modeling
- Software
- DOHaD

# Is this a featured talk? (true/false)
featured: true 

image:
  caption: 'Image credit: [**VanBug**](https://www.vanbug.org)'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/ErickNavDel
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=hoU7QEJIAPw"

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

