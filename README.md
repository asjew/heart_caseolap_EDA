# Exploratory Data Analysis of Cardiac CaseOLAP Scores

Research project for the [UCLA Integrated Data Science Training in Cardiovascular Medicine (iDISCOVER) Program](https://cvdatascience.dgsom.ucla.edu/pages/). Supervised by Dr. J. Harry Caufield.

## Introduction

The heart proteome is an extensive list of proteins that are expressed in the heart by an organism. Compiling a proteome requires large experiments and many resources. There already exists various human heart proteomes that we can reference, but the proteomes do not always match and are not complete. We want to analyze published biomedical literature to discover proteins that are missing from existing heart proteomes.

Our goal is to reference previous experimental results to see what has been observed about those cardiac proteins in the past. We want to know which proteins are specific to the heart and what relationships exists between these proteins and heart diseases. We want to demonstrate how text mining of biomedical literature and subsequent analysis can be used to assemble a full cardiac proteome and reveal potential protein-disease relationships.

## Repository Navigation

```
heart_caseolap_EDA
│   README.md   
└─── Analysis
│   │
│   └─── Rmd_Files
│       │
│       └─── Human_Abstract_Feb_23_2021
│           │   caseolap_analysis_human_abstract.Rmd
│       │
│       └─── Human_Full_Mar_29_2021
│           │   ARR_zscore.PNG
│           │   ...
│           │   VOO_zscore.PNG
│           │   caseolap_analysis_human_full.Rmd
│       |
│       └─── Mouse_Rat_Abstract_Feb_23_2021
│           │   caseolap_analysis_mouse_rat_abstract.Rmd 
│   │
│   └─── Rmd_Output
│       │   caseolap_analysis_human_abstract.pdf
│       │   caseolap_analysis_human_full.pdf 
│       │   caseolap_analysis_mouse_rat_abstract.pdf
│   │
│   └─── STATS 199 Lab Report.pdf
│   
└─── Data
│   │
│   └─── Human cardiac tissue-specific proteome - Feb 23 2021 
│       │
│       └─── input
│           │   ...
│       │
│       └─── results
│           │   caseolap.csv
│           │   ...
│       |note.txt
│   │
│   └─── Human reference proteome - Mar 29 2021 
│       │
│       └─── input
│           │   ...
│       │
│       └─── results
│           │   caseolap.csv
│           │   ...
│   │
│   └─── Mouse+rat cardiac tissue-specific proteome - Feb 23 2021 
│       │
│       └─── input
│           │   ...
│       │
│       └─── results
│           │   caseolap.csv
│           │   ...
│       |note.txt
```
## File Navigation
* `Analysis`
  - `Rmd_Files`: R Markdown files to view R code
  - `Rmd_Output`: To view PDF output of R Markdown files
* `Data`
  - Go to `caseolap.csv` files in each folder to view datasets used in analysis