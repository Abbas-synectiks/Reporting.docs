**Use Case: Budget Dashboard**

**Actor:** Financial Analyst, Cloud Administrator, Department Manager

**Goal:** To monitor and manage budget allocations, spending trends, and forecasted expenditures across multiple cloud platforms (AWS, GCP, Azure) using the Budget Dashboard.

**Preconditions:** The user must have appropriate permissions to access budget data and view detailed reports within the Budget Dashboard.

**Main Flow:**

1. The user logs in to the Budget Dashboard, which provides access to budget-related information for AWS, GCP, and Azure cloud platforms.
1. The Budget Dashboard consists of three tabs: AWS, GCP, and Azure, allowing users to view budget data specific to each cloud platform.
1. At the top-right corner of the screen, the user finds a duration button, which allows them to select the desired time period for viewing budget and spending data. Duration options include 1 day, 1 week, 1 month, quarter, half-year, and annual.
1. Below the tabs, the user sees four data cards displaying the following information:
   1. Budget Allocated: The total budget allocated for the selected time period.
   1. Remaining Budget: The remaining budget available after deducting total spend.
   1. Total Spend: The total expenditure incurred during the selected time period.
   1. Forecasted Spend: The projected spending forecasted for the remaining duration of the budget cycle.
1. Beneath the data cards, the Budget Dashboard features four widgets:
   1. Accounts with High Spending: Graphical representation of accounts with the highest spending.
   1. Transaction Type Cost: Graphical breakdown of spending by transaction types.
   1. Top Products of High Spending: Graphical representation of top products with high spending.
   1. Top Departments of Exceeding Budget: Graphical representation of departments exceeding budget allocations.
1. Each widget includes a kebab menu at the top-right corner, allowing users to access detailed reports and analytics for the specific data represented in the widget.
1. Below the widgets, the user encounters three data cards representing specific budget categories:
   1. R&D Department Budget: Details of the budget allocated and spent by the Research and Development department.
   1. Cluster Budget: Budget allocation and spending details for specific clusters or projects.
   1. Production Budget: Details of the budget allocated and spent for production-related activities.
1. Clicking on any of the data cards opens a detailed view, providing comprehensive insights into budget allocations, spending patterns, and forecasted expenditures for the selected category.

   **Alternative Flow:**

1. If the user encounters any errors or discrepancies in budget data or spending trends, they can utilize filtering options, review historical data, or seek assistance from the support team for resolution.

   **Postconditions:** The user gains a comprehensive understanding of budget allocations, spending trends, and forecasted expenditures across AWS, GCP, and Azure cloud platforms, enabling informed decision-making and effective budget management strategies.














   Title: Top Accounts with High Spending Analysis

- Actors:

1. Financial Analyst
1. Cloud Administrator
1. Department Manager

- Goal: To analyze and manage top accounts with high spending across AWS, Azure, and GCP platforms using the Top Accounts with High Spending Analysis tool.

- Preconditions:

1. Users must have appropriate permissions to access spending data and view detailed reports within the Top Accounts with High Spending Analysis tool.


- Main Flow:

1. Users access the Top Accounts with High Spending Analysis tool to gain insights into accounts with significant spending across AWS, Azure, and GCP platforms.
1. A breadcrumb trail at the top of the screen provides navigation options.
1. Below the breadcrumb trail, users find three tabs: AWS, Azure, and GCP, enabling them to view high spending details specific to each cloud platform.
1. Users click on one of the tabs to select a cloud platform and access detailed spending information for top accounts.
1. Beneath the tabs, four widgets display key spending metrics:
1. Month to Date Spend: Shows spending for the current month.
1. Forecasted Spend: Predicts future spending based on current trends.
1. Last Month Spend: Compares spending for the previous month.
1. Average Daily Spend: Calculates the average spending per day.
1. Users scroll down to find a table titled "Top 5 Spending Accounts" with the following headers:
1. Account ID: Unique identifier for each account.
1. Department: Department or team associated with the account.
1. VPC: Virtual Private Cloud associated with the account.
1. Service Count: Number of cloud services utilized within the account.
1. High Spending Region: Region where most spending occurs.
1. Spending: Amount of money spent within the account.
1. Variance: Difference between actual spending and budgeted amount.
1. Budgeted Amount/Budget: Allocated budget for the account.
1. A search bar at the top-right corner of the table allows users to search for specific accounts.
1. Users can analyze spending patterns, identify top accounts with high spending, and compare actual spending with budgeted amounts.

- Alternative Flow:

1. If users encounter discrepancies or errors in spending data, they can utilize the search functionality or review historical spending trends to identify and address issues.

- Postconditions:

1. Users gain actionable insights into top accounts with high spending across AWS, Azure, and GCP platforms, enabling informed decision-making and effective budget management strategies.









Title: Cost of Services Analysis for Account

Actors:

Financial Analyst

Cloud Administrator

Department Manager

Goal: To analyze and manage the cost of services within a specific account across AWS, Azure, and GCP platforms using the Cost of Services Analysis tool.

Preconditions:

Users must have appropriate permissions to access spending data and view detailed reports within the Cost of Services Analysis tool.

The user must have clicked on an Account ID or Service Count from the Top Accounts with High Spending Analysis page.

Main Flow:

After clicking on an Account ID or Service Count, the user is directed to the Cost of Services Analysis page.

