# Project Background
Founded in 2016, Row Health is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Row Health would like to build a deeper understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. These insights will guide their marketing budget strategy for the upcoming year. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.

The following key metrics were used to the evaluate the performance of the campaigns.

- **Click through Rate:** The percent of people who see a campaign and click on the associated link.
- **Cost per Click:** The average dollars spent per click on people who see a campaign and click on the associated link.
- **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
- **Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.


# Executive Summary
### Overview of Findings

From January 2019 to July 2023, Rhode Health successfully acquired 16,338 new sign-ups through 12 diverse campaign categories. These online campaigns, costing approximately $60,000, generated 9 million impressions and 850,000 clicks. This strategic marketing effort significantly boosted Rhode Health's brand awareness nationwide and drove an increase in sign-ups.

### About the Data
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

Rhode Health Insurance Entity Relationship Diagram (ERD)
<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/ERD.png" alt="Rhode Health Insurance ERD">
</p>


# Insights Deep-Dive
### Click through Rate
- Across categories, Health for All and Benefit Updates performed nearly 3-4x better than the average CTR at 36% and 22%, respectively.
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

### Cost per Click
- AAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
  
### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.9%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

### Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($124), as well as the lowest number of signups (23), compared to an average of $2.2.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

# Tableau Dashboard
Users can explore my interactive [Tableau dashboard](https://public.tableau.com/app/profile/jenncash29/viz/RhodeHealthCampaignCategoryDashboard/Dashboard1) and filter by plan, state, and campaign type. Highlights include tables and visualizations for KPI's, marketing, signup, and claim metrics. 
<div align="center">
  <a href="https://public.tableau.com/app/profile/jenncash29/viz/RhodeHealthCampaignCategoryDashboard/Dashboard1">
    <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Tableau%20Dashboard.png" alt="Tableau Dashboard">
  </a>
</div>

# Recommendations
- **Health for All:** Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Health Awareness:** Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
COVID Campaigns: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- **#HealthyLiving:** Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.
  
# Assumptions and Caveats
- Include campaign start and end dates to understand campaign performance over time
- Investigate missing clicks for Family Coverage Plan category

# Next Steps
- Include customer-specific dimensions (plan, state) to further tailor campaign recommendations based on client demographics
- Explore relationship between campaigns and customer claims to identify and target ideal patient types
