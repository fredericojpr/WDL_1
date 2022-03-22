# World Data League 2022

## 🎯 Challenge
#### *Predict Waste Production for its Reduction* (UrbanAI)

## 👥 Authors
* Bruno Alho
* Frederico Rodrigues
* Miguel Zina

## ✨ Introduction (250 words max)
*With world's population escalation, one of the major concerns within high density cities is their generation of environmental pollutants. 
Solid-waste management represents one of the greatest costs to municipal budgets, and given that the projected global waste generation continues to rise, understanding the drivers of it's growth can play a crucial role on improving garbage collection and managent. (https://www.nature.com/articles/502615a)*

*Austin (TX) was the fastest growing metro area of the last decade in the U.S., having its population expanded by a third. The capital of Texas is seen as the next big tech hub in the country and is expected to keep its growth. (https://austonia.com/austin-fastest-growing-metro)*

For this challenge our main purpose was to exlpore the patterns of waste production/collection in the city of Austin as well as the key factors that influence it.

## 🔢 Data (250 words max)
To support our research we have used different sources of information spanning four (4) pivotal areas:
1) *Daily Waste Collection Report for Austin* - a dataset shared by the City of Austin official data portal, containing daily reports of waste collection
2) *Population History* - sourced by the US Census Bureau and the City of Austin 
3) *Labour & Unemplyment* - sourced by the US Bureau of Labor Force Statistics, containing historical data of Employment for the city of Austin
4) *Issued Construction Permits* - also shared by the City of Austin official data portal, with historical data of issued construction permits both Residential and Commecercial 
5) *Weather History for Austin*

For our analysis, the team decided to set a particular time-frame that didn't include the recent Covid-19 pandemic. 
This decision was based on our findings regarding abrupt differences during lockdown periods ant the fact that our main dataset didn't include the most recent events (last collection events recorded around mid-2021).

It was settled that the time frame to use would be the last decade [2010, 2020[.


## 🧮 Methods and Techniques (250 words max)
Tell us what methods and algorithms you used and the results you obtained.
*Write here* t
Time Series.........


## 💡 Main Insights (300 words max)
Explain what you discovered from addressing this problem, such as interesting facts or statistics.

From our early exploratory analysis, some hypothesis were confirmed by data and other interesting facts were spotted.
- Monday is the day of the week with the greatest collected volume (as expected)
- Weekend's have  considerably less collections and collected volume (as expected)
- Weekdays present the biggest average waste collected, followed by weekends and then holidays (as expected)
- Garbage collection is the main Load Type (total volume)
- TDS Landfill is the main Drop-off site (total volume and number of drops)
- Between 10 a.m and 3 p.m. are the most common hours of collection

-------> Incluir insights dos outros datasets?
-------> Falar Forecast?

## 🛠️ Product
### Definition
Dashboard for collection route control

### Users
Route Planners and Waste Managers would benefit the most of using this dashboard to control and predict how to allocate their resources for the coming days/ weeks.


### Activities
* Predicts the changes in waste production in short and medium term
* Suggests which areas/routes need to be reinforced or diminished

### Output
Location of route to be improved and expected load weight.


## 🌍 Social Impact Measurement
### Outcome
If the outputs are your immediate results, describe your long-term results. What do you want your product to achieve? What ''good'' are you creating?
Example: To decrease response time from dispatchers so that people in urgent need receive help faster.

### Impact Metrics
From the outcome, define **2 to 4 metrics** that measure if you are achieving that outcome or not.
Example:
* Average Dispatch Time
* Average Distance from Accident Location and Dispatch Center

### Impact Measurement
Since you cannot wait to see the impact of your product, estimate it. You can do that by either using the estimations/predictions of your model, market research, products from proxy industries and/or similar locations, etc.

Example:
* *Based on model predictions*: Our model estimates a decrease of 6 minutes of the average dispatch time and a decrease of the average distance of 200 meters
* *Based on proxy products*: Similar studies in other cities show that the dispatch time can be decreased by as much as 13 minutes, depending on the traffic intensity of that city.
