# Data Wrangling- WeRateDogs 
## by Oloruntoba James Moritiwon


## Dataset

**WeRateDogs** is a Twitter account with the handle ``@dog_rates`` that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of ``10``. The numerators, though? Almost always greater than ``10, 11/10, 12/10, 13/10,`` etc. Why? Because "they're good dogs Brent". WeRateDogs has over 4 million followers and has received international media coverage. The dataset can be found at urls: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv and https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv. Querying Twitter API for additional data Using the Tweepy would be needed to create a ``tweet_json.txt`` for complete data gathering.


## Summary of Findings

In the course of assessing and wrangling tweet and image data gotten through programmatic downloads in addition to data from Twitter API, 16 issues were detected and documented. However, only 13 were cleaned of which 10 were quality issues and the balance of 3 were tidyness issues. technicaally 2 out of the 3 left out were cleaned in the process of extracting only needed columns from json text!. It can be concluded that dataframes met the conditions of clean data after sucessful merger and storage into a master archive.
 
Data Analysis and Visualization were carried out on the master archive leading to conclusions that:

- Dogs with double identities tend to rate higher than those who identify with just one of the original doctionary terms.
- There is a strong relationship between favourite and retweet counts.
- Puppers is the largest dogtionary category of dogs represented by the dataset.



## Key Insights for Act Report

For the Act report, I gave priority to categories of dogtionary and how they affect dog ratings. Afterwards, I discussed about the relationship between favorite and retweets counts for dogs under study. I concluded by showing the distribution of dogs under review by dogtionary terms.  

I started with a bar chart showing dogs by dogtionary terms and their ratings, and went further to show a scatterplot relating favorite and retweet counts for dogs under review. Finally, I discussed the distribution of dogs under review by dogtionary terms. I made sure visualizations reported were proper and clearly labelled.