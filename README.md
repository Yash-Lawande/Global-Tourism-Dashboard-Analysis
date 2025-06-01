# Global-Tourism-Dashboard-Analysis
## Project Objective
To develop a dynamic and interactive Power BI dashboard that comprehensively analyses global tourist arrival trends, identifying significant growth patterns, temporary declines during global events, and regional contributions. The objective is to provide actionable insights to policymakers and industry stakeholders for strategic planning and fostering sustainable tourism development.
## Dataset used 
The analysis for this project was performed using datasets primarily sourced from the **United Nations World Tourism Organization (UNWTO)**. You can find these raw data files in the - <a href="unwto-all-data.xlsx">Dataset</a>  directory of this repository

## Questions that can be asked about our dashboard:

### Overall Trends
* What was the overall trend in tourist arrivals for China between 1995 and 2025, and what significant peaks or drops were observed?
* How did global events like the 2008 financial crisis and the COVID-19 pandemic impact tourist arrivals in China, India, Indonesia, Japan, and Thailand?
* Which country experienced the most significant percentage drop in tourist arrivals during the COVID-19 pandemic?

### Regional Analysis
* Which region contributes the most to tourist arrivals in China over the entire period?
* How have the regional contributions to tourist arrivals changed over time for India?
* Are there any emerging regions that show increasing contributions to tourism in Southeast Asian countries like Indonesia or Thailand?

### Purpose of Travel
* How does the number of personal travel arrivals compare to business and professional travel arrivals for China year over year?
* Did the proportion of business travel increase or decrease during economic downturns for India?
* Which purpose of travel (personal or business) showed more resilience during periods of decline in tourist arrivals for Japan?

### Modes of Transport
* What is the dominant mode of transport for tourists arriving in China, and how has this changed over time?
* Are there any noticeable shifts in transport modes used by tourists in India post-2020?
* How does the reliance on air transport for arrivals compare between Japan and Thailand?

### Country-Specific Comparisons
* Compare the growth trajectory of tourist arrivals in China versus India from 1995 to 2019.
* Which country (among China, India, Indonesia, Japan, Thailand) has the most diverse regional source of tourists?
* Analyze the recovery patterns in tourist arrivals for China and India post-2020.

## Dashboard Interaction
- <a href="Dashboard.jpeg">View Dashboard</a>

## Process:

1.  **Data Collection and Preparation:**
    * Gathered historical data on tourist arrivals, categorized by year, region of origin, purpose of visit (personal, business and professional), and mode of transport (air, water, land).
    * Cleaned and transformed raw data to ensure consistency and accuracy for analysis in Power BI.

2.  **Dashboard Design and Development (Power BI):**
    * **Main Trend Analysis:** Created line charts to visualize the total sum of arrivals over time for each country (China, India, Indonesia, Japan, Thailand) to highlight growth patterns and significant dips.
    * **Regional Contributions:** Developed stacked bar charts to show the sum of arrivals by different regions (Africa, Americas, East Asia and the Pacific, Europe, South Asia, Middle East) across the years, allowing for a clear understanding of regional market share.
    * **Purpose of Travel Analysis:** Implemented line charts to compare the sum of personal and business/professional arrivals over time, illustrating the different trends in travel motivations.
    * **Transport Mode Analysis:** Designed line charts to display the sum of arrivals by air, water, and land transport, revealing popular entry methods and any shifts in preferences.
    * **Interactive Elements:** Incorporated slicers for year and country to enable dynamic filtering and exploration of data.
    * **Visual Enhancements:** Applied appropriate color schemes and labels for readability and aesthetic appeal.

3.  **Insights Extraction and Validation:**
    * Analysed the generated visualizations to identify key trends, anomalies, and correlations.
    * Validated findings against known global events (e.g., 2008 financial crisis, COVID-19 pandemic) to confirm their impact on tourism data.
    * Refined visualizations based on initial insights to better communicate findings.

## Dashboard
![Dashboard](https://github.com/user-attachments/assets/4c9b9647-cb95-4450-8abd-ad9b46f9e517)

## Project Insights:

* **Significant Growth Followed by Sharp Decline:** Tourist arrivals across most analyzed countries (China, India, Japan, Thailand, Indonesia) showed a general upward trend from the late 1990s, peaking around 2018-2019, before experiencing a dramatic drop in 2020 due to the COVID-19 pandemic. China's arrivals, for instance, peaked at 65K around 2018-2019 before falling to almost 0K in 2020. India saw a peak of 10.9K around 2018-2019 and a similar drop.
* **Impact of Global Events:** The 2008 financial crisis caused a temporary dip in tourist arrivals for some countries, but the COVID-19 pandemic had a far more profound and immediate negative impact, leading to near-zero arrivals in 2020 for many.
* **Dominance of East Asia and the Pacific:** For China, East Asia and the Pacific consistently represented the largest share of tourist arrivals over the entire period. This trend is likely similar for other Asian countries.
* **Personal Travel Dominates:** Personal travel generally accounts for a significantly larger proportion of tourist arrivals compared to business and professional travel across the analyzed countries. While both categories were affected by downturns, personal travel often showed a more pronounced decline during crises.
* **Air Transport as Primary Mode:** Air transport is the predominant mode of arrival for tourists in most analyzed countries, especially for long-haul travel. Land and water transport contribute smaller, but notable, shares depending on the country's geographical context.

## Final Conclusion:

This Power BI dashboard effectively illustrates the dynamic nature of global tourism. It highlights a period of sustained growth leading up to 2019, followed by an unprecedented collapse in 2020 due to the COVID-19 pandemic, and a gradual, albeit incomplete, recovery thereafter. The visualizations clearly demonstrate the varying impacts of economic and health crises on different aspects of tourism, including regional contributions, travel purposes, and transport modes. The dominance of personal travel and air transport, alongside the significant contribution of the East Asia and Pacific region, provides valuable insights for targeted marketing and infrastructure development. This dashboard serves as a powerful analytical tool for policymakers and industry stakeholders, enabling them to make informed decisions for fostering resilient and sustainable tourism strategies in the face of future challenges.



