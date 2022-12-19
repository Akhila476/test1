---
layout: default
title: Verify Stage
parent: Datacap Navigator Scan
grand_parent: Document Scanning
nav_order: 1
---
## Table of contents
{: .no_toc .text-delta }

- TOC
{:toc}

---
## Verify Stage

- After completing the steps outlined in the [Physical Scan](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/) section and clicking Submit, it will navigate to Job Monitor page, it will take few minutes for the batch to move to verify stage.
- When the status column changes to pending, double click on the Batch to open the Verify panel.
![image](https://media.github.ibm.com/user/369573/files/34c9bf00-cbec-11ec-99e2-1db48edfe4ce)
- Verify panel opens with three sections:  1.Page View, 2.Field Details, 3.Batch Structure View.
- All mandatory and editable fields will be displayed in the Field Details section.
![image](https://media.github.ibm.com/user/369573/files/6f335c00-cbec-11ec-9774-df4438f9230a)
- The document should identify the pages: Main Page and Trailing Pages for the selected Process
- In the Batch Structure view, user can view the Main Page, Trail Page, and Status column indicates if Problem is detected and document is not in proper format and will not be submitted.
![image](https://media.github.ibm.com/user/369573/files/8114ff00-cbec-11ec-97ef-17b42382e01e)
- In Batch Structure view status should be “Ok” for each and every document.
- Click **Run Validations** button, see [Field Validation](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#field-validations) section
- If the Field Validation is successful, message will display as “Task profile succeeded”.
- Click Submit button to complete process.
![image](https://media.github.ibm.com/user/369573/files/9a1db000-cbec-11ec-8be5-362bc2a5545f)


|Property Name(Fields)|Mandatory|Drop Down (Choice list)|Auto-Populate Fields|Field Editable|Read Only|
---|---|---|
|Barcode|yes|||yes||
|CNUM|yes|||yes||
|Document Date Datede|yes|||yes||
|Document Type ID|yes|||yes||
|Business Unit|yes|yes|yes||yes|
|Capture Source|yes||yes|yes||
|Document Type|yes|yes|yes||yes|
|Country|yes|yes|yes||yes|
|Page No|yes||yes||yes|
|Scan User|yes||yes||yes|
|Capture Date|yes||yes||yes|
|Scanner No|||||yes|
|Source System|||yes|yes||
|Entity||||yes||
|Doc No|||yes||yes|
|Completed Date||||yes||


## Mandatory Fields

- Mandatory fields are displayed with a red asterisk.
- Mandatory fields should not be empty.                          
- For Example: CNUM - TESTCM897
![image](https://media.github.ibm.com/user/376381/files/b4272380-c62b-11ec-93b8-e8002aadfcfe)

## Auto-Populate Fields
- Auto populated fields are pre-populated.  
- **For Example** , Capture Date will auto populate the field. The Capture Date validation is pre-populated with current date & time and will be read-only once item type created. 
![image](https://media.github.ibm.com/user/376381/files/d3be4c00-c62b-11ec-8392-e4a78ffa79c3)

## Field Validations
- As part of the [Verify Stage](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#verify-stage), click the **Run Validations** button to check field validations.  Validation messages will be displayed for all mandatory fields.
- If the Field Validation is successful, message will display as “Task profile succeeded”.
- Then click **Submit** to complete the process.
![image](https://media.github.ibm.com/user/369573/files/30ea6c80-cbed-11ec-99b1-f4e6c0a1edb6)
![image](https://media.github.ibm.com/user/369573/files/3cd62e80-cbed-11ec-91e0-24a1cce0eff2)
- If the Fields values are invalid, validation message displayed for mandatory fields.
- The field validations will be different for item types.
![image](https://media.github.ibm.com/user/369573/files/4fe8fe80-cbed-11ec-8e5f-80d7bdd7d2de)

### *Barcode Validation*
- Barcode Field is Mandatory.
- Barcode field is the stored and parsed to the following fields
    1. CNUM
    2. Document Date
    3. Document Type ID
    4. Business Unit

    **Example:**

    |Property Name|Property Value|Populated Barcode value|
    ---|---|---|
    |Barcode|1234567890420220012.00P|1234567890420220012.00P|
    |CNUM|123456789|123456789|
    |Document Date|4/20/2022 (MM/dd/yyyy)|042022 (MMddyy)|
    |Document Type ID|0012.00|0012.00|
    |Business Unit |Payroll|P|

- Select Run Validations. If all the validations are successful click Submit
- Note:  Error message may display if the Barcode is modified and does not match the scanned document.
![image](https://media.github.ibm.com/user/376381/files/a02ff180-c62c-11ec-97e2-45c754158853)
![image](https://media.github.ibm.com/user/376381/files/a756ff80-c62c-11ec-9c2e-59e348de558a)

### *Document Date convert string to date Validation*
- Document Date will be parsed from the Barcode.
- Verify the document date field is in MM/dd/yyyy format.
![image](https://media.github.ibm.com/user/376381/files/b9d13900-c62c-11ec-956d-01e7493ed9a0)
![image](https://media.github.ibm.com/user/376381/files/c05fb080-c62c-11ec-9ee2-b7b15e6ba363)

### *Business Unit (formerly ExpCode) Validation*
- Business Unit field value "P" from Datacap processing will be displayed as "Payroll" in the properties. 
- This value P will be included in the barcode, as last character:  9999998970706210045.00P.
![image](https://media.github.ibm.com/user/376381/files/dc635200-c62c-11ec-9e1d-8e4e081e9d19)

### *DocumentType ID (Expense Amt value)*
- Document Type ID will be parsed from the Barcode and set based on the selected Process Name, DocumentType ID value will be auto populated.
- For more details of the document Type ID and document type refer below table

|Document Type ID (Pay Code)|Document Type Description (Imaging Code)|
:---|:---|:---|
|0001.00|PAY – Payments|
|0002.00|TCS - Timecards|
|0003.00|401 – Stock|
|0004.00|TDS – TDSP / ETDSP|
|0006.00|BND – Bonds|
|0007.00|W2S – W2’s|
|0008.00|W4S – W4’s and W4 Mandates|
|0009.00|MST – Misc Taxes|
|0012.00|CER – Separations, LOA, Commissions, 36 Month Average|
|0013.00|IAP – Intl. Payroll to transfers on / off|
|0014.00|OVP – Overpayments|
|0017.00|WAG – Wage Verification|
|0018.00|DED – Deductions|
|0019.00|SUB – Subpoenas|
|0020.00|DEC – Deceased Employees|
|0021.00|DTA – Dual Temporary Assignments|
|0022.00|ESC – Escalations|
|0024.00|WOK – Workman’s Comp|
|0025.00|MIL – Military Leave|
|0026.00|ADP – Adoption Assistance|
|0027.00|IPM – Investment Plan Manager|
|0028.00|S&A – Sickness & Accident|
|0029.00|Clericals|
|0030.00|RST – Restricted Stock|
|0031.00|Clericals|
|0032.00|ACT – Accounting|
|0033.00|BKG – Banking|
|0034.00|UCW – Unclaimed Wage|
|0035.00|BLU – Blue Chips|
|0036.00|OPT – Stock Options|
|0037.00|TACRC – Quarterly Tax Filing & Amendments|
|0038.00|Clericals|
|0039.00|Clericals|
|0040.00|999 – Unknown or Ineligible|
|0041.00|Daily Tieouts|
|0042.00|Weekly Tieouts|
|0043.00|Semi Monthly Tieouts|
|0044.00|Monthly Tieouts|
|0045.00|Quarterly Tieouts|
|0005.00|Clericals|
|0010.00|Clericals|
|0011.00|Clericals|
|0016.00|Clericals|
|0023.00|Clericals|
|0015.00|Clericals|
|0046.00|Garnishments|

![image](https://media.github.ibm.com/user/376381/files/eedd8b80-c62c-11ec-98a8-685804545238)
![image](https://media.github.ibm.com/user/376381/files/f7ce5d00-c62c-11ec-9eb2-e5529f72ceec)


### *CNUM Validation*
- The CNUM field will be parsed from the Barcode, and the the starting 9 digits of Barcode value: 9999998970706210045.00P
- Valid CNUM will contain 0-9 characters. CNUM is a combination of digits and alphabets.
![image](https://media.github.ibm.com/user/376381/files/58639700-c639-11ec-9510-dc4d6eaa17a3)
![image](https://media.github.ibm.com/user/376381/files/62859580-c639-11ec-90e2-2da31a5e6308)

### *Capture source Validation*
- Check capture source field.
- As source of the document is scan, Capture source field value will be auto populated as Scan.
![image](https://media.github.ibm.com/user/376381/files/7630fc00-c639-11ec-885a-6a2f53bb6054)
![image](https://media.github.ibm.com/user/376381/files/7c26dd00-c639-11ec-9990-1ac146246b43)

### *Source system validation*
- Check Source system field.
- Source system field will be auto populated as Scan@GEJSP.
![image](https://media.github.ibm.com/user/376381/files/919c0700-c639-11ec-9114-da0752feafec)
![image](https://media.github.ibm.com/user/376381/files/ac6e7b80-c639-11ec-8411-f7cf676945eb)

### *Entity Validation*
- Check Entity field
- Entity field will be auto populated and editable as IBM.
![image](https://media.github.ibm.com/user/376381/files/bb552e00-c639-11ec-9807-6de2eef420bc)
![image](https://media.github.ibm.com/user/376381/files/c14b0f00-c639-11ec-86d1-c951835312d3)

### *Country Validation*
- Check country value field
- Country value will be set based on the last 3 characters of CNUM.
- Possible country values are USA.
- Country field is read-only.
![image](https://media.github.ibm.com/user/376381/files/d45ddf00-c639-11ec-9b94-4f6406953870)

### *Page no Validation*
- Check Page No field.
- Page No field will be auto populated according to the no of pages in the batch.
![image](https://media.github.ibm.com/user/376381/files/e8a1dc00-c639-11ec-8edd-b8ebc3ceb3c9)

### *Scanner No validation*
- Check the Scanner No. field.
- Scanner No field will be auto populated.
![image](https://media.github.ibm.com/user/376381/files/01aa8d00-c63a-11ec-8e10-3028543ec6df)

### *Doc No validation*
- Check the Doc No. field.
- The Doc No field as the Queue ID as displayed on the Job Monitor screen.
- Select Run Validations and further click on submit.
![image](https://media.github.ibm.com/user/376381/files/19821100-c63a-11ec-9a6b-7f1c4a6adcb1)
![image](https://media.github.ibm.com/user/376381/files/2141b580-c63a-11ec-9550-9e59207da754)

### *Scan User Validation*
- Check Scan User field.
- The Scan User is the logged in User ID ( Email IDExample:- User@in.ibm.com).
![image](https://media.github.ibm.com/user/376381/files/31f22b80-c63a-11ec-9b50-94ef8fe69f78)

### *Document Type Validation*
- Check Document Type field.
- Based on the document type ID, the document type field will auto-populate, document type should match with the document type ID.
- Document Type is read-only.
- Example Document Type ID:-0046.00,Document Type: Payroll Garnishments.
- For more details refer [DocumentType ID(Expense Amt value)](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/DocumentScanning/Datacap%20Navigator%20Scan/VerifyStage.html#documenttype-id-expense-amt-value).
![image](https://media.github.ibm.com/user/376381/files/49311900-c63a-11ec-9d37-4aa22e954efc)
![image](https://media.github.ibm.com/user/376381/files/50f0bd80-c63a-11ec-8a42-d2ee22757b7b)

### *Capture Date Validation*
- Check the Capture Date.
- Capture Date will be auto populated with current date.
- Capture Date will be of the format mm/dd/yyyy HH:mm:ss (ie. 04/10/2022 09:04:47)
![image](https://media.github.ibm.com/user/376381/files/65cd5100-c63a-11ec-8409-4757eeed8844)

### *Completed Date validation*
- Check the Completed Date.
- Completed date will be initially empty.
- If needed, User can manually enter the value for the completed date in the format MM/dd/yyyy.
![image](https://media.github.ibm.com/user/376381/files/7d0c3e80-c63a-11ec-98e8-24b2b624239a)

















