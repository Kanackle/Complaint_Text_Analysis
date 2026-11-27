# Complaint_Text_Analysis
A Regex text analysis of a complaints database

# Getting Started
Download the python and excel sheet and upload onto Google Drive in the folder structure provided within the file.
If you wish to change the file name or folder structure, make sure to change appropriately within the code 

#Summary
I analyzed 200 complaint narratives using text cleaning, word-frequency analysis, TF-IDF and exploratory LDA topic modeling. 
After refining the vocabulary, I used a three-topic model to summarize company-response distributions. 
Topic IDs are 0, 1 and 2; the semantic labels still require human review.

# Conclusion/Analysis
The most common recorded response was “Closed with explanation” (125/200, 62.5%), followed by “Closed with non-monetary relief” (64/200, 32.0%). The remaining 11 complaints (5.5%) were labelled “Closed.” Topics 1 and 2 had broadly similar response distributions. Topic 0 contained only 10 complaints, so its percentages should be interpreted cautiously.

Consumer-dispute values were available for 74 complaints: 18 True and 56 False. The other 126 were missing. Recording coverage differed by topic: 60.0% for Topic 0, 33.0% for Topic 1 and 38.4% for Topic 2. These coverage percentages are not dispute rates. Missing values cannot be treated as “not disputed,” and comparisons among recorded cases may be biased.

The model is exploratory and does not establish the optimal number of topics. The findings describe this analyzed subset; they do not demonstrate causation, customer satisfaction, or complaint resolution. A useful next step is to verify topic labels against additional narratives and document the dataset source, sampling procedure and a reproducible run workflow.