A breadcrumb trail at the top of the screen provides navigation options.

Below the breadcrumb trail, users find three tabs: AWS, Azure, and GCP, enabling them to view cost of services details specific to each cloud platform.

The page displays a title "Cost of Services in Account ID" to indicate the focus of the analysis.

Below the title, four widgets display key spending metrics:

Month to Date Spend: Shows spending for the current month.

Forecasted Spend: Predicts future spending based on current trends.

Last Month Spend: Compares spending for the previous month.

Average Daily Spend: Calculates the average spending per day.

Users scroll down to find a table titled "Overview of Top 10 Services" with the following headers:

Service Name: Name of the cloud service.

Total Instances: Total number of instances or resources used for the service.

Current Month Spend: Amount spent on the service in the current month.

Last Month Spend: Amount spent on the service in the previous month.

Variance: Difference between current month spend and last month spend.

A search bar at the top-right corner of the table allows users to search for specific services.

Pagination at the bottom of the table allows users to navigate through multiple pages if necessary.

Alternative Flow:

If users encounter discrepancies or errors in spending data, they can utilize the search functionality or review historical spending trends to identify and address issues.

Postconditions:

Users gain actionable insights into the cost of services within a specific account across AWS, Azure, and GCP platforms, enabling informed decision-making and effective resource allocation strategies.


**Use Case Title: Analyze Transaction Cost Breakdown by Type**

**Actor:** Financial Analyst (or anyone with access to the financial dashboard)

**Goal:** Gain insights into the composition of transaction costs by visualizing the breakdown of different transaction types (usage, tax, credit, recurring charges).

**Precondition:** The user has logged in to the platform and has access to the financial dashboard.

**Main Success Scenario:**

1. The user navigates to the financial dashboard within the platform.
1. On the dashboard, the user locates the "Transaction Type Cost" widget.
1. The widget displays a circle chart visually representing the breakdown of transaction costs by type.
   1. Each slice of the pie chart corresponds to a specific transaction type (usage, tax, credit, recurring charges).
   1. The size of each slice is proportional to the corresponding cost amount.
   1. Hovering over a slice displays a tooltip revealing the transaction type and its associated cost percentage or absolute value (depending on preference).
1. (Optional) The user can click on a specific slice of the pie chart to:
   1. Filter the dashboard or generate a report focusing on the selected transaction type.
   1. Drill down to a detailed view with a list of transactions belonging to that type.

**Alternative Flow:**

- If there are no transactions yet, the circle chart displays a message like "No Transaction Data Available."

**Exceptions:**

- The system encounters an error while retrieving transaction data. The user is presented with an error message and advised to contact support.

**Benefits:**

- Users can quickly understand the overall composition of their transaction costs at a glance.
- The circle chart provides a clear visual representation, making it easy to identify the most significant cost contributors.
- Optionally filtering by transaction type allows for deeper analysis of specific cost categories.


**Use Cases for "Available Budgets" Widget**

Following the example use case provided, here's a prompt to create use cases for the "Available Budgets" widget with budget cards:

**Actor:** Financial Analyst (or anyone with access to the financial dashboard)

**Goal:** Monitor and manage the organization's AWS budgets by viewing a consolidated overview and detailed information for each budget.

**Preconditions:**

- The user has logged in to the platform and has access to the financial dashboard.
- The user has appropriate permissions to view budget details.

**Use Case 1: Available Budgets Overview**

**Main Success Scenario:**

1. The user navigates to the financial dashboard within the platform.
1. The user locates the "Available Budgets" widget on the dashboard.
1. The widget displays a list of cards, each representing a single budget.
1. Each card displays the following information:
   1. Budget Name
   1. Department Name
   1. Time Period Left (e.g., "2 Months Remaining")
   1. Remaining Budget (absolute value)
   1. Budget Period (monthly, weekly, quarterly, yearly)
1. The card also features a progress bar:
   1. Divided from the center, visually separating remaining and spent budget.
   1. The right side of the bar displays the Total Budget Allocated.
   1. As spending increases, the filled portion of the bar on the left side expands towards the center, visually representing the remaining budget.
1. The user can quickly scan the list of cards to identify potential budget concerns based on:
   1. Low remaining budget values.
   1. Short time period left for expiration.

**Alternative Flow:**

- If there are no active budgets, the widget displays a message like "No Active Budgets Found."

**Benefits:**

- Provides a consolidated view of all active budgets within the organization.
- Users can easily assess the overall budget health based on remaining funds and expiration times.
- The progress bar offers a quick visual indicator of budget utilization.

**Use Case 2: Budget Card Details**

**Main Success Scenario (Building upon Use Case 1):**

1. The user clicks on a specific budget card in the "Available Budgets" widget.
1. Clicking the card displays a detailed view for that budget on a separate page.
1. The detailed view includes all information displayed on the card (budget name, department, time left, remaining budget, period) with potentially additional details like:
   1. Budget Description (optional)
   1. Planned vs. Actual Costs (optional)
   1. Cost Breakdown by Category (optional)
   1. Link to view historical cost data (optional)
1. (Optional) If overspending is detected (remaining budget is negative), the detailed view prominently displays a visual warning message like "Overspending."

**Benefits:**

- Provides deeper insights into individual budget details for informed decision-making.
- Allows users to analyze spending patterns and identify potential cost optimization opportunities.
- Alerts users to overspending situations requiring immediate attention.

