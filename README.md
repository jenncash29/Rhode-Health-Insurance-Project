# Project Background
Founded in 2016, Row Health is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Row Health would like to build a deeper understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. These insights will guide their marketing budget strategy for the upcoming year. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.

# Executive Summary
### Overview of Findings

From January 2019 to July 2023, Rhode Health successfully acquired 16,338 new sign-ups through 12 diverse campaign categories with 57 campaign types. These online campaigns, costing approximately $60,000, generated 9 million impressions and 850,000 clicks. This strategic marketing effort significantly boosted Rhode Health's brand awareness nationwide and drove an increase in sign-ups.

### About the Data
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

Rhode Health Insurance Entity Relationship Diagram (ERD)
<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/ERD.png" alt="Rhode Health Insurance ERD">
</p>


# Insights Deep-Dive
**The following key metrics were used to the evaluate the performance of the campaigns.**

1. **Click through Rate (CTR):** The percent of people who see a campaign and click on the associated link.
2. **Cost per Click (CPC):** The average dollars spent per click on people who see a campaign and click on the associated link.
3. **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
4. **Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.
  
### Click through Rate (CTR)
- Across categories, Health For All and Benefit Updates performed nearly 3x better than the average CTR at 25% and 22%, respectively.
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

### Cost per Click (CPC)
- Golden Years Security had the highest CPC at $0.68 with the lowest CTR of 1.41%.
- Health For All had the third highest CPC at $0.10 but achieved the highest CTR at 25%.
- Benefit Updates had the third lowest CPC at $0.04 yet had the second highest CTR rate at 22%.
  
### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.08%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (2.78%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.27%.

### Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($176), as well as the lowest number of signups (23), compared to an average of $3.70.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$2.2K.

# Tableau Dashboard
Users can explore my interactive [Tableau dashboard](https://public.tableau.com/app/profile/jenncash29/viz/RhodeHealthCampaignCategoryDashboard/Dashboard1) and filter by plan, state, and campaign type. Highlights include tables and visualizations for KPI's, marketing, signup, and claim metrics. 
<div align="center">
  <a href="https://public.tableau.com/app/profile/jenncash29/viz/RhodeHealthCampaignCategoryDashboard/Dashboard1">
    <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Tableau%20Dashboard.png" alt="Tableau Dashboard">
  </a>
</div>

# Presentation Sample
A PowerPoint presentation was created for the marketing team to present insights and recommendations from the campaign analysis. An excerpt from the slides below highlights top-performing campaign figures, recommendations, caveats and next steps, and an appendix detailing the technical process.

<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Signup%20Rates%20Slide.png" alt="Signup Rate">
</p>

<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Key%20Recommendations%20Slide.png" alt="Recommendations">
</p>

<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Caveats%20and%20Next%20Steps%20Slide.png" alt="Caveats and Next Steps">
</p>

<p align ="center">
  <img src="https://github.com/jenncash29/Rhode-Health-Insurance-Project/blob/main/images/Technical%20Process%20Slide.png" alt="Technical Process">
</p>
__________________________________________________________________________________________________________________________




