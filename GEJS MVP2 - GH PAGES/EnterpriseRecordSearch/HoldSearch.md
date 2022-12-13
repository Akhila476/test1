---
layout: default
title: Hold Search
parent: Enterprise Record Search
nav_order: 3
---

- For login information please refer to  [User Login] for more information
- After login to IER desktop, the work page will be loaded by default

   ![image](https://user-images.githubusercontent.com/119289294/204811933-e1c99b90-2782-4eb2-bf2c-341667d8c86a.png)
   
- At the left top most corner three bars are visible click on that

   ![image](https://user-images.githubusercontent.com/119289294/204812282-a28f9242-ab15-4b9e-a52f-853e1d443a82.png)
   
- user can view the Work, Favorites and Search tabs

   ![image](https://user-images.githubusercontent.com/119289294/204812477-f362429b-7bdf-461f-870c-f41e24bc59fe.png)
   
- Hold search is used to search the records that are either on Hold or Un Hold using the TalentID property and On Hold property

   ![image](https://user-images.githubusercontent.com/119289294/204812828-adcaf231-1280-4e10-b4c1-15d0f6e1b923.png)
   
**Search Criteria**

- Click on the “Hold Search” search template from “All Searches”.
- The following fields will be shown on the search criteria section.

   <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |TalentID|StartsWith, EndsWith, Is Not Empty, Equals|||9|
   |Retention Code|StartsWith, EndsWith, Is Not Empty, Equals||||
   |Document Retention Date|Equals, Between||||
   |DocumentTypeID|StartsWith, EndsWith, Is Not Empty, Equals|||7|
   |Document Date|Equals, Between||||
   |On Hold|Equals||True, False||
   

   </div>
   
   ![image](https://user-images.githubusercontent.com/119289294/204813063-e8c471e8-b186-41f7-ad2e-a15f74b5ec30.png)
   
1. Operator for string,

    <div class="code-example" markdown="1">

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |TalentID|StartsWith, EndsWith, Is Not Empty, Equals|String|
	|Retention Code|StartsWith, EndsWith, Is Not Empty, Equals|String|
    |DocumentTypeID|StartsWith, EndsWith, Is Not Empty, Equals|String|     

    </div>
	
2. Operators for the date and time Format  
    - Equals
    - Between
	
3)	Operators for Boolean Format
    - Equals
	
3. Search Button
    - After filling all the mandatory fields Click on “Search Button”.
    - User can view the Records based on value entered on the search criteria.
	
**Search Results:**
    - User could view all the information on the records in “Search Results” page.
	
	![image](https://user-images.githubusercontent.com/119289294/204813360-a0b8f2ba-bdf6-4a8a-b1d6-80b1e4c3d9b2.png)
	
- User can change the default order of the properties ,for that please refer [Result Display]