---
layout: default
title: Record declaration utility (for future documents)
parent: Other Features
nav_order: 2
---

**Adding Document**

- User must login to Global EJS ICN desktop with w3 credentials
    https://navigator-ejsdemoprj21.ibmejsdemo21-a77d60340023a6bc6f520169685a0756-0000.us-south.containers.appdomain.cloud/navigator?desktop=IGEJSP
- After login user, favorites page will be opened by default

   ![image](https://user-images.githubusercontent.com/119289294/204550431-2f31a32c-9a05-45e5-a5ba-f75971230744.png)
   
- At the left top most corner three bars are visible click on that, user can view the Home, Browse, Search , Datacap MainPage features

   ![image](https://user-images.githubusercontent.com/119289294/204552201-6493c580-e857-45b5-98cd-57b4286a429e.png)

- Select browse feature

   ![image](https://user-images.githubusercontent.com/119289294/204551914-c55a8f25-507f-4507-a094-f08872e6bbfe.png)
 
- Select and drag the document and drop on any one of the folders under Payroll US , user will get into add document page as shown below

   ![image](https://user-images.githubusercontent.com/119289294/204552770-228cc22b-b951-4ac4-afed-c8a9de29482e.png)
   
- Provide TalentID for the TalentID field
- Select date for the Document Date field 
- Provide document type ID for the Document Type ID field and click on white space then Document Type , Barcode values will populate automatically
- User then select date for the Completed Date field ( user must select the completed date while using document type IDs 0019.00 and 0046.00)
- Click on add button after filling all the mandatory fields to add the document
- Click on cancel button if user needs to go back

**Checking whether documents are declared or not**
- At the left top most corner three bars are visible click on that, user can view the Home, Browse, Search , Datacap MainPage features
- Select search feature

   ![image](https://user-images.githubusercontent.com/119289294/204553504-c9bcc1ef-f382-436a-b539-55c35cfc3097.png)
   
- User Then select any of the search template from All Searches , then enter TalentID for TalentID property field
   
   ![image](https://user-images.githubusercontent.com/119289294/204553916-07a2d779-a1ff-4021-80a5-bc105c0ded32.png)
   
- Then click on search button
- verify search results whether the document declared or not ( red icon will be visible beside the document)

   ![image](https://user-images.githubusercontent.com/119289294/204554403-13239061-2cc5-40ab-9127-a38dfa2c64d0.png)
   
**Known scenarios:**

**Positive Scenarios:**
- Documents that were checked out will be canceled from check out and will be declared in record category volumes
- After updating completed date for the Documents that are having document Type IDs 0019.00 and 0046.00 with completed date null will be declared in record category volumes

**Negative scenarios:**
documents will not be declared in some cases that are shown below:
If documents added with:
- invalid serial number
- Invalid document type ID
- Completed date empty with document type IDs 0019.00 and 0046.00


