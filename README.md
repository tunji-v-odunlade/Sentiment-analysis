# Sentiment-analysis of TED talks of Jack Andraka and Jennifer Pahlka
This repository contains an analysis of the TED Talk speeches by Jack Andraka and Jennifer Pahlka. The project focuses on exploring their language usage, sentiment, and themes covered in their respective talks. The analysis was conducted using R programming language and various packages for data manipulation and visualization.

## Introduction
This project aims to analyze TED Talk speeches by Jack Andraka and Jennifer Pahlka. The primary objectives include identifying the most frequently used words, comparing their language usage, and conducting sentiment analysis. Jack Andraka's talk focuses on a pancreatic cancer test, while Jennifer Pahlka's talk discusses coding for better government.

## Methods
### Packages for Analysis
The analysis employs various R packages, including dsEssex, tidyverse, tidytext, dplyr, and ggrepel.

## Loading of Dataset
The TED Talk dataset was sourced from the dsEssex R package. The speeches by Jack Andraka and Jennifer Pahlka were selected using the filter() function.

## Tidying and Removal of Stopwords
Text data was processed using the unnest_tokens() function and stopwords were removed with the anti_join() function. Word frequency for each speaker was calculated using the count() function.

## Top Words Visualization
A bar chart, created using ggplot2, illustrates the top 20 words used by each speaker. The chart also compares words used at least 8 times by both speakers.

## Sentiment Analysis
Sentiment scores were calculated using the NRC lexicon. Odds ratios and logarithms of sentiments for each speaker were computed. The relationship between sentiment and the logarithm of odds ratio was visualized.

## Results
### Top Words of the TED Speakers
A bar chart showcases the top 20 words used by Jack Andraka and Jennifer Pahlka. The word choices reflect the central themes of their respective talks.

## Comparison of Words Used
A comparison plot demonstrates the occurrence of words used by both speakers at least 8 times. The lack of strong correlation suggests distinct speech content.

## Sentiment Profile of the Speakers
A graph indicates the correlation between sentiment and the logarithm of the odds ratio for each speaker. Both speakers exhibit positive correlation between positive emotions and odds ratio.

## Conclusion
In summary, this analysis reveals that Jennifer Pahlka's speech encompasses a broader range of subjects and vocabulary compared to Jack Andraka's. While Jack's focus is on a pancreatic cancer test, Jennifer discusses technology's impact on government and society. Her sophisticated language usage and rhetorical devices enhance audience engagement. Despite differing themes, Jennifer's talk demonstrates a deep understanding of the interplay between technology, government, and society.

For the complete code and detailed analysis, please refer to the original publication on [RPubs](https://rpubs.com/vodunlade/1075235).
