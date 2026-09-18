

# Agriculture-Environment-Dashboard

### Dashboard Link : https://app.fabric.microsoft.com/groups/47b55c6e-6346-4ff5-9b90-5e9f79aeba5b/reports/7e6f3757-bcb0-45f6-b96b-af6de176e645/1e400f5bd0a12a0437d4?experience=fabric-developer

## Problem Statement

This dashboard helps analyze agricultural and environmental data to identify key patterns such as rainfall distribution, crop yield factors, and environmental conditions. It enables stakeholders to monitor climate-related variables, assess agricultural productivity, and make data-driven decisions for sustainable farming practices.

By integrating cloud-based data pipelines, the dashboard ensures scalability and real-time insights. It highlights areas where rainfall variability or environmental conditions impact crop growth, allowing for proactive measures.

### Steps followed
 - Step 1 : Uploaded dataset to AWS Cloud Platform by creating an S3 bucket.

 - Step 2 : Configured IAM user access in AWS to securely connect external tools.

 - Step 3 : Connected AWS S3 data to Snowflake using the IAM credentials.

 - Step 4 : Performed basic data cleaning in Snowflake (handling nulls, removing duplicates, formatting columns).

 - Step 5 : Connected the cleaned dataset from Snowflake into Power BI Desktop.

 - Step 6 : Applied Power Query transformations for additional shaping of data.

 - Step 7 : Created DAX measures to calculate key metrics such as rainfall averages, crop yield percentages, and environmental indices.

 - Step 8 : Added visual filters (Slicers) for dimensions like Region, Crop Type, Season, and Soil Condition.

 - Step 9 : Designed card visuals to represent KPIs such as total rainfall, average crop yield, and environmental score.

 - Step 10 : Built bar charts and line charts to show rainfall trends over time and crop yield comparisons across regions.

 - Step 11 : Used map visuals to represent geographical distribution of rainfall and crop productivity.

 - Step 12 : Inserted text boxes for project title and organization tagline.

 - Step 13 : Added company logo and styled the dashboard with a professional theme.

 - Step 14 : Published the report to Power BI Service for sharing and collaboration.

### Snapshot of Dashboard (Power BI Service)
 
 #### Rainfall Insights
 ![Snap_1]<img width="960" height="478" alt="Image" src="https://github.com/user-attachments/assets/a4696bb9-82b0-430a-ac3c-1ac532bd6b9c" />

#### Temperature Analysis
![Snap_2]<img width="960" height="484" alt="Image" src="https://github.com/user-attachments/assets/42f2d16b-a448-477c-b882-07f783d9b8be" />

#### Humidity Insights
![Snap_3]<img width="960" height="480" alt="Image" src="https://github.com/user-attachments/assets/728f469d-89de-42b0-8236-547b57536a6e" />

#### Other Insights
![Snap_4]<img width="960" height="479" alt="Image" src="https://github.com/user-attachments/assets/54ae6df8-8325-40b5-b49a-d17c9e7ebae1" />

# Insights
A single-page report was created in Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard:

### [1] Rainfall Analysis
Average rainfall across regions = X mm

Seasonal variation shows peak rainfall during Monsoon months.

Certain regions experience below-average rainfall, requiring irrigation support.

### [2] Crop Yield Insights
Highest yield observed in Region A with Y tons/hectare.

Lowest yield in Region B, correlated with poor rainfall and soil conditions.

Business crops (e.g., rice, wheat) show higher dependency on rainfall compared to cash crops.

### [3] Humidity Insights
Soil quality index average = Z/10.

Regions with higher soil fertility show consistent yield despite rainfall fluctuations.

Environmental stress factors (temperature, humidity) impact yield in specific zones.

### [4] Other Insights
Majority of farmers fall under returning users category, indicating repeat data collection.

Business-oriented farming practices dominate over personal subsistence farming.

Rainfall and soil condition are the two most critical factors influencing crop yield.
