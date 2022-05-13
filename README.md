This repository contains code in order to replicate main findings from Carsten Schwemmer & Sebastian Jungkunz' paper ["Whose ideas are worth spreading? The representation of women and ethnic groups in TED talks"](https://www.tandfonline.com/doi/full/10.1080/2474736X.2019.1646102) (Political Research Exchange **2019** (1), 1-23). If you are interested in the analyses, please enjoy the [original paper](https://www.tandfonline.com/doi/full/10.1080/2474736X.2019.1646102) and consider the authors' replication files via the [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EUDWP3).

In short, Schwemmer and Jungkunz answered the question of how women and different ethnic groups are represented in TED talks. The data they gathered contains transcripts of over 2333 TED talks. Further, via a facial recognition API they were able to extract key characteristics of speakers, such as gender and ethnicity. Finally, by using the Youtube Data API they also extracted YT metadata, such as likes, comments and views.

With this immense data they were able to perform multiple analyses. In this small replication, I will solely replicate their topic model analyses which in more particular is a [structural topic model](https://cran.r-project.org/web/packages/stm/vignettes/stmVignette.pdf) with the aims of **a)** examine how many and which topics are discussed in TED talks and **b)** how gender and ethnicity influence the topic prevalence (*e.g., are women more likely to talk about technical topics than men?*).

<b>A html version of my replication can be found here: https://clandesv.github.io/ted-talks-STM/stm_replication.html</b>


