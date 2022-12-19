---
layout: default
title: Upload To Workbaskets
parent: Manual Upload
grand_parent: Document Import
nav_order: 2
---

Please follow below instructions to upload documents into folders (Workbaskets), using Darg & Drop.

- Login into Global EJS Payroll application. Refer [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) for more login details.  
- After Login, by default user should land on the Browse page.
    ![image](https://media.github.ibm.com/user/369573/files/2dfdd500-c578-11ec-8e32-d38156a0becc)
- Expand Global EJS Folder to view Payroll_US Folder
    ![image](https://media.github.ibm.com/user/369573/files/6952d080-c585-11ec-80df-262eb5be36a2)
- Expand Payroll_US folder to view its subfolders
    ![image](https://media.github.ibm.com/user/369573/files/812a5480-c585-11ec-955f-7094c7663900)

    <div class="code-example" markdown="1">
    Note: Users are not authorized to upload documents to ‘Global EJS’ folder and’ Payroll_US folder’, they are only authorized to upload documents to subfolders of the Payroll_US folder.
    </div>
- Open any of the below mentioned Folders, as per the requirement
    1.	Payroll Banking
    2.	Payroll Garnishments
    3.	Payroll W4
    4.	Payroll Wage Verification

    ![image](https://media.github.ibm.com/user/369573/files/c3539600-c585-11ec-8e74-e84bfc689ea7)

- Open the document location on local machine to upload.
    ![image](https://media.github.ibm.com/user/369573/files/d6fefc80-c585-11ec-9d58-a77f0f5cfba5)

- Select and drag the document and drop on the Workbasket folders under Payroll_US
    ![image](https://media.github.ibm.com/user/369573/files/e8e09f80-c585-11ec-96fa-1eb0f99a9115)
- Once dropped, user will see ‘Add Document_screen’
    ![image](https://media.github.ibm.com/user/369573/files/fac24280-c585-11ec-8cfb-1158cbd5957b)
-  Default location of save-in is selected folder name and users are not-authorized to change the save in location

    <div class="code-example" markdown="1">
    **Note**: If user want to change the save-in location, once ‘Add Document’ dialog box shown on UI then user must close the screen by clicking on the ‘cancel’ button and again must drag and drop the document on the any other folder as per the requirement.
    </div>

- File name will be auto populated based on the selected document and will be read-only
    ![image](https://media.github.ibm.com/user/369573/files/1594b700-c586-11ec-95bd-003a741f218a)
- Add Document Template includes 2 tabs
    1. Manual Upload Attributes
    2. Other Attributes
- In ‘Manual Upload Attributes’ tab following details will be populated
- Enter CNUM, Document Date, Document Type ID attributes.
- Ensure the Document Type ID aligns with the Workbasket folder selected.
- Refer to [Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/Validations.html) section before providing values.
- Barcode will be auto populated and concatenated using CNUM, Document Date, Document Type ID, ‘P’ for Business Unit.
- Document Type, Capture Date and Scan User will be set by the system.

    |Property to Enter |Mandatory |Dropdown(ChoiceList)|Property Length |Auto Populate |
    --- | --- | ---|
    |Document Title|||255||
    |CNUM|Yes||9||
    |Document Date|Yes||255||
    |DocumentTypeID|Yes||7||
    |Document Type|Yes|Yes||Yes|
    |Barcode|Yes|||Yes|
    |Capture Date|||||
    |Scan User|Yes||50||
    |Completed Date|||||
   
    <img width="708" alt="image" src="https://media.github.ibm.com/user/369573/files/1b879980-c580-11ec-9e0f-af011e016a6b">
- In ‘Other Attributes’ tab following details will be auto populated

    <div class="code-example" markdown="1">

    |Property to Enter |Mandatory |Dropdown(ChoiceList)|Property Length |Auto Populate |
    --- | --- | ---|
    |Capture Source||||Yes|
    |Doc No||||Yes|
    |Business Unit|Yes|Yes||Yes|
    |Country|Yes|Yes||Yes|
    |First Name|||||
    |Last Name|||||
    |Page No|||5||
    |Mark for Deletion||Yes|||  

    </div>

    <img width="714" alt="image" src="https://media.github.ibm.com/user/369573/files/46262200-c581-11ec-80cb-3b35683cbcb6">
- After entering all required values on the ‘Manual Upload Attributes’ tab, click on ‘Add’ button
- The document will be added to selected folder.
    ![image](https://media.github.ibm.com/user/369573/files/76894400-cbb1-11ec-8cb5-2fafd67be446)









