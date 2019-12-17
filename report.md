**Capstone Project-Find the best location to open a restaurant in Melbourne**



**1. Introduction**

In this project, I will analyze where it is most appropriate if someone wants to open a Chinese restaurant in Melbourne

Melbourne has a population of almost 5 million, of which 650,000 are Chinese. In Australia, most of the population is concentrated in the CBD, and this is no exception in Melbourne. The profitability of a restaurant mainly requires a large flow of people, so through analysis, the location of the restaurant is preferably somewhere in the city center. There is also competition between the same types of restaurants. We can analyze the types of nearby restaurants to exclude some of the more competitive locations and choose the best location.

***

**2.Data Set**

Data obtained through foursquare API like follow:

![](/home/nastul/Documents/Coursera_Capstone/img/FireShot Capture 033 - learnPyDraw - Jupyter Notebook - localhost.png)

I separate restaurant locations from all businesses near Melbourne. The structure of the data is similar to that in the previous project, including the coordinates and categories of the business.

****

**3.Methodology**

In this project, I used k-means as a learning method. K-means is a clustering method. It mainly divides similar data together based on the similarity between the data. The initial idea is to find the main areas where the restaurants are concentrated, and the relationship between the distribution of different types of restaurants, and determine the traffic information of the CBD by clustering the restaurants.

**4.Results**

![](/home/nastul/Documents/Coursera_Capstone/img/FireShot Capture 046 - Coursera_Capstone_Pro2 - Jupyter Notebook - localhost.png)

Observation found that Chinese restaurants are mainly concentrated near Chinatown, and more centrally located. In contrast, there are not many restaurants near the north, but many near the river. The University of Melbourne in the north has a large student base as spending power, and there are many international student groups in Melbourne.

***

**5. Conclusion**

In general, the analysis of the above data found that the location near the north is more suitable for Chinese restaurants.