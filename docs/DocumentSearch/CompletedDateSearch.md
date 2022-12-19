---
layout: default
title: Completed Date Search
parent: Document Search
nav_order: 1
---

- The user must log in to the Global EJS payroll application 
    https://navigator-ejsdemoprj21.ibmejsdemo21-a77d60340023a6bc6f520169685a0756-0000.us-south.containers.appdomain.cloud/navigator?desktop=IGEJSP
- After Login user “Favorites”  page will be opened by default.
  
   ![image](https://user-images.githubusercontent.com/119289294/204798198-d160c56f-f557-459c-b732-c96db61224b0.png)
	
- At the left top most corner three bars are visible click on that hamburger , user can view the Home, Browse, Search , Datacap MainPage tabs.

   ![image](https://user-images.githubusercontent.com/119289294/204798415-b224a271-5994-424c-ac1d-262bbd4a20f8.png)
   
- Click on search 

   ![image](https://user-images.githubusercontent.com/119289294/204798636-a618c439-2010-4217-ba76-925dc43ab205.png)
   
- “Completed Date Search” is used to fill completed date for those documents which has completed date as  empty, If the documents are matched with the data entered then  those documents will be 
displayed to user in search results section.

   ![image](https://user-images.githubusercontent.com/119289294/204798839-afbb1d48-dab0-4d9b-84ac-8a3f44be1c60.png)
   
**Search Criteria:**
- Select the “Completed Date Search” From “All Searches”.
- The following list of fields will be displayed on the search criteria section.
    <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |DocumentTypeID|StartsWith, EndsWith, Equlas|||7|
   |TalentID|StartsWith, EndsWith, Equlas|Yes||9|
   |Completed Date|Is Empty||||

   </div>
   
   ![image](https://user-images.githubusercontent.com/119289294/204799023-5a581ff4-a613-4c7d-8660-f96c440e28c1.png)
   
1.	Mandatory field
	- Mandatory field should not be empty.  
	- If its empty, then Search button will be disabled and “This value is required” error message will be displayed against the field as shown below,
	
	![image](https://user-images.githubusercontent.com/119289294/204799247-0b32e2f9-4a81-488f-a334-d367f2b36c76.png)
	
2. Operator for string,

    <div class="code-example" markdown="1">

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |DocumentTypeID|StartsWith, EndsWith, Equals|String|  
	|TalentID|StartsWith, EndsWith, Equals|String|
    

    </div>
	
3. Search Button
   - After filling all the mandatory fields Click on “Search Button”.
   - Based on the values entered by the user, search results section will be loaded with documents.
   
**Search Results:**
- User can view all the information on the document in the “Search Results” page.

   ![image](https://user-images.githubusercontent.com/119289294/204799544-7129465c-07a9-498b-8155-d0c30f0ae98e.png)
