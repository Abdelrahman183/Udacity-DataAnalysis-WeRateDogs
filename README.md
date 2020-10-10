# Udacity-DataAnalysis-WeRateDogs
## Project Overview
The goal: wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.
### The Data
**Enhanced Twitter Archive:** The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. Of the 5000+ tweets, they were filtered for tweets with ratings only (there are 2356).  
**Additional Data via the Twitter API:** Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions, this additional data can be gathered by anyone from Twitter's API.  
**Image Predictions File:** Every image in the WeRateDogs Twitter archive was ran through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
### Tasks
##### Gathering, assessing and cleaning the data (Data wrangling).
##### Storing, analyzing, and visualizing the wrangled data.
### Reporting for the project
- Produced analysis and visualizations in the Jupyter Notebook *wrangle_act.ipynb* along with insights extracted from them.  
- Created a report called *wrangle_report.pdf* that briefly describes my wrangling efforts. This is was framed as an internal document.    
- Created a report called *act_report.pdf* that communicates the insights and displays the visualization(s) produced from the wrangled data. This was framed as an external document, like a blog post or magazine article, for example.
