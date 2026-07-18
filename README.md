<img width="1215" height="918" alt="P3 ( s4 )" src="https://github.com/user-attachments/assets/93146e04-6c0c-45c5-8d7c-9a684adf5f50" />
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
*(See the visuals below for a walkthrough of the configuration and final output)*

- **<img width="1215" height="918" alt="P3 ( s4 )" src="https://github.com/user-attachments/assets/fc91f0a4-f18f-4bfb-a2f0-8982add9962e" />
** 
  *Caption: Visual automation logic handling the Lead-to-Campaign routing.*

- **<img width="1899" height="801" alt="P3 ( s3 )" src="https://github.com/user-attachments/assets/d3be0b50-a7d5-4637-8197-3fa5e77e488a" />
** 
  *Caption: Custom Summary Formula validation in the Salesforce Report Builder.*

- **<img width="1875" height="845" alt="P3 ( s2 )" src="https://github.com/user-attachments/assets/965d3672-f6e0-46ad-bb72-809844053569" />
** 
  *Caption: The resulting report displaying the calculated Marketing ROI alongside standard metrics.*

- **<img width="1853" height="839" alt="P3 ( s1 ) " src="https://github.com/user-attachments/assets/186d4348-71ba-4ebd-965c-6e8611d3dbb9" />
** 
  *Caption: High-level dashboard visualizing campaign success and total ROI for stakeholders.*

---
*Built as a portfolio project to demonstrate Salesforce declarative development skills.*
