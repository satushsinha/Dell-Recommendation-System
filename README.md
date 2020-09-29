**Dell's-Recommendation-System**
In this project I am trying to create a system which will give customer a very unique experience in selecting the best Laptop's for him and even for solving some simple technical problems related to Laptop's.

**PART-1 (Recommendation System)**

**Web Scraping**

I scraped details about the dell laptop's from the flipkart website using Beutifulsoap and selenium libraries,I collected the name,price,features,rating and review for each laptop
The dataset can be viewed in the products.csv file and the code to create the same is available in webscraping.py file

**Dataset-Visualisation**

I visualised the dataset using matplotlib library, Plotted differnt graphs for the price vs rating,Number of laptops in differnt price ranges and many more all the graphs can be seen in Dell_visualisation.ipynb

**Recommendation System**

The recommendation system is taking the name of a laptop and on the basis of cosine similarity of its features with other laptops it is recommending top 10 laptops which features are most similar to the feature of input.The code for the same can be found in Dell_Recommendation_system.py

**PART-2 (Solving Technical Problems)**

Currently working on a chatbot wich will take the problem with the laptop of a user and will guide him through the steps to correct it,As the dataset is very large for this problem currently I am trying to collect the data from different sites. 
