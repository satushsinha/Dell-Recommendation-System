**Dell's Recommendation System**
 
In this endeavor, a system is formulated by me which will give the client a very unique experience in preferring the best Laptop for him and rightful for figuring out some simple technical problems associated with Laptops.


**PART-1 (Recommendation System)**

**Web Scraping**

I scraped details about the Dell laptop's from the Flipkart website using Beutifulsoap and selenium libraries, I amassed the name, price, features, rating, and review for each laptop. The dataset can be viewed in the products.csv file, and the code to establish the same is available in the webscraping.py file.

**Dataset-Visualisation**

I made up the dataset using the matplotlib library, Plotted different graphs for the price vs rating, the number of laptops in different price ranges, and many more. All the charts can be seen in Dell_visualisation.ipynb

**Recommendation System**
 
The recommendation system is accepting the name of a laptop and on the basis of cosine similarity of its features with other laptops, it is conferring the top 10 laptops which features are most synonymous with the feature of input. The code for the same can be found in Dell_Recommendation_system.py


**PART-2 (Solving Technical Problems)**
 
Presently working on a chatbot which will snatch the problem with the laptop of a user and will tutor him through the steps to fix it, As the dataset is relatively large for this problem currently I am making an exertion to gather the data from different sites.   
