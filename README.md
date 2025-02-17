# phase-4-project
## Sentiment Analysis
## Problem Statement
Financial markets are highly responsive to public sentiment, which fluctuates based on economic conditions, market trends, and unforeseen events. Traditional sentiment analysis techniques often struggle to capture these rapid changes, making it difficult for investors to make well-informed decisions. Social media platforms like Twitter provide a vast, real-time stream of public opinion, offering an opportunity to enhance sentiment analysis through advanced data-driven approaches.In the tech industry, companies such as Google and Apple rely on understanding customer sentiment to improve their products and services. Given the sheer volume of user feedback shared online, manual analysis is neither practical nor free from bias. Machine Learning offers a scalable and efficient solution by automating sentiment analysis, allowing businesses to derive meaningful insights from extensive datasets.This project focuses on developing and deploying Machine Learning models to analyze sentiment in customer feedback on Google and Apple products. By utilizing social media data, we aim to generate actionable insights for investors, traders, and businesses, helping them better understand public perception and make data-driven decisions.
## Data Understanding
The dataset, sourced from CrowdFlower via data.world, contains over 9,000 tweets labeled by human raters as positive, negative, or neutral. These tweets, posted during the South by Southwest (SXSW) conference, primarily discuss Google and Apple products, with raters determining both the sentiment and the specific brand or product mentioned. Compiled in 2013 by Kent Cavender-Bares, the dataset captures consumer opinions during a major tech event where product comparisons are common, potentially reducing bias. Given that tweets are concise and often emotionally charged, they serve as strong indicators of public sentiment. For this analysis, the target variable has been simplified into two categories: tweets with positive sentiment and those without (including neutral, negative, and unclear sentiments). The emphasis is on identifying positive sentiment, as it directly influences consumer behavior and investment decisions.
 ## Data Description
 The dataset contains three columns which include;
 tweet_text which contains the cintent of the tweets.
 Target whuch relates to the specific brand,sentiments related to.
 Emotion which outlined the expressions relating to the tweets.
 ## Data Preparation
 This included data cleaning,preprocessing and modelling.