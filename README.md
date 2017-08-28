# Milestone Report

### Exploratory text analysis as part of Coursera's Capstone project. 

## Contents
- `README.md`
- `milestone_report.Rmd` - R Markdown script that does the following: downloads the text documents provided by Swiftkey to Coursera; takes a random sample of the documents; cleans text by removing punctuations, numbers, and stop words; transforms all text to lower case; creates a Word Cloud showing the most frequent words in the sample; applies N-gram models to estimate most common word sequences in the document; plots top 20 most common bigrams, trigrams and quadgrams.
- `milestone_report.html` - compiled HTML file with plots.

## Getting Started
- Run the `milestone_report.Rmd` script to generate the N-gram models.
- R packages used in this analysis: knitr, kableExtra, dplyr, plyr, ggplot2, SnowballC, wordcloud, RColorBrewer, stringi, tm, quanteda.
