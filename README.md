# Salesforce Marketing ROI Automation ☁️

## Project Overview
This project showcases an end-to-end declarative Salesforce solution designed to bridge the gap between marketing effort and sales revenue. By automating lead-to-campaign association and creating custom ROI metrics, this solution provides marketing teams with immediate, actionable insights into campaign performance.

## Key Technical Skills Demonstrated
*   **Automation:** Built a `Record-Triggered After-Save Flow` to map incoming Leads to specific Campaigns based on UTM parameters, eliminating manual data entry.
*   **Advanced Reporting:** Configured `Custom Summary Formulas` in Salesforce Reports to calculate ROI percentages `((Amount - Cost) / Cost)` that are not available out-of-the-box.
*   **Business Logic:** Designed a scalable data architecture to ensure clean lead attribution and accurate financial reporting.
*   **Visual Dashboards:** Created executive-level dashboards to visualize ROI and conversion metrics.

## Solution Architecture
### 1. Automation Logic
*   **Goal:** Auto-associate Leads to Campaigns.
*   **Tool:** Salesforce Flow Builder.
*   **Implementation:** Triggered when a Lead is created with a `Campaign_UTM` value, the flow identifies the matching campaign and updates the Lead record.

### 2. ROI Calculation
*   **Goal:** Calculate true financial ROI per campaign.
*   **Tool:** Custom Summary-Level Formula (Report Builder).
*   **Logic:** `(AMOUNT:SUM - Campaign.Budgeted_Cost__c:SUM) / Campaign.Budgeted_Cost__c:SUM`

## Project Showcase
*(Insert your screenshots here)*
-*Caption: Visual automation logic handling the Lead-to-Campaign routing.*

-**[Insert Screenshot of Flow Canvas Here]** 
  *Caption: Visual automation logic handling the Lead-to-Campaign routing.*

- **[Insert Screenshot of ROI Formula Here]** 
  *Caption: Custom Summary Formula validation in the Salesforce Report Builder.*

- **[Insert Screenshot of Final Report Here]** 
  *Caption: The resulting report displaying the calculated Marketing ROI alongside standard metrics.*

- **[Insert Screenshot of Executive Dashboard Here]** 
  *Caption: High-level dashboard visualizing campaign success and total ROI for stakeholders.*

---
*Built as a portfolio project to demonstrate Salesforce declarative development skills.*
