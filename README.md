# JMU Keywords K-Means Clustering Problem 

The problem the machiene learning task was expected to solve was to discover what keywords were associated with the query of JMU in Twitter Social Media through Rapid Miners K-Means Clustering. Due to the recent announcement of Coach Mike Houston leaving JMUs Football team I was curious to see if many clusters would contain keywords that had to do with his departure. Through the keywords analzyed in the clusters I would be able to discover if more positivity or negativity surrounded this decision. My research problem will be a classification problem. I plan to utilize k-means clustering in order to solve this clustering problem. 

## How Data was collected

The data was collected through RapidMiner process. The [twitter](https://twitter.com) access token feature was utilized in order to collect real-time tweets that were relevant to my selected topic. By establishing a new connection and querying the word "JMU", over 150 keywords collected that were assigned to six different clusters. By converting the collected tweets into RapidMiner and setting the attribute to only capture special attributes, the ability to filter out unwanted ones was made possible. 
<img src="https://github.com/julianah7/FinalProject/blob/master/twittertoken.PNG" width="700">


## Process in RapidMiner
[Process](https://github.com/julianah7/FinalProject/blob/master/final.xml) 

<img src="https://github.com/julianah7/FinalProject/blob/master/Process%20of%20Twitter.png" width="500">
### By Enabling Special attributes, data is saved in a column that shows the top keywords of each cluster. Through this   process I am able to use K-Means Clustering to modify the amount of clusters that I want to visualize along with associated keywords in each cluster that could be paralell to one another.

<img src="https://github.com/julianah7/FinalProject/blob/master/ProcessofDocument.png" width="700">

                                                                                                

[Link to Tableau Public Visualization](https://public.tableau.com/profile/juliana6328#!/vizhome/FinalProjectWorkbook_3/Dashboard1)
