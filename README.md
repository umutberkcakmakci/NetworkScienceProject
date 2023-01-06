# NetworkScienceProject

This is the main project page for University of Padova 2022/23 Network Science course! 

In the code; we described how to get data from twitter, how to process it and how to visualize in Python. 

Also you can visualize your processed data in Gephi, an open-source platform for visualizing and manipulating large graphs, which you can find more visualization options in there! 

https://github.com/gephi/gephi

Libraries we used:
- matplotlib for visualization, 
- time and datetime for the search query we applied, 
- networkx to enable network science analysis of the data, 
- Pandas to display the dataframe easily.

To get the data from twitter, you need a twitter developer account. 

https://developer.twitter.com/en/support/twitter-api/developer-account

With that account, you can have access to the last 7 days of tweets using this endpoint -> https://api.twitter.com/2/tweets/search/recent.

To access more tweets and go back more than 7 days, you need Academic Research account. If you have, you can use the endpoint below to get the data -> https://api.twitter.com/2/tweets/search/all.

In the code, the endpoint is set to academic research -> https://api.twitter.com/2/tweets/search/all.
