# Big-Mobility-Data-Analytics-for-Public-Health-Interview-Task

Please find the notebook here [Notebook](https://github.com/anuragMaravi/Big-Mobility-Data-Analytics-for-Public-Health-Interview-Task/blob/main/Big%20Mobility%20Data%20Analytics%20for%20Public%20Health%20Data%20Code%20Interview%20Task.ipynb)

## Data Source
### [NYC Taxi Trips](https://github.com/uber-web/kepler.gl-data/blob/master/nyctrips/data.csv)
This data set, downloaded from [NYC Taxi and Limousine Commission (TLC) website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page), includes yellow and green taxi trip records capturing pick-up and drop-off dates/times, pick-up and drop-off locations (latitude, longitude), trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

### [NYC restaurant locations](https://drive.google.com/file/d/11oMqNz_0aksP_vFXMQhA6a5rrWPshrew/view?usp=share_link)
- The New York City Department of Health and Mental Hygiene (DOHMH) conducts unannounced restaurant inspections on an annual basis in order to check for compliance with policies on food handling. Data on these restaurant inspection results are publicly available at [NYC Open Data](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j) and are updated daily. The specific data set for download above was accessed on 8/28/17 and contains records from 2014 - 2017. This older data was chosen in order to be more aligned with the taxi data, collected in 2015. This is important, since there is high turnover in restaurants over time (i.e., many go out of business).  
- The data set contains information on restaurant name and location, type of food (CUISINE DESCRIPTION), inspection date, and details on violation codes, total scores, and associated grades. The data is longitudinal in nature, with multiple rows per restaurant representing inspections over time. A full data dictionary is available [here](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j).
- For the following questions, **we will focus on analyzing the locations of restaurants** (specified by the combination of their building, street, and zipcode features) **and not their inspection results**.

## Notebook Preview
### Linked Data
![alt text](https://github.com/anuragMaravi/Big-Mobility-Data-Analytics-for-Public-Health-Interview-Task/blob/main/sample_images/linked_data_2.png)
### Taxi Drop Location
![alt text](https://github.com/anuragMaravi/Big-Mobility-Data-Analytics-for-Public-Health-Interview-Task/blob/main/sample_images/taxi_drop_map.png)
### Restaurants Location
![alt text](https://github.com/anuragMaravi/Big-Mobility-Data-Analytics-for-Public-Health-Interview-Task/blob/main/sample_images/restaurant_map.png)