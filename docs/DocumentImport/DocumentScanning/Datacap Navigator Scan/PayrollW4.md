---
layout: default
title: Payroll W4
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 6
---
Use this process to scan documents to the workbasket folder.

- For Login information, refer to  [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Datacap Main Page.
- Job Monitor page will open, click the Scan icon to open the NScan page for scanning documents.
![image](https://media.github.ibm.com/user/376381/files/7689b280-c5b9-11ec-930b-1865265c0123)

**Source:**
- On the NScan page, use the Source drop-down to select the Scanner
- On the Barcode separator sheet (created outside the system), Document Type ID value included in barcode should be “0008.00” for W4.
![image](https://media.github.ibm.com/user/376381/files/ae93f400-c5bf-11ec-9f39-b29f87b738bc)

**Process Name:**
- Select the required process Name for the relevant barcode separator Sheet.
- Click On Scan button, document will be scanned.
![image](https://media.github.ibm.com/user/376381/files/b81d5c00-c5bf-11ec-922d-b2a4e0cbe564)
- Click on Submit, Batch will be created if correct Process Name is selected and relevant Barcode separator sheet is scanned.
![image](https://media.github.ibm.com/user/376381/files/c10e2d80-c5bf-11ec-9579-66b8084567d9)
- QueueID will be the unique dataCap-generated incremental number, which can be viewed at the first column of ICN DataCap Job Monitor.
![image](https://media.github.ibm.com/user/376381/files/c9666880-c5bf-11ec-80e8-5d58044ffc83)

**Verify Panel:**
- When the status is shown as pending, double click on the Batch to open the verify page.
![image](https://media.github.ibm.com/user/376381/files/d2efd080-c5bf-11ec-9a0e-fe2a944d5d15)
- Verify panel should open in Page View -> Field Details -> Batch structure View
- All mandatory and editable fields will be displayed the field details section.
- Click On “Run Validations”.
![image](https://media.github.ibm.com/user/376381/files/e307b000-c5bf-11ec-875a-ae4fabe984e0)
- If the Field Validation is successful, message will display as “Task profile succeeded”.
- For more details refer to the [Field Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section
- Click on Submit button.
![image](https://media.github.ibm.com/user/376381/files/edc24500-c5bf-11ec-8a53-43f8c4213357)
- Document will be exported to Payroll W4 FileNet Workbasket.
![image](https://media.github.ibm.com/user/376381/files/f6b31680-c5bf-11ec-9535-d04994298342)

**Export To FileNet:**
- Payroll W4FileNet Workbasket.
- For more details refer [Edit document from Workbaskets](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/EditDocumentFromWorkbaskets.html).
![image](https://media.github.ibm.com/user/376381/files/00d51500-c5c0-11ec-90c2-aadfa1b62a9b)


