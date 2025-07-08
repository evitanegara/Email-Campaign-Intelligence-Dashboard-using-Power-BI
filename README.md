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

### Campaign Performance Overview

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

