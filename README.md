Geospatial Clustering for Delivery Optimization using Python

This is a mini project where I tried out **geospatial clustering** using Python, mainly to group delivery locations based on their coordinates (latitude/longitude).  
Basically, I wanted to see how companies like Zomato or Amazon might decide zones for delivery based on real map data.


What’s Inside?

Calculating real-world distance between restaurant and delivery point using **geopy**
Plotting delivery points on **interactive maps** using **Plotly**
Applying **K-Means clustering** to divide India into delivery zones
Filtering out invalid GPS points (outliers)
Giving meaningful names to clusters like "Central Delivery Zone", etc.

Dataset Info

I used a dataset that has:
Restaurant location (`Restaurant_latitude`, `Restaurant_longitude`)
Delivery location (`Delivery_location_latitude`, `Delivery_location_longitude`)
More fields but not really used in clustering

Libraries Used

pandas,
numpy,
sklearn,
geopy,
plotly.
