# **Juliana Holloway IA 480 Machiene Learning Final Project**
# :beers::beers::beers::beers:

## **JMU Keywords K-Means Clustering Problem** 

The problem the machiene learning task was expected to solve was to discover what keywords were associated with the query of JMU in Twitter Social Media through Rapid Miners K-Means Clustering. Due to the recent announcement of Coach Mike Houston leaving JMUs Football team I was curious to see if many clusters would contain keywords that had to do with his departure. Through the keywords analzyed in the clusters I would be able to discover if more positivity or negativity surrounded this decision. My research problem will be a classification problem. I plan to utilize k-means clustering in order to solve this clustering problem. 

## **How Data Was Collected**

The data was collected through RapidMiner process. The [twitter](https://twitter.com) access token feature was utilized in order to collect real-time tweets that were relevant to my selected topic. By establishing a new connection and querying the word "JMU", over 150 keywords collected that were assigned to six different clusters. By converting the collected tweets into RapidMiner and setting the attribute to only capture special attributes, the ability to filter out unwanted ones was made possible. 
<img src="https://github.com/julianah7/FinalProject/blob/master/twittertoken.PNG" width="700">


## **Process in RapidMiner**
[Process](https://github.com/julianah7/FinalProject/blob/master/final.xml)
- Data script of Process imported into GitHub

<img src="https://github.com/julianah7/FinalProject/blob/master/Process%20of%20Twitter.png" width="500">
By Enabling Special attributes, data is saved in a column that shows the top keywords of each cluster. Through this   process I am able to use K-Means Clustering to modify the amount of clusters that I want to visualize along with associated keywords in each cluster that could be paralell to one another. This process gives the ability to convert the collected tweets into rapid miner and set the attribute to only capture the text of the converted tweet document,to filter out the unwanted attributes that were not significant or necessary in the research.

<img src="https://github.com/julianah7/FinalProject/blob/master/ProcessofDocument.png" width="700">
The tweets after being converting the collected into rapid miner and setting the attribute to only capture the text of the converted tweet document, this will give the ability to filter out the unwanted attributes that will not be significant or necessary in my research. I coverted the text to vectors, convert all letters to lower case, and eliminate letters that are too long, and filter stop words in order to produce the most concise visually appealing classification as possible.

<img src="https://github.com/julianah7/FinalProject/blob/master/stepbysteprocess.png" width="700">
Step by step process in RapidMiner that allowed me to enable special attributes in order to visualize keywords in their respective clusters. The aggregate feature allows you to preform this task on your attributes by identifying the top key words in each cluster. Then to transpose the selected data and select the role of ID in order to assign each to a specific cluster.The twitter data along with the cluster is then saved to the selected excel files along with the keywords and clusters. 

## **Results of Clusters** 
<img src="https://github.com/julianah7/FinalProject/blob/master/amountofclusters.png" width="700">
Visualization result of the amount of clusters collected from the k-means clustering analysis. As you can see, Cluster_5 collected the most keywords out of all 6 clusters that were fomulated. 

## **Justification of Models and Parameters**                                                                                          
Keywords and their clusters were then exported to tableau in a CVS file, the words along with their clusters were created in a dashboard, by chaning the attribute to a decimal value to see the weight of the keywords to their cluster. Word Clouds were then formulated in order to visualize the significant words in each cluster. By duplicating the sheet and substituting the average TF-IDF of the 1st cluster with the others, I was be able to create a visualization for all the clusters. After a dashboard was created for each sheet, I uploaded this to a story in Tableau in order to visualize and compare each cluster popular key words against one another. Also, by enabling sheet on the story, gives the visualization of querying the popularity in words among clusters for viewers. The quality of the data will be true due to the fact that it is obtained directly through twitter and is people’s opinion rather than missing values or labels. The interactive link below allows readers to visualize and interact with the data directly among different clusters. 

## **Tableau Interactive Visualization**
[Link to Tableau Public Visualization](https://public.tableau.com/profile/juliana6328#!/vizhome/FinalProjectWorkbook_3/Dashboard1)
- This link allows users to interact with the data in real time, querying specific keywords to see how many clusters the words were relative to. In this link you can see from the left side legend that many of the words can be inferred to be associated with Football and the sudden annoucement.

## **Conclusion and Limitations**
Although this does give the opinion of many students in real time, and most of the 150 keywords found were associated with the announcement of Coach Houstons departure, the true keywords and ability to classify just based off these clusters is not enough. Because the keywords do not show who they are tweet to or about, having to researcha and inference played a big part in the justification of the findings. In order to improve this research and method the ability to perform some sort of social network analysis in a side by side comparison with the cluster analysis could potentially solidy some of the keywords and findings, along with visualizing who was tweeted the most and what the tweets were about in order to justify my findings. 

## *External Resources for more Info:* :pencil2:
1. [Info on Coach Houston Departure](https://www.witn.com/content/news/SOURCES--Kirkpatrick-new-offensive-coordinator-at-ECU-501984331.html) :football:
2. [Link to Social Network Tool That Could Improve / Further Findings](https://gephi.org/) :wrench:



