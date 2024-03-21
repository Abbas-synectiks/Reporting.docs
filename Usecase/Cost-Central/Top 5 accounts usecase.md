**USE CASE: COST OF TOP 5 ACCOUNTS**



**Use Case: Top 5 Accounts Widget**

**Actor:** Cloud Administrator, Cloud Operations Team, Financial Analyst

**Goal:** To monitor and analyze Cost of Top Accounts of cloud services across different categories within the cloud environment using the Cost of Top Accounts widget.

**Preconditions:** The user must have access to the cloud management platform and appropriate permissions to view usage data.

**Main Flow:**

1\.The user logs in to the cloud management platform and navigates to the dashboard.

2\. On the dashboard, the user locates the Cost of Top accounts widget, which displays graphical representations of the Top cost consuming accounts or departments.

4\. At the top-right corner of the widget, there is a "View Details" button.

5\. Upon clicking the "View Details" button, the user is directed to the detailed report page.

6\.The detailed page provides insights into accounts which are using more services than usual.

7\. The cost of top accounts detail page includes

- Two buttons on the top right corner of the screen

  **Filter Button:**

  - When clicked, the filter button displays options including pre-selected options called All regions, All VPCs , All Accounts , All Tagnames and All products.
  - The "All regions" option consists of sub-options listing all the regions from where the compute service is being used.
  - The "All departments" option consists of sub-options listing all the departments utilizing the compute service.
  - The "All products" option consists of sub-options listing all the products using compute services.

**Duration Button:**

- When clicked, the duration button displays options for selecting the duration: 1 day, 1 week, 1 month, quarter, half-year, and annual.

Below the buttons there are,

8\. four cards, showing the following information:

- This month spend
- Month to date spend
- Forecasted spends
- Average daily spend

9\. Below there is information table showing data. The data table shows information of Account Name, Account Id, Organization Unit, Current Month Spend, Last Month Spend, Spending Variance, Average daily spend and Action.

10\. Upon clicking the view more link in actions tab, the system takes you to account detail page. Where the details of the account using all the services are shown. 

**Alternative Flow:**

- If the user selects some other widget on the overview dashboard, the corresponding data is displayed.
- If the user selects the storage tab or the other tabs available. The data will be displayed according to the tab the user selected.
- If the user encounters an error while accessing the cost of top accounts widget, an error message is displayed, suggesting troubleshooting steps or recommending contacting support for assistance.

**Post conditions:**

- The user gains insights into the Costings of top accounts using cloud services with the help of Appkube in the AWS environment.
- The user can analyze the Costings of top accounts using cloud services, identify areas for cost optimization, and make informed decisions to manage potential savings efficiently.

**Success Scenario:**

- The user successfully accesses to the Costings of top accounts widget, navigates to the detailed page, customizes the view using filter and duration options, and analyzes potential savings.

**Failure Scenario:**

- The user encounters an error while accessing the Costings of top accounts widget or detailed pages, hindering their ability to analyze Costings of top accounts and make informed decisions. The user may need to retry accessing the widget or seek assistance from the support team to resolve the issue.


**Use Case: COST OF SERVICES IN IT ACCOUNT**

**Title:** Exploring Services Details for IT Account

**Introduction:** Upon clicking the 'View More' button for the ‘IT Account’ in the 'Cost of Top 5 Account' widget, users are directed to a new page providing a detailed breakdown of services used in that specific Account.

**Actors:**

- Cloud Administrators
- Financial Analysts
- Stakeholders responsible for cost management

**Goals or Objectives:** The primary goal is to allow users to delve deeper into the cost breakdown of services within the selected region.

**Preconditions:**

- User has accessed the 'Cost of Top 5 Account' widget.
- IT Account is selected as the focus.
- Relevant cloud accounts are integrated with the system.


**Main Flow:**

1. **Page Initialization:**
   1. Users click the 'View More' button for the IT Account.
   1. The page displays information related to services used in the IT Account.



1. **Top Right Corner Buttons:**
   1. **Filter Button:**
      1. Clicking the 'Filter' button opens a popup with multiple dropdowns.
      1. Dropdown options include:
         1. Select all regions.
         1. Select all services.
         1. Select all VPCs.
         1. Select all products.
         1. Select all Account.
      1. By default, the filter is set to 'All' (all services, all VPCs, all regions, all products) except for the Account name, it is selected to ‘IT account’.
   1. **Date Picker Button:**
      1. Clicking the 'Date Picker' button provides a range of pre-selected dates:
         1. Last month
         1. This month
         1. Last quarter
         1. Current quarter
         1. Current year
         1. Last year
      1. By default, it is set to 'This Month.'
1. **Overview Cards:**

   1. Four cards display spendings based on the selected filters:
      1. **Month to Date Spend of All Services:** Shows spending for all services in the IT account for the current month.

        




      1. **Forecasted Spend:** Provides an estimate of the current month's spending for the IT ACCOUNT.
      1. **Last Month Spend:** Displays spending from the previous month for the IT Account.
      1. **Avg Daily Spend:** Calculates the average daily spending for the IT Account.



   1. A table contains the following columns:
      1. **Service Name:** All the services accessed in the IT Account.
      1. **Current Month Spend:** Month To Date spend of that service.
      1. **Last Month Spend:** Total cost incurred on that service in the last month.
      1. **Variance:** Difference between the MTD spend and the last month's spend to date.
      1. **Actions:** Contains a 'View More' link for each service.
1. **View More Link:**
   1. Clicking the 'View More' link in the 'Actions' column directs users to a detailed breakdown page for that service. This page provides further insights into the usage, costs, and other relevant details for the selected service within the IT Account.

