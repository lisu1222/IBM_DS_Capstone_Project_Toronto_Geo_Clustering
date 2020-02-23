# Capstone Project
## Toronto Geo Clustering 
This project is an IBM Data Science capstone project that includes web scraping, data preprocessing and clustering analysis.
### Data Source
- The postal codes table of Canada was scrapped from Wikipedia page. 
- Google API was applied to get latitude and longitude values for each neighbourhood in Toronto.
- Foursquare API was applied to explore venues in Toronto.
### Data Preprocessing and Cleaning
- Dropped raws without neighborhood information.
- Dealt with missing and duplicated values.
- Transformed column 'Neighbourhood' to usable formats
- Added latitude and longitude columns by using Google API to loop through each address
- Cleaned the json data extracted with Foursquare API and structured into dataframes
### Analyze and Visualize Neighborhoods
- Identified each neighborhood's nearby venues
- One-hot encoding to find out categories of venues in each neighborhood and scored frequency
- Found out the top 5 most common venues for each neighborhood 
### Cluster Neighborhoods
- Ran K-means to cluster neighborhoods into 5 clusters
- Created a map, set color scheme for clusters and added markers 

 
 	

