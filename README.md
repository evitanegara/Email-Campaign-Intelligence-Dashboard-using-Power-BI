# Email Campaign Analysis Dashboard using Power BI

## Project Overview

This dashboard provides a detailed analysis of email marketing campaign performance over a three-month period (July–September 2024). It offers key insights into when audiences are most engaged, which content types perform best, how different client segments behave, and which regions contribute most to conversions. Built in Power BI, the dashboard transforms raw engagement metrics into actionable visualizations to support marketing strategy, UX optimization, and audience targeting. It enables campaign managers to identify high-impact sending times, optimize content design, and refine audience segmentation to improve open, click, and conversion rates.

## Dataset Overview

| Column            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Campaign name     | Name of each email campaign                                                 |
| Campaign type     | Type of campaign (newsletter, events and webinars, promotional, nurturing)  |
| Conversion target | Goal of the campaign (sign-up, purchase, download, form, web visit)         |
| Date sent         | Date the campaign was sent                                                  |
| client_email      | Email address of the recipient                                              |
| client segment    | Recipient type (Lead or Customer)                                           |
| country           | Country of the recipient                                                    |
| country latitude  | Country’s latitude                                                          |
| country longitude | Country’s longitude                                                         |
| device            | Device used to open the email (desktop or mobile)                           |
| opened            | 1 if the recipient opened the email                                         |
| clicked           | 1 if the recipient clicked any link or button                               |
| bounced           | 1 if the email was undelivered                                              |
| unsubscribed      | 1 if the recipient unsubscribed                                              |
| conversion        | 1 if the recipient completed the campaign goal                              |

## Executive Summary

