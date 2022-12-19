---
layout: default
title: Payroll Garnishments
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 5
---
Use this process to scan documents to the workbasket folder.

- For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Datacap Main Page.
- Job Monitor page will open, click the Scan icon to open the NScan page for scanning documents.
    ![image](https://media.github.ibm.com/user/376381/files/7689b280-c5b9-11ec-930b-1865265c0123)

**Source:**
- On the NScan page, use the Source drop-down to select the Scanner.
- On the Barcode separator sheet (created outside the system), Document Type ID value included in barcode should be “0046.00” for Garnishments.
![image](https://media.github.ibm.com/user/376381/files/c8810700-c5be-11ec-9f23-afe6c071e95b)

**Process Name:**
- Select the required process Name for the relevant Barcode separator Sheet.
- Click the Scan button, document will be scanned.
![image](https://media.github.ibm.com/user/376381/files/d6cf2300-c5be-11ec-8ffe-763caf3c547a)
- Click on Submit, Batch will be created if correct Process Name is selected and relevant Barcode separator sheet is scanned.
![image](https://media.github.ibm.com/user/376381/files/de8ec780-c5be-11ec-8189-1bc80ffda197)
- QueueID will be unique datacap-generated incremental number, which can be viewed at the first column of ICN Datacap Job Monitor.
![image](https://media.github.ibm.com/user/376381/files/e6e70280-c5be-11ec-8011-6e9ec16fc512)

**Verify panel:**
- When the status is shown as pending, double click on the Batch to open the verify page.
![image](https://media.github.ibm.com/user/376381/files/f1090100-c5be-11ec-993a-261ac1933f3a)

- Verify panel should open in Page View -> Field Details -> Batch structure View
- All mandatory and editable fields will be displayed in the field details section.
- Click On “Run Validations”.
![image](https://media.github.ibm.com/user/376381/files/fa926900-c5be-11ec-943e-3ebe5b9484fb)
- If the Field Validation is successful, message will display as “Task profile succeeded”.
- For More details refer to the [Field Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section.
- Click on Submit button.
![image](https://media.github.ibm.com/user/376381/files/05e59480-c5bf-11ec-82e9-8d539ee0f632)
- Document will be exported to Payroll Garnishments FileNet Workbasket.
![image](https://media.github.ibm.com/user/376381/files/10079300-c5bf-11ec-8266-bef2fe040f5a)

**Export To FileNet:**
- Payroll Garnishments FileNet Workbasket.
- For more details refer [Edit document from Workbaskets](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/EditDocumentFromWorkbaskets.html).
![image](https://media.github.ibm.com/user/376381/files/1a299180-c5bf-11ec-867d-0dfbaac62e3d)

