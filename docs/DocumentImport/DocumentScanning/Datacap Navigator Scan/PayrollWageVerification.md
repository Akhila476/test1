---
layout: default
title: Payroll Wage Verification
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 3
---

Use this process to scan documents to the workbasket folder.

- For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Datacap Main Page.
- Job Monitor page will open, click the Scan icon to open the NScan page for scanning documents.
    ![image](https://media.github.ibm.com/user/376381/files/7689b280-c5b9-11ec-930b-1865265c0123)

**Source:**
- On the NScan page, use the Source drop-down to select the Scanner
- On the Barcode separator sheet (created outside the system), Document Type ID value included in barcode should be “0017.00” for Wage Verification.

**Process Name:**
1.	Select the required process Name for the relevant Barcode separator Sheet.
2.	Click On Scan button, document will be scanned.
![image](https://media.github.ibm.com/user/376381/files/c9179e80-c5ba-11ec-9364-2be9996692cb)
3.	Click on Submit, Batch will be created if correct Process Name is selected and relevant Barcode separator Sheet is scanned.
![image](https://media.github.ibm.com/user/376381/files/d6cd2400-c5ba-11ec-97da-d9f71c927542)
4.  QueueID will be unique datacap-generated incremental number, which can be viewed at the first column of ICN Datacap Job Monitor.
![image](https://media.github.ibm.com/user/376381/files/ee0c1180-c5ba-11ec-9def-9dc236b9a430)


**Verify panel:** 
- When the status is shown as pending, double click on the Batch to open the verify page.
![image](https://media.github.ibm.com/user/376381/files/78547580-c5bb-11ec-9783-af4465f9a60b)
- Verify panel should open in Page View -> Field Details -> Batch structure View
- All mandatory and editable fields will be displayed in the field details section.
- Click On “Run Validations”.
- For More details refer to the [Field Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section.
![image](https://media.github.ibm.com/user/376381/files/9d48e880-c5bb-11ec-854a-d0fe1e90dd4e)
- If the Field Validation is successful, message will display “Task profile succeeded”.
- Click on Submit button.
![image](https://media.github.ibm.com/user/376381/files/ab970480-c5bb-11ec-9562-bbd371ea5e02)
- Document will be exported to Payroll Wage Verification FileNet Work basket.
![image](https://media.github.ibm.com/user/376381/files/bea9d480-c5bb-11ec-9a30-33faa41c7573)

**Export To FileNet**
- Payroll Wage Verification FileNet Workbasket.
- For more details refer [Edit document in from Workbaskets](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/EditDocumentFromWorkbaskets.html).
![image](https://media.github.ibm.com/user/376381/files/de40fd00-c5bb-11ec-96c4-c33513d6643a)




