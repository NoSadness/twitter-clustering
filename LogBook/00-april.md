LogBook
-------
- [April](https://github.com/gtrdp/masters-thesis-guntur/blob/master/LogBook/00-august.md)

**To-Do**

- Learn DBI
- TF IDF
- Learn how to visualize the data from Google Trends

April #1
---------
- **Sun Apr  2 21:41:15 WIB 2017**
	- Preparing the git repository.
	- Mining twitter using python:
		- https://marcobonzanini.com/2015/03/02/mining-twitter-data-with-python-part-1/
	- Limits in Twitter APIs:
		- https://dev.twitter.com/overview/terms/agreement-and-policy
		- https://dev.twitter.com/rest/public/rate-limiting
	- Google trends might help: https://trends.google.nl/trends/
	- Library for twitter mining: http://tweepy.readthedocs.io/en/v3.5.0/
	- Resources for learning twitter mining:
		- https://github.com/bonzanini/Book-SocialMediaMiningPython
	- Got the minimal working example (not yet pre-processed).

- **Mon Apr  3 11:59:22 WIB 2017**
	- Learn about twitter clustering.
	- Might be interesting: https://github.com/JamesPHoughton/twitter-cluster
	- Downloaded some papers.
	- Nice tools to create geobox
		- http://boundingbox.klokantech.com
		- geobox whole world: ```GEOBOX_WORLD = [-180,-90,180,90]```
		- Jogja and surroundings: ```JOGJA = [109.4763,-8.4557,111.3928,-7.2811]```
	- The streaming API doesn't allow to filter by location AND keyword simultaneously (http://stackoverflow.com/questions/22889122/how-to-add-a-location-filter-to-tweepy-module).
		- https://dev.twitter.com/streaming/overview/request-parameters#locations
	
		> Bounding boxes do not act as filters for other filter parameters. For example track=twitter&locations=-122.75,36.8,-121.75,37.8 would match any tweets containing the term Twitter (even non-geo tweets) OR coming from the San Francisco area.
	
- **Tue Apr  4 09:42:00 WIB 2017**
	- 	Preprocessing: remove RT, via, URL, unicode characters (convert to string if possible), remove hastags (or separate hashtags and regular term)?.
	-  From python to web based graph: https://github.com/wrobstory/vincent
	-  Discussion about text (document) clustering:
		-  https://www.researchgate.net/post/What_is_the_best_algorithm_for_Text_Clustering
		-  http://datascience.stackexchange.com/questions/979/algorithms-for-text-clustering
		-  Latent Dirichlet Allocation (LDA)
		-  k-Means
		-  Latent Semantic Analysis
		-  Ontology based clustering
	- DBI implementation in Python (and also other index in text clustering):
		- http://www.turingfinance.com/clustering-countries-real-gdp-growth-part2/
	- Visualization options:
		- No text are presented, possibly only the keywords. When the pointer hovers on a particular point, the full text (tweet) appears.
	- Interesting bookmarks:
		- http://scikit-learn.org/stable/auto_examples/text/document_clustering.html
		- http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/
		- https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/
		- http://brandonrose.org/clustering
		- http://www.cs.duke.edu/courses/spring14/compsci290/assignments/lab02.html
		- http://nlpforhackers.io/recipe-text-clustering/
		- http://datascience.stackexchange.com/questions/979/algorithms-for-text-clustering
		- http://harrywang.github.io/document_clustering/
		- Several indices in clustering: http://www.turingfinance.com/clustering-countries-real-gdp-growth-part2/