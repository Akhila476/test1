---
layout: default
title: Disposition Record Search
parent: Enterprise Record Search
nav_order: 4
---

- For login information please refer to  [User Login] for more information
- After login to IER desktop, the work page will be loaded by default

   ![image](https://user-images.githubusercontent.com/119289294/204810046-4c377e6c-eb3f-4a70-8da1-c82d37792e54.png)
   
- At the left top most corner three bars are visible click on that

   ![image](https://user-images.githubusercontent.com/119289294/204810287-b17e9e40-2c88-4ba1-ae41-edeb53238946.png)
   
- user can view the Work, Favorites and Search tabs

   ![image](https://user-images.githubusercontent.com/119289294/204810507-82ca64c1-8209-4a5b-91ae-8d41795fb2c4.png)
   
- •	Disposition Record search is used to search records based on the Disposition date, if records are matched with the provided information then those records will be displayed to users in Search results section

   ![image](https://user-images.githubusercontent.com/119289294/204810729-98144146-5511-4d69-a7e1-f53e2c0c02f8.png)
   
**Search Criteria**

- Click on the “Disposition Record Search” search template from “All Searches”.
- The following fields will be shown on the search criteria section.

   <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |TalentID|StartsWith, EndsWith, Is Not Empty, Equals|||9|
   |Capture Date|Equals, Between||||
   |DocumentTypeID|StartsWith, EndsWith, Is Not Empty, Equals|||7|
   |Document Date|Equals, Between||||
   |Completed Date|Equals, Between||||
   |Currrent Disposition Date|Equals, Between||||
   |Document Retention Date|Equals, Between||||
   

   </div>
   
   ![image](https://user-images.githubusercontent.com/119289294/204810975-fedd7a57-8478-4fbe-bf64-8976236572c7.png)
   
1. Operator for string,

    <div class="code-example" markdown="1">

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |TalentID|StartsWith, EndsWith, Is Not Empty, Equals|String|
    |DocumentTypeID|StartsWith, EndsWith, Is Not Empty, Equals|String|     

    </div>
	
2. Operators for the date and time Format  
    - Equals
    - Between
	
3. Search Button
    - After filling all the mandatory fields Click on “Search Button”.
    - User can view the Records based on value entered on the search criteria.
	
**Search Results:**

    - User could view all the information on the records in “Search Results” page.
	
	![image](https://user-images.githubusercontent.com/119289294/204811172-22a67f84-7937-435b-9092-7132e3a1a0e8.png)

- User can change the default order of the properties ,for that please refer [Result Display]
   
 