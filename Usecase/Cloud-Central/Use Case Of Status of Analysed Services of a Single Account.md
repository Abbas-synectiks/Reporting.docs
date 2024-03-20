**Use Case Of Status of Analysed Services of a Single Account.**

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.001.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.002.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.003.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.004.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.005.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.006.jpeg)

![A screen shot of a graph

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.007.jpeg)

![A screenshot of a graph

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.008.jpeg)

![A screenshot of a graph

Description automatically generated](Aspose.Words.98001b88-84fa-4889-86b2-e6022b4831bc.009.jpeg)

**Title:** Use Case of Status of Analysed Services of a single Account

**Actors:**  CEO, CTO, CFO, Cloud Administrator, Cloud Operations Team leads.

**Description:** This use case describes the process for users to manage and analyze the status of analysed services within the single account dashboard of the AppKube platform. Users can access insights into the optimization status of various services, categorized into savings, optimal, risk, and not analysed stages.

**Trigger Points:**

1. If the User want to know the status of the services of a particular single account

**Precondition:**

1. User must have access permissions to the AppKube platform.
1. User must be authorized to access the Cloud Central Dashboard.

**Main Flow:**

1. In a single account dashboard shows the status of analysed services in donut chart
1. which displays the services categorized into savings, optimal, risk, and not analysed stages.
1. User clicks on any of the status (savings, optimal, risk, or not analysed), redirecting them to the respective state page.
1. On the status page, user views a table and top left side corner displaying services in that particular state. By default, first service is selected.
1. The table includes columns such as 
   1. Instance ID
   1. Availability Zone
   1. Account ID
   1. Instance Type
   1. Optimization Type
   1. Recommendation Reason
   1. Recommended Instance Type
   1. Performance Effect
   1. Estimated Monthly Savings
   1. Overall Status.
1. User can click on an Instance ID to view details of a particular instance, which redirects them to the single instance page.
1. On the single instance page, user views information about the current instance on the left side and recommendations on the right side.
1. User can click on CPU, memory, storage, or network utilization at the bottom left side of the page to view utilization graphs on the right side. By default, CPU utilization is selected.

**Post Condition:**

1. User successfully reviews the status of analysed services, gaining insights into the optimization status of various services within the Cloud Central Dashboard.
1. User may take further actions based on the insights obtained, such as optimizing resources, addressing risks, or initiating analysis for not analysed services.

**Alternative Flow:**

1. If the user encounters any issues accessing the Cloud Central Dashboard or viewing the status of analysed services, then the user cannot see the details of the services.

