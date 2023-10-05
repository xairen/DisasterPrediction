# Machine Learning based Natural Disaster Prediction

# Abstract 
Natural disasters cause significant damage to property and pose a threat to human
lives. To mitigate the impact of these disasters, emergency management teams need to
have preventive strategies in place before these incidents occur. The capstone project
proposes a machine learning approach that integrates historical data of disasters and
weather-related metrics including precipitation, average temperature, extreme temperature (Max and Min), number of cooling and heating days specific to counties across
United States. In addition to this, exploratory data analysis was performed on FEMA
(Federal Emergency Management Agency) disaster and hazard mitigation records, NOAA
(National Oceanic and Atmospheric Administration) weather datasets, and U.S. Census data detailing population to provide data-driven insights on disaster trends, weather
patterns, mitigation projects, and population vulnerabilities across regions. The model
was specifically designed using the merged dataset from FEMA disaster summaries and
NOAA’s weather data. Four machine learning algorithms were used; Logistic Regression, Decision Trees, Gradient Boosting, and Random Forest. The performance of each
model is compared using accuracy measures to select the best approach. An interactive
map is designed with the results of the predictions, which can be utilized by hazard mitigation authorities to allocate resources, identify high-risk areas, and make informed
decisions regarding emergency response strategies. These insights aid policymakers to
design more robust disaster management frameworks aiming to significantly reduce
the impact of future natural calamities

# Datasets

1. NOAA Weather - Precipitation, Average Temperature, Heating Days, Cooling Days, Maximum Temperature, Minimum Temperature
2. FEMA Disaster
3. US Census (Population)

# Algorithms used

1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosting

# Feature Importance

Understanding the feature importance in the machine learning model provides information about which variables played a crucial role in forecasting. It aids in validating
the models logic and provides hints about how the model could be further enhanced.
The following factors have had a significant influence on predicting incident type for a given location,
1. Month : The most influential feature that shows the impact of seasonal variations on disasters. For instance, flooding typically occurs during rainy seasons
while fire occur during dry summer months.
2. CombinedFIPS : Provides geographical information such as proximity of water
bodies or specific terrains and how a given region might be more prone to a certain type of disaster. For example, Los Angeles is prone to Earthquakes because
of the seismic plates near it.
3. Precipitation : Increase in rainfall directly correlates to disasters like flood,
landslides or severe storms. Higher precipitation can lead to increasing risks to
other disasters as well.
4. Temperature (Average, Max, Min) : Extreme temperatures and average temperature are crucial in predicting certain types of disaster and provide a general
overview of the climate in a given region. Higher temperatures are related to
droughts and wildfires while lower temperatures can be related to snowstorms
and cold waves.
5. Heating and Cooling Days : Indicate colder and warmer climate which can
be associated with freeze/heat related disasters along with the number of days a
given region has cooler or hotter days.
6. Programs Declared : These features have a lower importance but might provide
subtle insights into preparedness or help in identifying areas that require more
resources or risk of impact from disasters.







