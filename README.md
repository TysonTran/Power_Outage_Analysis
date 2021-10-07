# Major Power Outage Analysis
This is a exploratory data analysis of a Major Power Outage in the US dataset from Purdue's Laboratory for Advancing Sustainable Critical Infrastructure with a ML model. I was exploring the data to gain insight into who are the people most affected by major power outages and created a ML model to predict if an individual would be affected by a major power outage or not.

## Findings

### Where do Major Power Outages Tend to Occur
- California has the most Major Power outages with Texas and Michigan following
- RFC and WECC almost have double the number of major power outages as compared to any other region

### Where do Major Power Outages take the longest to get back up and running?
- ECAR region tend to have longer major outages compared to any of the other regions

### When do Major Power Outages Tend to Occur?
- Major power outages tend to occur in the summer months of June, July, and August
- Major power outages have incresingly become more common compared to the early 2000s

### ML Model
- Looking to predict if a major power outage will occur
- Features Used: Month, Postal Code, Climate Catgory, Anomaly Level, Total_Price
- Used a decision tree classifier
- Improved Model by .037 using Grid Search
- Received a accuracy score of .81 