The analysis reveals that email engagement peaks mid-week, with Wednesdays showing the highest opens and clicks. August was the best-performing month by clicks, while September led in opens but had a lower click-through rate. Events and Webinars were the most effective campaign types, and Leads consistently outperformed Customers in both clicks and conversions. Most engagement occurred on desktop devices, but mobile also contributed significantly. Top conversion goals were Web Visits and Sign Ups, while Form Completions and Downloads underperformed. Asia led by total conversions, and Iceland had perfect engagement metrics, contrasting with high bounce and unsubscribe rates in countries like Afghanistan and Kosovo.
## Visualization
![image](https://github.com/user-attachments/assets/3a3fa00c-c5b4-4253-97e0-26140ef35f5e)
![image](https://github.com/user-attachments/assets/d53de185-3950-4bf9-9e22-a151eded241e)
![image](https://github.com/user-attachments/assets/d9694876-68c1-4e51-a5eb-8a556a58726c)

<p align="center">
  <img src="https://github.com/user-attachments/assets/3a3fa00c-c5b4-4253-97e0-26140ef35f5" alt="email campaign" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d53de185-3950-4bf9-9e22-a151eded241e" alt="email campaign power bi" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9694876-68c1-4e51-a5eb-8a556a58726c" alt="email campaign dasboard" width="700"/>
</p>

## Insights Deep-Dive

###  Time-Based Engagement Patterns
- Email open and click activity fluctuates heavily across different days of the month, suggesting recipient responsiveness is influenced by campaign timing.
- Day 18 recorded the highest open volume at 2.9K and click volume of 125, indicating a highly successful campaign.
- Day 7 follows with 2.8K opens and 272 clicks, showing another peak in engagement.
- Day 28 and Day 3 also saw strong performance, with over 2K opens each and 150+ clicks.
- Several dates such as Day 20, 17, and 24 saw fewer than 10 clicks, indicating possible inefficiencies in CTA placement or email content.

### Weekly Trends
- Wednesday stands out as the highest performing weekday, achieving 9.2K opens and 615 clicks—more than double the volume of other weekdays.
- Monday and Thursday both recorded 3.3K opens and clicks, positioning them as secondary best days.
- Sunday has the lowest engagement indicating that weekend emails are less effective.

### Monthly Trend
- August led in total click volume with 8,203 clicks and had 8,203 opens, marking it as the most engaging campaign month overall.
- September generated the highest open volume at 8,347, but had only 541 clicks, indicating lower click-through effectiveness.
- July had the lowest open volume but still achieved 583 clicks, reflecting strong CTA or content performance among fewer engaged users.

#### Top Campaign by Conversion Rate
- The August Newsletter delivered the highest conversion count, reaching 349 conversions, making it the most successful campaign of the quarter.
- September Newsletter followed with 140 conversions, confirming that newsletters consistently perform well in driving user action.
- Other high-performing campaigns include After Event Follow-Up with 125 conversions, Product Workshop Invitation July with 100 conversions, and Product Workshop Invitation September with 89 conversions, all of which demonstrate strong user engagement beyond the top newsletters.

### Campaigns with the Highest Bounce Rate
- Product Workshop July recorded the highest bounce rate at 0.14%, suggesting significant issues with list quality or email deliverability. Followed by After Event Follow Up with a bounce rate of 0.13%.
- Drip3 Licensing and Pricing Plan had the lowest bounce rate at 0.04%.
- Compared to Drip3, both Product Workshop July and After Event Follow Up had bounce rates over three times higher, highlighting the need for improved list hygiene in event-driven campaigns.

### Total Click and Conversion by Campaign Type
- Events and Webinars campaigns recorded the highest engagement, with 1,141 clicks and 599 conversions, making them the top-performing format.
- This was followed by Newsletter campaigns, which also delivered strong results with 622 clicks and 547 conversions.
- Lead Nurturing campaigns came next with moderate engagement levels.
- The least effective were Promotional campaigns, generating only 19 clicks and 8 conversions, showing the biggest gap in campaign performance. Compared to Promotional campaigns, Events and Webinars drove nearly 60 times more conversions.

### Engagement by Campaign Type and Client Segment
- Leads consistently outperformed Customers across all campaign types in both clicks and conversions.
- The highest engagement from Leads was seen in Events and Webinars, followed by Newsletters, while Lead Nurturing campaigns were engaged exclusively by Leads with no customer interaction.
- In contrast, Customers showed lower but steady engagement, particularly in Newsletters and Events.
- This pattern highlights that Leads are more active and responsive to campaign messaging, making them the ideal segment to prioritize for future targeting.

### Total Clicks and Conversions by Client Segment
- Leads recorded the highest engagement, with 1,314 total clicks and 806 conversions, outperforming Customers in both metrics.
- Customers contributed 703 clicks and 471 conversions, showing lower response levels across all campaign types.
- This trend highlights the importance of prioritizing Leads in future campaign targeting, as they consistently demonstrate stronger conversion intent.

### Clicks by Device Type
- The majority of email engagement occurred on desktop devices, which accounted for 1,244 clicks (61.7%).
- Mobile devices generated 771 clicks (38.2%), reflecting a strong on-the-go audience segment.
- Only 2 clicks (0.1%) came from unknown devices.
- These insights reinforce the need to optimize email layout and CTA design for both desktop and mobile audiences.

### Conversions by Goal Type
- Web Visit was the most successful goal, achieving 551 total conversions, 311 from Leads, 240 from Customers.
- Sign Up ranked second, with 269 conversions from Leads and 172 from Customers, totaling 441 conversions.
- Purchase conversions were heavily driven by Leads 123 vs. 4, indicating higher buying intent among prospects.
- Form Completion had the lowest total, with only 33 conversions recorded.

### Click Engagement by Conversion Goal Type
- Sign Up received the most click activity with 495 clicks from Leads and 304 from Customers, totaling 799 clicks.
- Web Visit followed, with 363 clicks from Leads and 263 from Customers.
- Purchase had a strong lead-side performance 241 clicks but very low from Customers 9 clicks, showing a steep drop in conversion likelihood.
- Form Completion and Download goals had the lowest engagement, with just 45 and 170 clicks from Leads respectively.

### Country-Level Performance
- Iceland delivered a perfect 100% open, click, and conversion rate, making it the top-performing country overall.
- Vanuatu and Guinea followed with 20% and 11% conversion rates respectively, standing out as high-converting regions.
- Most countries recorded conversion rates under 10%, indicating that strong performance is concentrated in a few standout regions.

### Continent-Level Conversion Trends
- Asia recorded the highest number of total conversions 426, making it the most engaged region.
- Europe followed with 268 conversions, and North America placed third with 213 conversions.
- Australia/Oceania showed the lowest performance, contributing just 31 conversions across all segments.

### Campaign Type by Continent
- Events and Webinars were the best-performing campaign types across all continents—especially in Asia around 211 conversions and Africa in total 149 conversions.
- Newsletters had consistent performance in Europe and North America.
- Lead Nurturing was most active in North America around 57 conversions and Europe around 34 conversions, with limited impact elsewhere.
- Promotional campaigns showed minimal traction across all regions.

### Countries with the Highest Unsubscribe & Bounce Rates
- Kosovo recorded the highest unsubscribe rate at 2.22%, followed by Lebanon 1.61% and Denmark 1.30%.
- Afghanistan had the highest bounce rate at 3.70%, over 15x the global average.
- Myanmar, UAE, Indonesia, and Australia had the lowest bounce rates below 0.25%, indicating strong list quality and deliverability.

## Recommendations

### Campaign Timing
- Focus email delivery on mid-week days, which consistently demonstrate higher open and click rates. These align better with user behavior and inbox-checking patterns.
- Avoid weekend sends, especially Sundays as engagement significantly drops due to reduced screen time and work related attention.
- Maintain a consistent send schedule whicha re same time and day each week to improve familiarity and support long-term open rate performance.
- Avoid over sending, as high campaign frequency correlates with higher unsubscribe rates. Saturated segments should be managed carefully to protect list health.

### Campaign Content Strategy
- Continue prioritizing Events, Webinars, and Newsletters, as these consistently yield the highest conversion results.
- Use visual storytelling to enhance emotional connection and brand recall. Visuals are processed up to 60,000x faster than text and improve engagement.
- Optimize CTA buttons by:
  - Placing CTAs in clear, prominent areas  
  - Using contrasting colors to draw attention  
  - Applying action-oriented language like “Download Now” or “Get Your Guide”
- Implement A/B testing to validate subject lines, CTA designs, and layout decisions—ensuring the best-performing variants are prioritized.

### Audience Targeting
- Prioritize Leads in campaign targeting—they deliver stronger click and conversion rates and present better ROI potential.
- Reevaluate the Promotional campaign strategy, which showed the lowest engagement. Revise messaging, design, or targeting to improve relevance.
- Focus efforts on high-performing countries like Iceland, Vanuatu, and Guinea. Simultaneously, exclude or clean underperforming segments with high bounce rates to improve deliverability.

### Device Experience & UX Optimization
- With over 61% of clicks from desktop, ensure landing pages are optimized for fast loading, clean design, and intuitive layout.
- Improve landing page quality by:
  - Ensuring SEO-optimized, original, and relevant content  
  - Highlighting unique selling propositions (USPs) early  
  - Using trust signals (testimonials, contact info, security icons)  
  - Simplifying navigation and reducing visual clutter

### Conversion Goal Design
- Continue promoting Web Visits and Sign-Ups, which currently show the highest success rates.
- Redesign or test new approaches for lower performing goals like Form Completions and Downloads consider shorter forms, clearer CTA text, and better-aligned landing pages.
- Tailor messaging and CTA design based on goal type to ensure better alignment between user intent and experience.

### List Hygiene & Email Deliverability
- Audit and clean contact lists from high-bounce campaigns like Product Workshop (July) and After Event Follow-Up to improve sender reputation.
- Replicate formatting, tone, and send timing from low bounce campaigns like Drip3 Licensing to enhance inbox placement.
- Monitor unsubscribe behavior in countries with high opt-out rates (e.g., Kosovo, Lebanon). Consider reducing frequency or changing tone for these regions.

### High Open, Low Click Campaigns
- Investigate campaigns like September, which showed strong open performance but low click through rates often due to weak CTAs or content mismatch.
- Rework layout, message clarity, and CTA visibility on dates like Day 17, 20, and 24 to better convert already-engaged recipients.
 
## Contact

For questions or collaboration, contact **evitanegara@gmail.com**
