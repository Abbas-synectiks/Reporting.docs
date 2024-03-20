**Use Case Of AWS Services.**

![](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.001.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.002.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.003.jpeg)

![A screenshot of a computer

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.004.jpeg)

![A screenshot of a phone

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.005.jpeg)

![A screenshot of a graph

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.006.jpeg)

![A screenshot of a graph

Description automatically generated](Aspose.Words.e07d1a03-0db4-49e8-a413-3ca192830d30.007.jpeg)

**Title:** AWS Service Management Use Case

**Actors:**  CEO, CTO, CFO, Cloud Administrator, Cloud Operations Team leads.

**Description:** This use case Describes the process for users to manage AWS services within the Cloud Central Dashboard of the AppKube platform. Users can access a list of AWS services from the Cloud Summary widget and top-used services, navigate through specific service details such as EC2 instances, and monitor utilization metrics for individual instances.

**Trigger Points:**

1. If the user wants to see a single service from the overall services.

**Precondition:**

1. User must have access permissions to the AppKube platform.
1. User must be authorized to access the Cloud Central Dashboard.

**Main Flow:**

1. User logs into the AppKube platform using their credentials.
1. User navigates to the Cloud Central Dashboard within the reporting module.
1. User clicks on the total number of AWS services displayed in the Cloud Summary widget, or user click the view details (CTA) of top used services, which redirects them to the list of services page.
1. User selects the EC2 service from the list of services, which redirects them to the list of EC2 services page.
1. On the list of EC2 services page, user can view details of each instance in a tabular method, the table includes, 
   1. Instance ID
   1. Instance Type
   1. Availability Zone
   1. Department Name
   1. Product Name
   1. Instance State
   1. Usage hours
   1. Add-on
   1. Overall Status of the instance.
1. User can click on Instance ID to view details of a particular instance, which redirects them to the single instance page.
1. On the single instance page, user can view information about the current instance on the left side and recommendations on the right side.
1. User can click on CPU, memory, storage, or network utilization at the bottom left side of the page to view utilization graphs on the right side. By default, CPU utilization is selected.

**Post Condition:**

1. User successfully navigates through AWS service lists and instance details, gaining insights into various aspects of service management within the Cloud Central Dashboard.
1. User may take further actions based on the insights obtained from service details, such as optimizing resources or making recommendations.

**Alternative Flow:**

1. If the user encounters any issues accessing the Cloud Central Dashboard or navigating through service details, then the user Can’t see the details of the service.

