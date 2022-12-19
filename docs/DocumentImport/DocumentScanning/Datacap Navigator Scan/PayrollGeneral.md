---
layout: default
title: Payroll General
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 7
---

Use this process to scan documents to the repository.

- For Login information, refer to  [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Datacap Main Page.
- Job Monitor page will open, click the Scan icon to open the NScan page for scanning documents.
![image](https://media.github.ibm.com/user/376381/files/7689b280-c5b9-11ec-930b-1865265c0123)

**Source:**
- On the NScan page, use the Source drop-down to select the Scanner
- On the Barcode separator sheet (created outside the system), Document Type ID value included in barcode should be a valid value excluding Workbasket identifiers.  Excluded values:  0008.00, 0017.00, 0033.00, 0046.00
- For more details refer [Datacap Navigator Scan(NScan)](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/)

**Process Name:**
- Select the required process name for the relevant Barcode separator sheet.
- Click On Scan button, document will scan.
![image](https://media.github.ibm.com/user/376381/files/9cff1c00-c5c0-11ec-957c-809523fa6afc)
- Click on Submit, Batch will be created when user selects the correct Process Name and scan the relevant Barcode separator sheet.
![image](https://media.github.ibm.com/user/376381/files/a5575700-c5c0-11ec-8a8e-899e76179599)
- QueueID will be unique datacap-generated incremental number, which can be viewed at the first column of ICN Datacap Job Monitor.
![image](https://media.github.ibm.com/user/376381/files/ae482880-c5c0-11ec-880a-11729779db94)

**Verify Panel:**

- When the status is shown as pending, double click on the Batch to open the Verify page.
![image](https://media.github.ibm.com/user/376381/files/b7d19080-c5c0-11ec-94f7-209a11d7c10b)
- Verify panel should open in Page View -> Field Details -> Batch structure View
- All mandatory and editable fields will be displayed the field details section.
- Click On “Run Validations”.
![image](https://media.github.ibm.com/user/376381/files/c15af880-c5c0-11ec-91f8-96e21fb4cb37)
- If the Field Validation is successful, message will display as “Task profile succeeded”.
- For More details refer to the [Field Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section.
- Click on Submit button.
![image](https://media.github.ibm.com/user/376381/files/cae46080-c5c0-11ec-9ba7-0eb3797bed56)
- Document should Export to the FileNet repository these documents can be view through the document search
- For more details refer [Document Search](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/DocumentSearch.html).
![image](https://media.github.ibm.com/user/376381/files/d6d02280-c5c0-11ec-94f7-ea8d6f8a4154)





