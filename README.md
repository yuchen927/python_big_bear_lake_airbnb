<!-- ABOUT THE PROJECT -->
## About The Project

<img src="https://www.bigbear.com/imager/s3_us-west-1_amazonaws_com/big-bear/images/Scenic-Snow/89xVzXp1_d7439eaa25498c77bfbbdcd092d7d67c.jpeg" width="700">


### *Analyze Big Bear Lake's airbnb data:*

* What are the most popular room types served? 
* What are the average price per night?
* What the relationship between price and location?
* Are the most-listing host company/agents or individual?
* What did customers comment on the review?




<!-- GETTING STARTED -->

## Installation

  ```py
  pip install matplotlib
  pip install seaborn 
  pip install wordcloud 
  pip install geopandas
  pip install plotly-express
  ```
  
  
### **Data Context**

This dataset contains 1,500 Airbnb listings across Big Bear Lake. Meanwhile, the geographical location of houses, photos, and booking available dates are also provided for further analysis.

### **Data Content**

The csv file contains 767 fields. The description of main field is as below:

- address: Address of Airbnb.
- pricing/rate/amount: Price of Airbnb  
- pricing/rate/currency: Currency of Airbnb listing
- primaryHost/totalListingsCount: Host's total listings
- stars: Rating from guests
- url: Airbnb list link
- primaryHost/firstName: Host's first name / company name 
- primaryHost/id: Host's ID
- roomType: Listing's house/room type
- location/lat: Latitude of Airbnb
- location/lng: Longtitude of Airbnb


<!-- ACKNOWLEDGMENTS -->

## Acknowledgments
The data was scraped from Airbnb.com. All data in the file is publicly available to everyone already. Please be noted that data is originally owned by Airbnb.com.

* [Airbnb Analysis, Visualization and Prediction](https://www.kaggle.com/code/chirag9073/airbnb-analysis-visualization-and-prediction)
* [Python Exploratory Data Analysis (EDA) on NYC Airbnb](https://medium.com/analytics-vidhya/python-exploratory-data-analysis-eda-on-nyc-airbnb-cbeabd622e30)
* [How to Get and Analyze Data for Your Airbnb Market in Python](https://levelup.gitconnected.com/how-to-get-and-analyze-data-for-your-airbnb-market-in-python-37ffeb0c2d16?gi=5c3400dc7593)
* [Airbnb Scraper](https://apify.com/dtrungtin/airbnb-scraper/input-schema)


