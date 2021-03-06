# Dtorres-political-facebook-ads-capstone
Analysis of political ads on Facebook.
Douglas Torres Capstone proposal

**Executive Summary**

I will be looking into data from political ads in Facebook to determine what makes a political ad successful on the platform. I gathered public data from ProPublica compiled from thousands of ProPublica users from around the world, and data from Data is Plural that takes a look at posts by hyperpartisan Facebook pages.

**Motivation**

Social media has been found to influence the discourse on political issues over the last decade. My aim with this capstone project is to shine some light on which organizations are trying to influence public sentiment the most through Facebook and how reliable the information tends to be. 

**Data Question**

What makes a successful political ad on Facebook?

**Data Sources**

Article on how political ads online have affected political discourse 
https://www.theguardian.com/technology/2018/mar/19/facebook-political-ads-social-media-history-online-democracy

Facebook political ads database: https://www.propublica.org/datastore/dataset/political-advertisements-from-facebook

Data is Plural source: https://tinyletter.com/data-is-plural/letters/data-is-plural-2016-11-16-edition

**Approach**

By looking at the targetedness, campaigners, segmentations, and the entities mentioned in the ads I will be able to draw insights from this data to find out the ways organizations on Facebook effectively target Facebook users. 

**Obstacles observed**

Data cleaning will have to address converting the data to appropriate datetime formats and such for proper analysis. The created_at and updated_at values were not converted into proper datetime values and the ad impressions still appears as numeric continous data as supposed to categorical for example.

Another challange I encountered throughout the data set up was the json files stored in the entities and targets observations. A lot of data stored inside these json files gave more meaning to the data so I had to extract this by turning the files into dictionary values and matching them to their ad ids. This resulted in more than 1 million observations since each target and entities per ad were accounted for.

![For loop created to extract data from the json format in the raw data.](Screenshots/Screen%20Shot%202019-12-27%20at%206.52.10%20PM.png)
