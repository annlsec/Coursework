## Replication Materials: _Winning! Election Returns and Engagement in Social Media_

Replication materials for Calvo, Ventura, Aruguete and Waisbord "Winning! Election Returns and Engagement in Social Media", PLOS ONE, 2023,

> __Abstract:__
> This article analyzes social media engagement when elections are adjudicated to one of the contending parties. We extend existing models of political dialogue to explain differences in social media engagement (i.e. time-to-retweet) when users support the winner or losers of an election. We show that users who support the winning candidate are more engaged and have a lower time-to-retweet. We also show heterogeneity in Twitter engagement conditional on the number of followers, with accounts with more followers being less sensitive to the election result. We measure the effect of electoral adjudication using a regression discontinuity design, with estimates by winning or losing status, and for accounts with many followers (high authority) or with few followers (low authority). Analyses use Twitter data collected in Argentina (2019), Brazil (2018), the United Kingdom (2019), and the United States (2016).

The latest pre-print can be found [here](CVAW_winning_preprint.pdf). The published version is [here](https://journals.plos.org/plosone/article/authors?id=10.1371/journal.pone.0281475)

## Tutorial 

This README file provides an overview of the replications materials for the article. The R codes used in the article can be found under the folder **Codes**. The dehydrate tweets that allow for a replication of the data sources used in the articlesis under the folder **data**. All the images for the main paper are available at the folder output

If other researchers are interested in the processed datasets, please contact the authors directly. 

The codes below do not fully replicate the results since we cannot share the full hydrated datasets. However, they should work as a guide for the methods used in the paper, and could be applied to a similar collection of tweets from the Twitter API. 

#### code
- `main_code.py` (runs the main results of the paper)
- `appendix_code.py` (runs all results of the appendix)
- `additional_analysis.py` (additional analysis main paper)
- `prep_code.py` (does all the processing of the data)

#### data
- `survey_data_raw.csv` (raw data)
- `survey_data_clean.csv` (clean data)

#### output
- `figure_1.png` (figure 1)
- `figure_2.png` (figure 2)
- `figure_3.png` (figure 3)
- `figure_4.png` (figure 4)
- `figure_5.png` (figure 5)
- `figure_appendix_1.png` (figure 1 appendix with heteregenous effects)
- `figure_appendix_2.png` (figure 2 appendix results for polarization)
- `figure_appendix_3.png` (figure 3 appendix robustness checks)
