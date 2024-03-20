﻿
**Use Case: Most Used Services Widget**

![](Aspose.Words.951f213f-e838-4784-840d-a47fae17a773.001.png)![](Aspose.Words.951f213f-e838-4784-840d-a47fae17a773.002.png) ![](Aspose.Words.951f213f-e838-4784-840d-a47fae17a773.003.png)![](Aspose.Words.951f213f-e838-4784-840d-a47fae17a773.004.png)![](Aspose.Words.951f213f-e838-4784-840d-a47fae17a773.005.png)

**Use Case: Most Used Services Widget**

**Actor:** CTO, CFO, Cloud Administrator, Cloud Operations Team and Financial Analyst

**Goal:** To monitor and analyze the usage of cloud services across different categories within the cloud environment using the Top Used Services widget.

**Preconditions:** The user must have access to the Appkube and appropriate permissions to view usage data.

**Main Flow:**

1. The user logs in to the cloud management platform and navigates to the dashboard.
1. On the dashboard, the user locates the Top Used Services widget, which displays graphical representations of the most frequently used cloud services.
1. The widget provides a graphical representation, such as a bar chart or pie chart, depicting the usage distribution among the top services.
1. At the top-right corner of the widget, there is a "View Details" button.
1. Upon clicking the "View Details" button, the user is directed to the detailed usage report page.
1. The detailed usage report page provides insights into the usage patterns, trends, and metrics for the top-used services.
1. The top used services detail page includes
1. Two buttons on the top right corner of the screen
   1. **Filter Button:**
      1. When clicked, the filter button displays options including pre-selected options called All regions, All departments, and All products.
      1. The "All regions" option consists of sub-options listing all the regions from where the compute service is being used.
      1. The "All departments" option consists of sub-options listing all the departments utilizing the compute service.
      1. The "All products" option consists of sub-options listing all the products using compute services.
   1. **Duration Button:**
      1. When clicked, the duration button displays options for selecting the duration: 1 day, 1 week, 1 month, quarter, half-year, and annual.

Below the buttons there are,

1. four cards, showing the following information:
   1. Last month spend 
   1. Month-to-date spend
   1. Forecasted spend
   1. Average daily spend
1. Below the cards there is information table showing data of top 10 services used with the heading of the table as Service name, current month spend, last month spend, Variance, average daily spend and actions.
1. when view details is clicked under actions tab, It takes you to a different page. The page displays four (4) cards namely, Total Ec2 instance, Running instance, stopped instances and Terminated instances. Below that there is a detailed cost report of the particular services within a tabular format.
1. The table consists of following Tags, Instance ID, Instance Type, Instance status, Pricing Model, Availability zone, On demand cost / per hour, Reserved Instance / per hour, Usage hours, add-ons, Total spend. And its respective data below in the table.

   **Alternative Flow:**

1. If the user selects some other widget on overview dashboard, the corresponding data is displayed.
1. If the user selects the storage tab or the other tabs available. The data will be displayed according to the tab the user selected.
1. If the user encounters an error while accessing the Spending Overview widget or detailed spending reports, an error message is displayed, suggesting troubleshooting steps or recommending contacting support for assistance.

**Post conditions:**

- The user gains insights into the top 10 used services and patterns across various categories within the AWS environment.
- The user can analyze the top used services effectively, identify areas for cost optimization, and make informed decisions to manage cloud expenses efficiently.

**Success Scenario:**

- The user successfully accesses, the top 10 used services widget, navigates to the detailed top used services reports, customizes the view using filter and duration options, and analyzes spending data to optimize costs effectively.

**Failure Scenario:**

- The user encounters an error while accessing the Spending Overview widget or detailed spending reports, hindering their ability to analyze spending data and make informed decisions. The user may need to retry accessing the widget or seek assistance from the support team to resolve the issue.

