# Data_analytics_Tableau_Comparative_study_of_countries

 The company is expanding and wants to open new branches in various parts of the world.
  The task is to compare various parameters such as income, life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio of different countries using the sample insurance dataset and world development indicators dataset.

## Objective:
+ Compare global countries based on:
+ Income Group, Life Insurance Share, Market Share, Insurance Penetration, Reinsurance Accepted Ratio, Retention Ratio
+ Identify target markets for new insurance branches
+ Provide interactive filters, KPIs, and trend visualizations to support decision-making

 ## Datasets Used
+ Primary Dataset
   - Insurance Sample Dataset → Contains insurance-related indicators by country and year
+ Secondary Dataset
   - Global Financial Development / World Development Indicators → Provides income groups and country attributes
     
## Key Features & Steps Implemented
 - Geographic Map (Income-Based Coloring)
 - A world map showing all countries
 - Colored by Income Group from the secondary dataset
 - Dashboard includes Income Group Filter
 - The country names in the map will act as the trigger
   https://en.wikipedia.org/wiki/Country

![img1](https://github.com/user-attachments/assets/c65add24-8998-4f34-8a0d-caca84e9f92d)

*  Created a KPI Table to show the comparison between the selected period and the period prior to the selected one.
 * Created two parameters for Year Selection and Category Selection
 * Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio
 *	Created a calculated field to calculate the Growth %
 *	Created a table to show these values
 *	Title will be updated based on the category selection
	
![img2](https://github.com/user-attachments/assets/5d245107-995c-4490-9804-abaa884ae4c7)

* Create Growth Indicator Shapes based on the Growth %
*	Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it
![img3](https://github.com/user-attachments/assets/dad1ad1d-e57d-42ce-82d4-d0ddaf75cb34)![img4](https://github.com/user-attachments/assets/67231c84-a14e-46c4-be71-86b4d14eeb11)

* Create a trend line to show the selected category values

![img5](https://github.com/user-attachments/assets/e15a0ecc-4bed-4c33-a668-31ff0e0acabc)


* Created a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well

  ![img6](https://github.com/user-attachments/assets/70a768ee-4c3b-44e7-9001-daf0852044b1)

## Tools Used
- Tableau Desktop
- Data Blending & Calculated Fields
- Geo Maps, KPIs, URL Actions, Trend Lines, Parameter Controls

## Insights Enabled
The dashboard allows stakeholders to:

- Identify high-income vs low-income regions with strong insurance penetration
- Compare market maturity across countries
- View year-over-year performance for key insurance metrics
- Analyze growth patterns and potential expansion opportunities
- Drill into specific countries using external web data

## Outcome
- A complete, interactive Tableau dashboard that supports global insurance expansion strategy by enabling leaders to analyze markets across economic and insurance indicators and make informed decisions on where to open new branches.