**Postconditions:** Users gain a granular understanding of the cost distribution and usage patterns of individual services within the IT Account, facilitating more targeted optimization efforts.

**Success Criteria:**

- Users can seamlessly navigate and interact with the detailed services overview for the IT Account.
- Detailed breakdowns and visualizations provide actionable insights.
- The 'View More' links lead users to in-depth analyses for further investigation at the service level.

**Benefits:**

- Users can analyze spending for individual services within the IT Account.
- The filter and date picker options provide flexibility and customization for focused analysis.
- Overview cards offer a quick glance at key spending metrics.
- The 'View More' link facilitates a deeper dive into each service's details.

**Conclusion:** The detailed services overview for the IT Account empowers users to make informed decisions regarding resource allocation and cost optimization at the service level within their chosen cloud service provider. The combination of filters, date picker, and overview cards enhances the user's ability to conduct a more nuanced analysis for precise cost management.

**THE END**

**Use Case: Detailed Cost Analysis of EC2 Service in  ‘IT Account’**

**Title:** Analyzing EC2 Service Costs in ‘IT Account’

**Introduction:** Upon clicking the 'View More' button for the EC2 Service within the ‘IT Account,' users are directed to a new page that provides a comprehensive breakdown of the cost associated with EC2 instances. This detailed analysis enables users to optimize spending and enhance efficiency.

**Actors:**

- Cloud Administrators
- Financial Analysts
- Stakeholders responsible for cloud cost management

**Goals or Objectives:** Enable users to perform a detailed cost analysis of EC2 instances within the ‘IT Account' allowing for effective optimization and decision-making.

**Preconditions:**

- Users are on the 'Cost of Top 5 Product' page.
- 'View More' button for the 'EC2' Service within the ' IT Account ' is visible.
- Relevant cloud accounts are integrated with the system.
- Data for EC2 instances within the ' IT Account ' is available.

**Main Flow:**



1. **Clicking 'View More' for EC2 Service:**
   1. Users click the 'View More' link for the 'EC2' Service within the 'IT Account.'



1. **Navigating to New Page:**
   1. Users are directed to a new page titled 'EC2 Service Cost Analysis.'
   1. Two buttons on the top right corner: 'Filter' and 'Date Picker.'
1. **Default Filter Settings:**
   1. Upon clicking the 'Filter' button, a popup appears with dropdowns:
      1. 'Select All Regions'
      1. 'Select All Services' (EC2 selected by default)
      1. 'Select All VPCs'
      1. 'Select All Products' (Internal CRM Tool selected by default)
      1. 'Select All Accounts.
   1. Default settings: 'All' for regions, VPCs, Products and  'EC2' for services,  ‘IT Account’ for Accounts. 
1. **Date Picker Options:**
   1. Clicking the 'Date Picker' button reveals pre-selected date ranges:
      1. 'Last Month'
      1. 'This Month' (default)
      1. 'Last Quarter'
      1. 'Current Quarter'
      1. 'Current Year'
      1. 'Last Year'
1. **Overview Cards:**
   1. Five cards display spending details based on the selected filters:
      1. **Total EC2 Instances:** Indicates the total number of EC2 instances, including running, stopped, and terminated, in the selected month.
      1. **Month to Date Spend:** Shows the total spending on EC2 instances for the ‘IT Account’ across all regions in the current month.
      1. **Forecasted Spend:** Provides an estimate of the current month's spending, with a trend compared to last month.
      1. **Last Month Spend:** Displays spending from the previous month, along with a trend compared to the month before.
      1. **Avg Daily Cost:** Calculates the average daily cost of the EC2 Service within the ‘IT Account '
1. **Table: Cost Consumption of EC2:**
   1. A table with 11 columns presents detailed spending information for each EC2 instance:
      1. **Tags:** Tag names of the EC2 instance.
      1. **Instance ID:** Lists the Instance ID.
      1. **Instance Type:** Specifies the type of EC2 instance (e.g., t2.2xlarge, c5.2xlarge).
      1. **Instance Status:** Indicates whether the instance is currently running, stopped, or terminated.
      1. **Pricing Model:** Specifies whether the EC2 instance is On Demand, Spot Instance, or Reserved Instance.
      1. **Availability Zones:** Displays the zone where the instance is located.
      1. **On Demand Cost / HR:** Cost per hour if the instance is On Demand or under a Savings Plan.
      1. **Reserved Instance Cost / HR:** Effective per hour cost if the instance is under a Reserved Instance; null if On Demand.
      1. **Usage Hours:** Total hours the instance has run so far.
      1. **Add-ons:** Additional cost associated with attached EBS, if any; null otherwise.
      1. **Total Spend:** Total cost associated with each EC2 instance.
1. **Search Bar:**
   1. A search bar allows users to search for a specific EC2 instance by ID or tag.
1. **Pagination:**
   1. Pagination with 'Previous Page' and 'Next Page' buttons facilitates navigation through multiple instances.
   1. The center of the screen indicates the current page being accessed.

**Postconditions:** Users gain in-depth insights into the cost breakdown of individual EC2 instances within the ‘IT Account,' supporting informed decision-making and cost optimization efforts.

**Success Criteria:**

- Users can seamlessly navigate and interact with the detailed cost analysis of EC2 instances.
- Overview cards provide a quick summary of key spending metrics for EC2 instances within the ' IT Account '
- The table offers a comprehensive breakdown of spending details for each EC2 instance.
- The search bar facilitates quick identification of specific instances.
- Pagination allows users to navigate through multiple pages of EC2 instances.

**THE END**

