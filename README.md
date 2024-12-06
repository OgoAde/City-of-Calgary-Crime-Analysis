# Crime Analysis in the City of Calgary (2012-2017)
## Overview
This project involved analyzing crime trends in the City of Calgary between 2012 and 2017 using data sourced from the City of Calgary Open Data Portal. The analysis aimed to uncover key insights about crime distribution, trends, and associated factors across the city, providing actionable intelligence for stakeholders.
The workflow included:

**Data Sources**: A combination of CSV files and APIs.

**Tools**: Power Query for data cleaning and transformation, Power BI for visualization, and Snowflake schema for data modeling.<br><br>

## Goals
1. Identify crime-prone areas and their contributing factors.
2. Understand seasonal and yearly trends in crime patterns.
3. Provide an interactive dashboard for stakeholders to analyze specific crime categories, types, and geographic segments.<br><br>


## Data Preparation

 **Data Cleaning and Transformation**
 
**Tools:** Power Query
- Handled missing values, inconsistencies in date formats, and standardized column names for seamless integration.<br><br>

## Data Modeling
**Schema**: Snowflake schema with key relationships:
- Fact table for crime data.<br><br>
- Dimension tables for communities, residential types, wards, and sectors.<br><br>
- Connected data using unique keys (e.g., community codes, ward numbers).<br><br>
- Mapped community names, residential types, and wards for proper relational modeling <br><br>

## Dashboard Features
**VISUALS**<br><br>
1. **Clustered Bar Chart:**
- Shows the Top 10 Communities by Total Crime.
- Key Insight: The top 3 crime-prone areas over the 5-year period were:
**Beltline** with 48,000 crimes,
**Downtown Commercial Core** with 39,000 crimes and 
**Forest Lawn** with 16,000 crimes.<br><br>

2. **Pie Chart:**
- Represents Crime Distribution by Residential Type.
- Insight: Residential areas accounted for 91.6% of total crimes, indicating a significant concentration in these areas.<br><br>

3. **Line Chart with Drill-Down:**
- **Crime Trends Over Time (2012–2017)**
- Enabled drill-down into months for detailed analysis.


**Insights**:
- Spike in 2015: A significant increase of over 20,000 crimes compared to previous years, marking a notable deviation in the trend.
- Post-2015 Consistent Increase: Following the spike in 2015, crime rates continued to rise yearly, highlighting a concerning pattern of growth.<br><br>

4. **Card Visuals:**
- The dashboard includes interactive card visuals that display key metrics such as the total crime count, total population, crime rate per 1,000 residents, and the average number of crimes per day. These visuals are dynamic and update in response to slicer selections, providing real-time insights based on user input.<br><br>

5. **Buttons for Navigation:**

- The report features navigation buttons to enhance usability, allowing users to switch seamlessly between pages and sections.<br><br>

6. **Slicers for Dynamic Insights:**
- These slicers enable stakeholders to drill deeper into the data, filtering for specific areas, timeframes, or crime categories.
- The slicers included are; Crime Category, Crime Type, Ward Number, Sector<br><br>
![Dashboard Screenshot](https://github.com/OgoAde/Crime-Analysis-in-the-City-of-Calgary-2012-2017-/blob/main/Screenshot%201.png)


## Key Findings
**Crime Concentration:**
Beltline, Downtown Commercial Core, and Forest Lawn accounted for a significant share of total crimes.<br><br>

**Location Type:** Residential areas were the most common crime location (91.6% of total crimes).<br><br>

**Seasonal Trends:** Crime rates increased during summer months (June to September).
Crime levels dropped significantly during winter months (December to February).<br><br>

**Yearly Trends:**
In 2015, total crimes spiked by over 20,000—a notable anomaly compared to previous years.
Following 2015, crime rates saw a consistent upward trend, emphasizing the need for long-term mitigation strategies.<br><br>
![Dashboard Screenshot](https://github.com/OgoAde/Crime-Analysis-in-the-City-of-Calgary-2012-2017-/blob/main/Screenshot%202.png)

## Recommendations
**1. Enhanced Patrols in Crime-Prone Areas:**
- Increase law enforcement presence in Beltline, Downtown Commercial Core, and Forest Lawn to deter criminal activity.<br><br>

**2. Seasonal Crime Prevention:**
- Launch summer-specific crime prevention campaigns to address the spike in criminal activity during warm months.<br><br>

**3. Community Engagement Programs:**
- Foster community-police partnerships in residential areas to address the root causes of crime.<br><br>
  
**4. Analysis of 2015 Spike:**
- Conduct further investigation into socioeconomic, policy, or demographic changes in 2015 to understand the sharp increase in crimes and address similar triggers in the future.<br><br>

**5. Data-Driven Allocation of Resources:**
- Use predictive analytics to allocate law enforcement resources effectively and proactively address high-risk areas.<br><br>

## Methodology
**Data Cleaning:**
- Performed in Power Query.
- Handled null values, transformed data types, and removed duplicates.<br><br>

**Data Modeling:**
- Built a snowflake schema to establish relationships between facts and dimensions.<br><br>

**Visualization:**
- Created a Power BI dashboard for insights and storytelling.<br><br>

## Potential Applications
1. **Policy Making:** Helps policymakers allocate resources to high-crime areas.<br><br>
2. **Trend Prediction:** Allows law enforcement to anticipate seasonal and yearly crime patterns.<br><br>
3. **Community Awareness:** Provides communities with data to advocate for safety improvements.<br><br>

## Screenshots
![Dashboard Screenshot](https://github.com/OgoAde/Crime-Analysis-in-the-City-of-Calgary-2012-2017-/blob/main/Screenshot%203.png)
![Dashboard Screenshot](https://github.com/OgoAde/Crime-Analysis-in-the-City-of-Calgary-2012-2017-/blob/main/Screenshot%204.png)
![Dashboard Screenshot](https://github.com/OgoAde/Crime-Analysis-in-the-City-of-Calgary-2012-2017-/blob/main/Screenshot%205.png)




## Future Enhancements
1. **Real-Time Integration:** Incorporate live data feeds for up-to-date crime analysis.<br><br>
2. **Predictive Modeling:** Leverage machine learning to forecast crime trends.<br><br>
3. **Anomaly Detection:** Develop models to detect and explain crime spikes like the one in 2015.<br><br>

## Link to Dashboard
<iframe title="City of Calgary Report" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMzY5M2Y4ZTYtZTQwNS00NjkxLWJlYzQtMzA1ZTQ0OTE2MmEyIiwidCI6ImY1MmYyMTgzLTlmNjctNGFkMi1iNjU2LTZmNzU0ZmUxOTZjYiIsImMiOjZ9" frameborder="0" allowFullScreen="true"></iframe>

