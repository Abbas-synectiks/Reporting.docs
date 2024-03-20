
![](Aspose.Words.9fef2486-5868-4aa6-bfc8-1edcbe9323ca.001.png)

**Use Case: Create Invoice - Multi-step Form**

**Description:**  This use case outlines the process for users to create invoices efficiently through a multi-step form within the "Create Invoice" dashboard.

**Actors:** Authorized Users (with permission to create invoices).

**Triggers:** Requirement to generate an invoice for consumed cloud services within the organization.

**Precondition:** The user possesses appropriate permissions following industry-standard access controls to access the "Create Invoice" dashboard.

**Postcondition:** The user successfully generates an invoice with the specified details, conforming to industry standards.


**Normal Flow:**

The authorized user logs into the system and navigates to the "Create Invoice" dashboard.

On the dashboard, the user encounters the title "Create Invoice" and a step indicator displaying three sequential steps:

a. "Step 1: Add OU."

b. "Step 2: Add Project & Services."

c. "Step 3: Payment and Date."

**In Step 1: Add OU:**

a. The user inputs the organization's name in the "Organization Name" text field, conforming to data integrity standards.

b. The user selects the department from the "Select Department" dropdown menu.

c. The user initiates progression to the next step by clicking the "CONTINUE" button.

**In Step 2: Add Project & Services:**

a. The user selects compute, storage, and network services.

b. The user chooses a product from the "Select Product" dropdown menu.

c. The user can navigate back to the previous step using the "BACK" button, maintaining user-friendly interactions.

d. The user proceeds to the next step by clicking the "CONTINUE" button, ensuring the logical flow of the process.

**In Step 3: Payment and Date:**

a. The user selects the "Invoice Issuing Date" and "Invoice Expiration Date".

b. The user can navigate back to the previous step using the "BACK" button, maintaining user-friendly interactions.

c. The user finalizes the form submission by clicking the "CONTINUE" button, confirming the completion of the invoice create system displays a completion screen featuring a green checkmark and the message "Completed!! Invoice Created Successfully!!," ensuring a clear indication of Invoice created. 

b. The user is presented with buttons for "HOME" to return to the main dashboard and "CONTINUE" for further actions, following a standard user interface pattern

![](Aspose.Words.9fef2486-5868-4aa6-bfc8-1edcbe9323ca.002.jpeg)


**Normal Flow:**

The user logs into the system and navigates to the Invoice Management interface.

The interface displays back navigation, allowing the user to return to the previous step ("<----- create invoice").

**The user can perform various actions using buttons:**

**Delete:** Removes the selected invoice from the system.

**Edit:** Opens the invoice for editing, redirecting the user to a multi-step form for modification.

**Send:** This action sends the invoice to the relevant departments

**The Invoice Details section provides comprehensive information:**

Invoice Type: CHARGEBACK INVOICE

Invoice Number: 1806

Date Issued: 30th, 2023

Date Due: 03 JAN, 23

Account ID: 22222

Billing Period: January 1 - January 30, 2023

**Summary Section:**

AWS Service Charges: $12,800

Charges: $10,000

Tax: $0.00

**Total for this invoice: $12,800**

**Detailed Breakdown: list of all cloud services.** 

EC2: $1,800

S3: $2,500

RDS etc… 

If the system encounters errors during action execution (delete, edit, send), the user receives appropriately formatted error messages.

If the user has insufficient permissions, an access denied message is displayed, adhering to security protocols.





![](Aspose.Words.9fef2486-5868-4aa6-bfc8-1edcbe9323ca.003.jpeg)



**Normal Flow:**

1) **Log in and Navigate:**

`             `The user logs into the system and navigates to the "Chargeback Dashboard."

1) **Top Right Corner:**

`              `A prominent "Back to Home" button is displayed.

`              `Clicking it redirects the user to the main dashboard, ensuring seamless navigation.

1) **Invoice Status Cards:**

`             `Three "Invoice Status Cards" provide real-time updates on invoice statuses:

`             `Paid: Displays the number of successfully paid invoices.

`             `Dispute: Indicates the count of invoices currently in dispute.

`             `Pending: Reflects the number of invoices awaiting processing or approval.

1) **History of Invoices:**

`             `Below the cards, the user explores the "History of Departments" section.

`             `Each entry includes the department name, associated invoice records, and relevant historical data.

**Alternative Flow:**

**Error Handling:**

If the system encounters errors during data retrieval or card updates, the user receives appropriately formatted error messages.

**Permission Issue:**

If the user has insufficient permissions, an access denied message is displayed when attempting to access specific sections, adhering to security protocols.


