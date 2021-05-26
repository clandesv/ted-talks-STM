# Overview

Original Paper can be found here: https://www.tandfonline.com/doi/full/10.1080/2474736X.2019.1646102

This repository contains R-code to analyze data from a dataset containing transcripts and other metadata of TED Talks Data, namely a Structural Topic Model and some visualizations.

# Data

- get the original data (ted_main_dataset.tsv) from the harvard dataverse: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EUDWP3

- to avoid running the first topic model (k=20) on your own (it might take some time depending on your hardware), simply load "ted_first_model.RData"

- to avoid running the overall 5 topic models (K=20,30,40,50) (it might take some more time depending on your hardware), load "ted_all_topic_models.RData"

- to skip all prior steps and to load the final model (k=30), load "ted_final_topic_model.RData"
