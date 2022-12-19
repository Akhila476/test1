---
layout: default
title: Upload to Repository
parent: Manual Upload
grand_parent: Document Import
nav_order: 1
---

Please follow the below instruction to import documents into the system, using Drag and Drop.

- Login into Global EJS Payroll application. Refer [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) for more login details.  
- After Login, by default user should land on the Browse page.
   ![image](https://media.github.ibm.com/user/369573/files/2dfdd500-c578-11ec-8e32-d38156a0becc)
- Open the document location on local machine to upload to the repository.
   ![image](https://media.github.ibm.com/user/369573/files/4a9a0d00-c578-11ec-8c39-087ec52564e3)
- Select and drag the document and drop on the Browse page, as shown in below   
   ![image](https://media.github.ibm.com/user/369573/files/643b5480-c578-11ec-9da2-c0a0b300e405)
- Once dropped, user will see ‘Add Document’ dialog on UI (User Interface)
   <img width="947" alt="image" src="https://media.github.ibm.com/user/369573/files/d9605700-c583-11ec-884a-cc97a3f98796">
- Default location of **Save-in** is repository, users are not-authorized to change the save in location.
- **File name** will be auto populated based on the selected document and will be in read-only mode.
   <img width="941" alt="image" src="https://media.github.ibm.com/user/369573/files/bbdebd80-c582-11ec-8334-e4eb4990b9dd">
- Add Document Template includes 2 tabs
   1. Manual Upload Attributes
   2. Other Attributes
- In ‘Manual Upload Attributes’ tab following details will be populated
- Enter CNUM, Document Date, Document Type ID attributes.
- Refer to [Validations](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentImport/CommonFunctionalities/Validations.html)  section before providing values.
- Barcode will be auto populated and concatenated using CNUM,  Document Date, Document Type ID, ‘P’ for Business Unit.
- Document Type, Capture Date and Scan User will be set by the system.


   |Property to Enter |Mandatory |Dropdown(ChoiceList)|Property Length |Auto Populate |
   --- | --- | ---|
   |Document Title|||255||
   |CNUM|Yes||9||
   |Document Date|Yes||||
   |DocumentTypeID|Yes||7||
   |Document Type|Yes|Yes||Yes|
   |Barcode|Yes|||Yes|
   |Capture Date|||||
   |Scan User|Yes||50||
   |Completed Date|||||

   <img width="708" alt="image" src="https://media.github.ibm.com/user/369573/files/1b879980-c580-11ec-9e0f-af011e016a6b">

- Document Title is the name of the selected document, and its value will be auto populated. User will also be able to change the document title.
- In ‘Other Attributes’ tab following details will be 
auto populated

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

- After entering all the required values in both Manual Upload Attributes tab and Other Attributes tab, Click on ‘Add’ button
- The document will add to the repository.


