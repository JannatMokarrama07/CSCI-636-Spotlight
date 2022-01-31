# CSCI-636-Spotlight
## Recommending Articles using Content-based Analysis
### *Introduction:* ###
Reading articles has many advantages as they have the latest information. Due to the increased number of articles on the web daily, it is difficult and time consuming to find out the articles of users' choice. In this scenario, a recommendation system can play vital role by making users' experience easier and saving their time. Recommendation system can analyze either readers’ past read articles or the topics-related contents or both to do recommend articles to users. The main goal of the recommendation systems is to improve the users' experience in the online environment. Primarily, there are three types of recommendation methods. They are content-based filtering, collaborative filtering, and hybrid filtering. The focus of content-based recommendation system is in analyzing the similarity among the attributes of items to extract most similar items to user's choice whereas the collaborative filtering gives emphasize in users’ past behaviors and attributes to suggest items. On the other hand, hybrid recommendation system tries to combine both concepts to improve the experience of recommendation.

### *Objective:* ###
The aim of this spotlight is to use the concept of content-based recommendation system to recommend top-most related articles to the users based on the similarities between searched text and the article titles. At first, after fetching the data, it is preprocessed by checking for empty texts, removing all the duplicates, etc. Then some text-level  preprocessing like tokenization, stop-word removal, etc are conducted to get the desired and processed text to calculate similarities. Finally, article recommendation is generated using two popular text similarity techniques Bag of Words (BoW) and TF-IDF to understand their relative performance in this scenario.

### *Dataset:* ###
The dataset used in this spotlight is collected from publication dataset of <i>dimensions.ai</i>

### *Spotlight Steps:* ###
Here I worked in three steps: <br>
* __Task 1__ : Setup <br>
* __Task 2__ : Data Loading, Exploration, and Preprocessing <br>
* __Task 3__ : 

### References ###
1. Ricci F, Rokach L, Bracha S, Kantor PB. Recommender Systems Handbook. Boston, USA: Springer.
2. Lops P, de Gemmis M, Semeraro G. Content-based recommender systems: State of the art and trends. Recommender Systems Handbook. 1st ed. Boston, USA: Springer, 2011, pp. 73-105.
3. https://www.alpha-quantum.com/blog/content-based-recommendation-engine/content-based-recommender-system-with-python/
4. https://towardsdatascience.com/recommending-news-articles-based-on-already-read-articles-627695221fe8
5. https://thecleverprogrammer.com/2020/10/11/what-is-a-recommendation-system-in-machine-learning/
6. https://github.com/rwalk/gsdmm
