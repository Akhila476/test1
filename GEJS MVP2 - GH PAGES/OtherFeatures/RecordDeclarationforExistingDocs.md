---
layout: default
title: Record declaration utility (for existing documents)
parent: Other Features
nav_order: 1
---

**Purpose**
- Based on the Document Type ID and Record Retention all the Existing documents will be declared as records in record category volumes 

**checking declared documents**
- User must login to Global EJS payroll Application
    https://navigator-ejsdemoprj21.ibmejsdemo21-a77d60340023a6bc6f520169685a0756-0000.us-south.containers.appdomain.cloud/navigator?desktop=IGEJSP
- After Login user “Favorites”  page will be opened by default

   ![image](https://user-images.githubusercontent.com/119289294/204545375-8ca56c4c-51b6-456c-860d-4d019e6b278f.png)
   
- At the left top most corner three bars are visible click on that, user can view the Home , Browse, Search and DataCap Main Page tabs
- Select search feature

   ![image](https://user-images.githubusercontent.com/119289294/204545094-d5f60d4a-cb5d-4adf-96ba-2e416f7985fd.png)
   
- User Then select any of the search template from All Searches , then enter TalentID for TalentID property field

   ![image](https://user-images.githubusercontent.com/119289294/204544678-6255aac8-af5a-43f2-942d-52f046a8031c.png)
   
- Then click on search button
- verify search results whether the documents with the provided TalentID are declared or not (red icon will be visible besides the document)

  ![image](https://user-images.githubusercontent.com/119289294/204544221-f668afc2-19ac-4032-880c-8b7259a11c4b.png)
   
**Known scenarios **
documents will not be declared in some cases that are shown below:
If documents are having
    - Invalid serial number
    - Invalid document type ID
    - Completed date empty with document type ID 0019.00 and 0046.00
   

