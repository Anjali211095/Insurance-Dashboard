The objective of this project is to create a comprehensive Insurance Dashboard in Power BI that provides an interactive and visually compelling representation of critical insurance metrics. The dashboard will allow users to slice and dice data using various filters, explore trends in policy status, claim amounts, and demographic data, and view premium and coverage amounts based on multiple factors.

Key Dashboard Features:
Slicers: Slicers allow users to filter and view data based on specific criteria. The slicers in this dashboard include:

Policy Type: Filter policies by different types such as life insurance, health insurance, car insurance, etc.
Claim Number: Filter by specific claim numbers to drill into claim-specific data.
Customer ID: Allows filtering by individual customers to review their claim and premium history.
Policy Status: Filter by active or inactive policies to view policy trends and premium/claim dynamics.
Age Group: Filter claims by age group to analyze trends in different age demographics.
Cards: Power BI cards will be used to highlight key figures related to insurance policies and claims:

Premium Amount: Displays the total premium collected across all policies or filtered groups.
Claim Amount: Shows the total claim payout amount across all policies.
Coverage Amount: Displays the coverage amount, giving insight into how much coverage is provided.
Gender Breakdown: A card showing the distribution of policies or claims by gender to highlight any trends.
Visualizations: The dashboard will include a variety of visualizations to help users explore data effectively.

Area Chart for Premium Amount by Policy Status: An area chart will be used to display trends in premium amounts over time, broken down by policy status (active vs. inactive). This will help users understand how premium collection varies between active and inactive policies, and across different time periods.

Line Chart for Claim Amount by Age Group: This line chart will plot claim amounts across different age groups, helping to identify any patterns or outliers in claims based on customer age.

Line Chart for Premium Amount by Policy Type: This chart will allow users to see premium amounts categorized by policy type, enabling comparisons between different types of insurance, such as life insurance, health insurance, etc.

Line Chart for Inactive vs. Active Policies: This chart will plot the number of active and inactive policies over time, providing insight into how the ratio between active and inactive policies evolves, as well as its impact on premium and claim amounts.

Data Model:
The data model for this dashboard will consist of several related tables, including:

Policies Table: Contains details about the policy types, status (active/inactive), coverage amount, premium amount, customer IDs, and associated claims.
Claims Table: Contains claim numbers, claim amounts, customer IDs, policy type, and date of claims.
Customers Table: Contains customer details such as customer ID, age, gender, and location.
Key Metrics & KPIs:
The following KPIs will be measured on the dashboard:

Total Premium Collected: Sum of premiums for all policies or filtered group.
Total Claim Amount: Total of all claim amounts.
Average Premium by Policy Type: Breakdown of average premium per policy type.
Claim Ratio by Age Group: Ratio of claim amounts versus premium for different age groups.
Inactive vs. Active Policy Count: Number of inactive vs. active policies.
Interactivity:
The dashboard will be fully interactive, with slicers enabling dynamic filtering of the data. When a user selects a particular policy type or age group, the charts and cards will automatically update to reflect the selected filter.
Cross-highlighting will be enabled, allowing users to click on elements within the visualizations to drill down and filter other visualizations dynamically.
Potential Use Cases:
Insurance Company Executives: Gain insights into the overall health of the company’s policies, premium collections, and claims.
Risk Analysts: Analyze which age groups or policy types contribute the most to claims and whether premiums are adequately priced.
Marketing Teams: Use insights from policy and claim data to target specific demographics more effectively.
End-User Experience:
The users will be able to:

View policy performance by filtering specific policies, age groups, and genders.
Analyze premium amounts across different time periods and by policy type or status.
Observe trends in claims by age group and understand the relationship between premiums and claims.
Make data-driven decisions by exploring different dimensions of insurance data.
