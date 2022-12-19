---
layout: default
title: Payroll Banking
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 4
---

Use this process to scan documents to the workbasket folder.

1.	For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) Section.
2. From the Browse page, click the hamburger icon to expand the menu and select Datacap Main Page.
3. Job Monitor page will open, click the Scan icon to open the NScan page for scanning document.
![image](https://media.github.ibm.com/user/369573/files/e4e4fb00-cbdf-11ec-8236-c0955bb48d6f)

**Source:**
- On the NScan page, use the Source drop-down to select the Scanner
- On the Barcode separator sheet (created outside the system), Document Type ID value included in barcode should be “0033.00” for Banking.

**Process Name:**
- Select the required process Name for the relevant Barcode separator Sheet.
- Click the Scan button, document will be scanned.
    ![image](https://media.github.ibm.com/user/376381/files/bbfbaf00-c5bc-11ec-943d-0feac85398b6)
- Click on Submit, Batch will be created if correct Process Name is selected and relevant Barcode separator sheet is scanned.
    ![image](https://media.github.ibm.com/user/376381/files/cae26180-c5bc-11ec-80d7-babcbd78e18f)
- QueueID will be unique datacap-generated incremental number, which can be viewed at the first column of ICN Datacap Job Monitor.
    ![image](https://media.github.ibm.com/user/376381/files/d9307d80-c5bc-11ec-8bc3-b54b4bec3751)

**Verify panel:**
- When the status is shown as pending, double click on the Batch to open the verify page.
    ![image](https://media.github.ibm.com/user/376381/files/ee0d1100-c5bc-11ec-986c-91b73c3cf8b7)
- Verify panel should open in Page View -> Field Details -> Batch structure View
- All mandatory and editable fields will be displayed in the start of the field details section.
- Click On “Run Validations”.
- For More details refer to the [Field Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section.
    ![image](https://media.github.ibm.com/user/376381/files/04b36800-c5bd-11ec-9392-878608344c44)
- If the Field Validation is successful, message will display “Task profile succeeded”.
- Click on Submit button.
    ![image](https://media.github.ibm.com/user/376381/files/18f76500-c5bd-11ec-97fb-2a7361b71496)
- Document will be exported to Payroll Banking FileNet Workbasket.
![image](https://media.github.ibm.com/user/376381/files/2c0a3500-c5bd-11ec-9281-7e2f67f19209)

**Export To FileNet:**
- Payroll Banking FileNet Workbasket.
- For more details refer [Edit document in from Workbaskets](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/EditDocumentFromWorkbaskets.html).
![image](https://media.github.ibm.com/user/376381/files/47754000-c5bd-11ec-95bf-dfa735e4850c)
