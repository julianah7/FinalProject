# JMU Keywords K-Means Clustering Problem 

The problem the machiene learning task was expected to solve was to discover what keywords were associated with the query of JMU in Twitter Social Media through Rapid Miners K-Means Clustering. Due to the recent announcement of Coach Mike Houston leaving JMUs Football team I was curious to see if many clusters would contain keywords that had to do with his departure. Through the keywords analzyed in the clusters I would be able to discover if more positivity or negativity surrounded this decision. My research problem will be a classification problem. I plan to utilize k-means clustering in order to solve this clustering problem. 

## How Data was collected

The data was collected through RapidMiner process. The [twitter](https://twitter.com) access token feature was utilized in order to collect real-time tweets that were relevant to my selected topic. By establishing a new connection and querying the word "JMU", over 150 keywords collected that were assigned to six different clusters. By converting the collected tweets into RapidMiner and setting the attribute to only capture special attributes, the ability to filter out unwanted ones was made possible. 
<img src="https://github.com/julianah7/FinalProject/blob/master/twittertoken.PNG" width="700">


## Process in RapidMiner
[Process](https://github.com/julianah7/FinalProject/blob/master/final.xml) 

<img src="https://github.com/julianah7/FinalProject/blob/master/Process%20of%20Twitter.png" width="500">
By Enabling Special attributes, data is saved in a column that shows the top keywords of each cluster. Through this   process I am able to use K-Means Clustering to modify the amount of clusters that I want to visualize along with associated keywords in each cluster that could be paralell to one another.

<img src="https://github.com/julianah7/FinalProject/blob/master/ProcessofDocument.png" width="700">
The tweets after being converting the collected into rapid miner and setting the attribute to only capture the text of the converted tweet document, this will give the ability to filter out the unwanted attributes that will not be significant or necessary in my research. I coverted the text to vectors, convert all letters to lower case, and eliminate letters that are too long, and filter stop words in order to produce the most concise visually appealing classification as possible.

<img src="https://github.com/julianah7/FinalProject/blob/master/stepbysteprocess.png" width="700">
Step by step process in Github that allowed me to enable special attributes in order to visualize keywords in their respective clusters. The aggregate feature allows you to preform this task on your attributes by identifying the top key words in each cluster. Then to transpose the selected data and select the role of ID in order to assign each to a specific cluster.The twitter data along with the cluster is then saved to the selected excel files along with the keywords and clusters. 

                                                                                                

[Link to Tableau Public Visualization](https://public.tableau.com/profile/juliana6328#!/vizhome/FinalProjectWorkbook_3/Dashboard1)
