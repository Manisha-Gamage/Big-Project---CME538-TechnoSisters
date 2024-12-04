# Housing Affordability and Safety Analysis in Toronto and Vancouver

Toronto and Vancouver, two of the most vibrant cities in Canada, offer incredible cultural and economic opportunities. However, their high cost of living presents challenges for individuals and families, particularly those with low to average incomes. Finding a balance between housing affordability, safety, and access to amenities can be overwhelming. The process of researching property values, crime rates, and neighborhood features across multiple sources only adds to the complexity.

This project aims to simplify the decision-making process. It offers a data-driven platform that consolidates and analyzes key neighborhood information from both cities. By integrating data on housing prices, crime rates, income levels, and local amenities, it provides actionable insights. The goal is to bridge the gap between affordability and safety, helping users find neighborhoods that meet their needs without compromise.

Data for this project was gathered from several sources to ensure a comprehensive analysis:

* ```Housing Data```: Collected from [Zillow](https://www.zillow.com/) and [Rew](https://www.rew.ca/) websites to analyze property prices and house features.

* ```Crime Data```: Sourced from the [Toronto Police Service](https://data.torontopolice.on.ca/pages/open-data) and [Vancouver Police department](https://geodash.vpd.ca/opendata/) websites to assess neighborhood safety. 

* ```Income Data```: Retrieved from [Open Data Portal](https://open.toronto.ca/dataset/neighbourhood-profiles/) and [Census Canada](https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/details/page.cfm?Lang=E&SearchText=Vancouver&DGUIDlist=2021A00055915022&GENDERlist=1&STATISTIClist=1&HEADERlist=0) to understand income distribution per year across neighborhoods.

* ```Amenities Data```: Extracted from [Open Street Maps](https://download.geofabrik.de/north-america/canada.html) to evaluate access to schools, hospitals, parks, and more.

* ```Neighborhood Data```: Obtained from [Toronto](https://open.toronto.ca/dataset/neighbourhoods/) and [Vancouver](https://opendata.vancouver.ca/explore/dataset/local-area-boundary/export/?disjunctive.name) neighborhood datasets to define geographic boundaries and attributes.

We combined these datasets and conducted exploratory data analysis (EDA) to identify relationships between affordability, safety, income, and amenities. This analysis helps uncover trends, correlations, and insights across the data. Feature engineering was performed to create and select features for clustering neighborhoods by affordability. We also classified neighborhoods based on income and safety and predicted house prices.

**Overview of Folders:**
1. ```Data```: Contains the code to collect the data, the collected data, and the cleaned data used in the project.
2. ```Feature Engineering and EDA```: Includes the code to create new features, perform feature selection, and conduct exploratory data analysis of the features.
3. ```Income and crime class selection```: Contains the code and results for classifying neighborhoods based on income and crime data.  
4. ```Affodabilty_Safety_Price_prediction```: Contains the code for clustering neighborhoods by affordability, ranking neighborhoods, analyzing safety, and predicting house prices, along with the results.  

**Workflow:**

![image](https://github.com/user-attachments/assets/7cf590f4-f2ac-4171-b6d0-5d28f553174d)

**Data Cleaning-Filtering-Combining**

![image](https://github.com/user-attachments/assets/aef44eee-1de3-4af9-91a3-6a12e3e9df79)


**Link to Medium article:**

* Toronto vs. Vancouver: The Battle for Affordable and Safe Neighborhoods - (https://medium.com/@manisha.gamage/toronto-vs-vancouver-the-battle-for-affordable-and-safe-neighborhoods-66b8fd843bb6)
