**Use Case Of Top Accounts With More Products.**

**Title:** Use Case of Top Accounts With More Products.

**Description:** This use case describes the functionality of Top accounts with more products section within the Cloud Central Dashboard.

**Actors:**

- CEO, CTO, CFO, Cloud Administrator, Cloud Operations Team leads.

**Trigger Point:**

1. The user wants to know about Accounts with more product widget.

**Preconditions:**

1. User must have access permissions to the Cloud Central Dashboard.
1. User must be logged into the AppKube platform.

**Main Flow:**

1. User logs into the AppKube platform using their credentials.
1. After successful login, the user navigates to the reporting module within the AppKube platform.
1. Within the reporting module, the user selects the Cloud Central Dashboard.
1. the user interacts with the Top Accounts with More Products widget, showing that top 5 accounts haves the more number of products compared to all accounts, displayed in a bar chart format.
1. User Clicks on the view details button on the Top Accounts with more Products.
1. User is redirected to an Accounts page.
1. In the top of the page there’s a breadcrumb to go back to the previous pages.
1. There’s a search bar to search for an account with the account name or account id.
1. Displaying a tabular list of accounts which includes details such as 
- Account Name
- Account ID
- Department Name
- Total number of Regions
- Total number of VPC’s
- Total number of Products
- Total number of Services.
1. User clicks on a Products or services to go the particular page.
1. Suppose user clicks on the products, then the user Redirects to the particular account Products page.
1. All products are displayed in tabular Format, and in the top right corner user can switch to the particular category by default all is selected.
1. Table includes the columns such as,
   1. product name
   1. VPC ID
   1. Region
   1. Total number of services
   1. product category.
1. User Clicks on Product Name of the 3-tier.
1. User redirect to the particular product page. 
1. On the 3-tier product page, on the top of the page there’s a breadcrumb to go back to the previous pages.
1. ` `the user see all layers of the product (web layer, app layer, data layer, auxiliary layer) on the left side and overall services of the production stage on the right side. User clicks on ec2 service, which redirects to the particular service list which shows in a tabular format on the bottom of the page. Which includes the following details,
- Instance ID
- Instance type
- Availability zone
- Pricing model
- Adds-on
- Usage hours
- Created on
- Instance State

1. User Clicks on the Instance ID which redirects to the instance page.
1. On the Instance page user sees the breadcrumb to go back to the previous pages.
1. Below the breadcrumb, the user sees the instance details. Where it shows the whole details of the particular instance.
1. Below that, the user sees the CPU utilization, memory utilization, network Inbound and Outbound Traffic, and Disk read and write operation.
1. By default, all graphs show the data of the last one hour and With that user can choose the custom time range to see the data on his/her way.


   ` `<b>User Click on web layer in 17<sup>th</sup> point.</b>

1. User Select the Web layer on the Left side of the page, on the right side according to the layer the services are shown.
1. User selects the EC2 service from the services, and a table of EC2 services is shown at the bottom of the page, displaying
- Instance ID
- Instance type
- Availability zone
- Pricing model
- Adds-on
- Usage hours
- Created on
- Instance State
1. Clicks on the Instance ID which redirects to the instance page.
1. On the Instance page user sees the breadcrumb to go back to the previous pages.
1. Below the breadcrumb, the user sees the instance details. Where it shows the whole details of the particular instance.
1. Below that, the user sees the CPU utilization, memory utilization, network Inbound and Outbound Traffic, and Disk read and write operation.
1. By default, all graphs show the data of the last one hour and With that user can choose the custom time range to see the data on his/her way.

**The user Click on the SOA Product.**

**Normal Flow:**

1. User clicks on the SOA Product, the user is redirected to the SOA product page.
1. On the top of the page there’s a breadcrumb to back to the previous pages..
1. the user see the Business and common services of the product page on the left side and overall services of the production stage on the right side. 
1. On the right side Corner shows the software environment( Production, Staging, Testing, and Development ). By default, the Production stage is selected.
1. The user can select a business or common service, the user selects the business service then the list of modules is displayed, By default first module of the business is selected According to the selection of Service, the right side shows the App service, Data Service and  other Services.
1. The user selects the App Service, then the AWS Services of the App service is displayed in the same widget. Same to all other services.
1. The user selects the EC2 service from the services, a table of EC2 services is shown at the bottom of the page, displaying the Items such as 
   1. Instance ID
   1. Instance type
   1. Availability zone
   1. Pricing model
   1. Usage hours
   1. Adds-on
   1. Created on
   1. Instance State
1. the user clicks on the instance ID, then the user is redirected to the particular instance page.
1. On the Instance page user sees the breadcrumb to go back to the previous pages.
1. Below the breadcrumb, the user sees the instance details. Where it shows the whole details of the particular instance.
1. Below that, the user sees the CPU utilization, memory utilization, network Inbound and Outbound Traffic, and Disk read and write operation.
1. By default, all graphs show the data of the last one hour and With that user can choose the custom time range to see the data on his/her way.

<b>On 3<sup>rd</sup> point User Clicks on the EC2 from the Services of the Production stage.</b>

1. On the right side, overall services of the production stage which shows the services. User clicks on ec2 service from the services, which redirects to the particular service list which shows in a tabular format on the bottom of the page. Which includes the following details,
- Instance ID
- Instance type
- Availability zone
- Pricing model
- Adds-on
- Usage hours
- Created on
- Instance State

1. User Clicks on the Instance ID which redirects to the instance page.
1. On the Instance page user sees the breadcrumb to go back to the previous pages.
1. Below the breadcrumb, the user sees the instance details. Where it shows the whole details of the particular instance.
1. Below that, the user sees the CPU utilization, memory utilization, network Inbound and Outbound Traffic, and Disk read and write operation.
1. By default, all graphs show the data of the last one hour and With that user can choose the custom time range to see the data on his/her way.


**On The top Accounts page User Clicks on the Services.**

**Normal Flow:**

1. User clicks on the services displayed in the table on the accounts page.
1. User is redirected to the services page where all the services are shown in count.
1. There is a search bar to search a service by its name. And on the top of the page, there’s a breadcrumb to go back to the previous pages.
1. User selects the EC2 service from the list of services, which redirects to the list of EC2 services page.
1. On the list of EC2 services page, user can view details of each instance in a tabular method and there’s a search bar to search the instance with the instance Id, the table includes the following column, 
   1. Instance ID
   1. Instance Type
   1. Availability Zone
   1. Product Name
   1. Adds-on
   1. Created on
   1. Usage hours
   1. Instance State
1. User can click on Instance ID to view details of a particular instance, which redirects them to the single instance page.
1. On the Instance page user sees the breadcrumb to go back to the previous pages.
1. Below the breadcrumb, the user sees the instance details. Where it shows the whole details of the particular instance.
1. Below that, the user sees the CPU utilization, memory utilization, network Inbound and Outbound Traffic, and Disk read and write operation.
1. By default, all graphs show the data of the last one hour and With that user can choose the custom time range to see the data on his/her way.


