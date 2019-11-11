# **Project :** ***Write A Data Science Blog Post***


## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Executive Summary
5. Licensing, Authors, and Acknowledgements


### 1. Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. 
The code should run with no issues using Python versions 3.*.


### 2. Project Motivation
This is an Udacity Data Scientist Nanodegree Program's project and I'm interested to explore more on AirBNB related data.

Therefore, this simple analysis is aiming to clear below interesting points pop-up about both Boston and Seattle AirBNB data we have :
1. *Any seasonality impact to AirBNB monthly total earnings from both Seattle and Boston cities ?*
2. *What type of properties are more costly and is it relatively favorable ?*
3. *Are we able to classify positive or negative comments based on customers reviews ? And, what is the distribution ?*


### 3. File Descriptions
- The data source for Seattle and Boston AirBNB data are available @ http://insideairbnb.com/get-the-data.html 
- 3 different data files are available from each city such as
  - *Calendar : Daily price and availability data per listing ID.*
  - *Listings : Home-level information about AirBNB listings and inclusive their reviews scoring as well.*
  - *Reviews : Review-level information such as "comments".*


### 4. Executive Summary
#### *Question 1. Any seasonality impact to AirBNB monthly total earnings from both Seattle and Boston cities ?*
 - *Business Understanding :*
    - Geographically, both cities are located far apart from each others; Seattle @West of United States & Boston @East of United States.
    - Therefore, it causes their best travelling period slightly differ from each others i.e. Peak season is between Jun-Aug for Seattle vs. May-Oct for Boston as well as the pricing.
 - *Methodology :*
    - Generate average AirBNB rental fee by month in both cities for comparison.
 - *Findings :*
    - Generally, average AirBNB rental fee in Boston is 44% (USD198 vs. USD138) higher than Seattle city.
    - It seems like the AirBNB pricing is seasonal fluctuations and interestingly, the pricing for both Low and Shoulder seasons are similar in Boston city (i.e. 10% more expensive for High season vs. Shoulder/Low seasons). Whereas in Seattle, it is 8% and 15% cheaper for Shoulder and Low season respectively as compare to High season.

#### *Question 2. What type of properties are more costly and is it relatively favorable ?*
 - *Business Understanding :*
   - To understand is different type of property and its pricing do playing an important role in determine customers favouritism.
 - *Methodology :*
   - Generate the average pricing for each property type and its renting transactions.
 - *Findings :*
   - Out of 19 different property types in both cities, surprisingly "Guesthouse" appears as most costly (i.e. USD289) property type as compare to the rest and follow by "Boat" and "Villa" with price of USD274 and USD190 respectively.
   - But costly property types doesn't seem to be favorable by customers. In fact, substantial beds capacity by property type is the key factor to a guest favouritism during vacation i.e. "Apartment" with max capacity of 16 and "House" with 15.
 
#### *Question 3. Are we able to classify positive or negative comments based on customers reviews ? And, what is the distribution ?*
 - *Business Understanding :*
   - Analyzing and understand what is the feedback given by customers.
 - *Methodology :*
   - Use Natural Language Toolkit to classify "positive" or "negative" comments from reviews sentence.
 - *Findings :*
   - Both Boston and Seattle are getting excellent feedback from AirBNB guests and Seattle city is slightly outstanding with ~6p.p.

1. *"WriteADataScienceBlogPost.ipynb"* is capturing the program scripting details especially on data understanding, exploration, cleaning and modeling (if relevant) part.
2. *Blog post [YOU Spent but SOMEONE “Earn”…](https://medium.com/@eyanney.ang/you-spent-but-someone-earn-48fe84fd087d)* is mainly summarizing the business objective and its executive summary.


### 5. Licensing, Authors, Acknowledgements
1. Acknowledgements to 
   - Udacity Data Scientist Nano Degree courses for some of code ideas
   - Kaggle/AirBnb for making the data available for analysis and you can find the Licensing for the data and other descriptive information at the Kaggle link available [here](http://insideairbnb.com/get-the-data.html).
2. Otherwise, feel free to use the code here as you would like !
