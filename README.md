# Funnel Pipeline & Sales Conversion Analysis for Saas Tech 

### Executive Summary:

<p align ="justify"> Using SQL, Python, and Power BI, I analyzed the company’s sales pipeline to identify revenue risks, stage bottlenecks, and activity gaps affecting conversion. The dashboard highlights declining pipeline value, inconsistent sales activity, and delays in key deal stages that limit quota attainment. These insights reveal immediate opportunities to strengthen forecasting accuracy and improve overall sales effectiveness.:</p>

Key areas of improvement:

- Optimize message and workflow touchpoints inside the sales funnel.

- Increase structured follow-up through automated reminders.

- Strengthen client engagement to enhance conversion and reduce lost deals.



### Business Problem:

<p align="justify"> Completed orders are essential for this SaaS tech company because they are directly tied to revenue generation. However, stakeholders have identified that the product is experiencing a lower-than-expected conversion rate, particularly between user interaction, login attempts, and final order completion. This gap suggests that a considerable number of users fall out of the workflow before completing the intended process, indicating friction points within the login and verification stages.. </p>

#### Order completion for chart 

<img width="1536" height="1024" alt="ChatGPT Image 9 dic 2025, 16_33_35" src="https://github.com/user-attachments/assets/f414af6f-c06c-4fb1-8eb9-78e3600567b8" />
<img width="164" height="434" alt="image" src="https://github.com/user-attachments/assets/b9afc325-be9e-4ae5-9999-5b53c5c12575" />

### Methodology:

- Data Extraction: SQL queries to pull pipeline, deal stage, activity, and sales performance records.

- Data Processing: Python (Pandas, Numpy) for cleaning, transformation, and KPI calculations.

- Analytics & Visualization: Power BI for dashboard creation (funnel analysis, stage duration, win rate, activity score).

- Comparative Analysis: YTD trends, variance vs. quota, deal size behavior, agent performance benchmarking.

#### Skills:

- SQL (joins, aggregations, window functions).

- Python (Pandas, ETL, KPI computation).

- Power BI (DAX, relationships, advanced visuals).

- Data Analytics (trend analysis, funnel analytics, churn risk, win–loss analysis).

- Business Intelligence (storytelling, dashboard design, stakeholder communication).

### Results & Business Recommendations:

<p align="justify"> 
The dashboard reveals strong initial user engagement but a major drop-off before the login stage, driven by no-login attempts, errors, and MFA failures. Only 25.43% of users complete the order, indicating workflow friction rather than acquisition issues. Insights show that login errors and harvest failures are the highest-impact blockers. Reducing login errors by 1% could add 8–12 additional daily completions. Improving MFA success rates by 1% could increase daily revenue by £150–£210. Streamlining login guidance, optimizing MFA steps, and enhancing error handling are recommended to significantly improve pull-through rates. </p>

<img width="500" height="336" alt="image" src="https://github.com/user-attachments/assets/31bc0436-2c2c-45f2-a2c6-e7869af34e5e" />

✅ Pipeline value decreased $28M YTD, exposing revenue risk.

✅ Weighted pipeline decreased $8.1M, reducing win probability.

✅ Average sales cycle dropped 2 days, but stage bottlenecks persist (Proposal & Negotiation).

✅ Win rate increased to 9.3%, indicating better deal quality.

✅ Lost deals mainly due to customer unresponsiveness, pricing, and poor fit.

✅ Top agent activity score dropped by 200 points, impacting team momentum.

<p align="justify"> 
Because the strongest opportunities to increase order completion come from reducing workflow friction, improving login and MFA success rates, and stabilizing error-prone technical stages, I recommend a few strategic adjustments:

Implement guided UI prompts and early-stage nudges to encourage users to complete the login step, addressing the largest drop-off segment (“No Login Attempt”) and increasing progression into the authentication process.

Enhance MFA performance and flexibility by introducing streamlined verification flows, clearer instructions, and fallback authentication options to reduce abandonment during security validation.

Improve technical stability in harvest-related processes by optimizing backend logic, adding automated retries, and strengthening error-handling, ensuring fewer order failures caused by system interruptions.

Add real-time alerts and diagnostic indicators in dashboards to highlight failure hotspots such as login errors, MFA denials, and harvest failures, enabling teams to respond quickly and prioritize engineering fixes.

I believe these adjustments will significantly increase the pull-through rate, improve user experience across critical workflow stages, and support measurable revenue growth while reducing operational overhead through improved product visibility and faster issue detection.</p>

### Next Steps:

Build predictive models (conversion likelihood, deal scoring).

Automate daily/weekly data refresh for the dashboard.

Integrate CRM workflow triggers for stalled deals.

Develop cohort analysis by segment and agent.

Present insights to leadership and design action plan with Sales Ops.
