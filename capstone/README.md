## New York Aribnb analysis
Almost 5 million of travelers visit New York annually. New York has more than 40000 Airbnb for the travelers to choose.
How to choose an appropriate one based on location, price and the other factors?This analysis is of Airbnb' s marketing from
New York. The data is from Kaggle website:https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data . 
### Outline for data analysis: 
data wrangling, data visualization, statistical analysis and machine learning.
### Data wrangling:
1. Drop unnecessary and column with too many missing values, including ‘last_review’ ‘host_name’ columns.
2. Fill ‘NaN’ in the missing value area.
3. Remove the ‘price’ outliners.
4. Encode the data: factorize the ‘neighbourhood_group’ and ‘room_type’ to number format to finish the kendall correlation analysis.
### Data visualization:
1. Identify that top hosts who have most listings. 
2. Identify the room type distribution trend.
3. Summary the number of listings by neighbourhood_group.
4. Find out the relationship between 'neighbourhood group' and 'price'.
5. Visualize the Location vs room type.
6. Figure out the room type distribution trend of top ten neighbourhood listings.
7. visualzie the price map in New York city.
### Statistical analysis:
Employ bootstrap sampling method to analysis the price between different room types and find out the price between 
entire home/apt and private room has significant difference.
### Machine learning analysis: linear regression, decision tree and random forest.

