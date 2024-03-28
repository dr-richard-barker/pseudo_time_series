---
description: These R codes were used to merge counts tables for IDEP1 analysis
---

# Example code used for multi-study meta-analysis



` R code ``` `

**`#Load libraries`**&#x20;

`library(tidyverse)`&#x20;

`library(data.table)`

**`#Set working directory setwd("New_Plant_Matrix")`**

`URLs<-c("https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-120_rna_seq_Normalized_Counts.csv?version17",  "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-38_rna_seq_Normalized_Counts.csv?version12",   "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-37_rna_seq_Normalized_Counts.csv?version11", "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-321_rna_seq_Normalized_Counts.csv?version4", "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-218_rna_seq_Normalized_Counts.csv?version10")`   &#x20;

`destFiles<-c("https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-120_rna_seq_Normalized_Counts.csv?version17", "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-38_rna_seq_Normalized_Counts.csv?version12", "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-37_rna_seq_Normalized_Counts.csv?version11", "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-321_rna_seq_Normalized_Counts.csv?version4",  "https://genelab-data.ndc.nasa.gov/genelab/static/media/dataset/GLDS-218_rna_seq_Normalized_Counts.csv?version10")`

**`#Download files from URLs and save them to destination files`**

`for (i in 1:length(URLs)){ download.file(URLs[i], destFiles[i]) }`

` PlantMetaMatrix <- read_csv("destFiles") ``` `



**If you want to get started these lines of code might help**

**Thanks for your help**
