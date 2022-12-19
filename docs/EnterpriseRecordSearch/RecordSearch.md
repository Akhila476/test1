---
layout: default
title: Record Search
parent: Enterprise Record Search
nav_order: 2
---

- For login information please refer to  [User Login] for more information
- After login to IER desktop, the work page will be loaded by default

   ![image](https://user-images.githubusercontent.com/119289294/204813769-77ceb245-ef8a-4261-8e21-88762d4e8789.png)
   
- At the left top most corner three bars are visible, click on that, work , Search , Favorites tabs will be displayed .Click on Search.

   ![image](https://user-images.githubusercontent.com/119289294/204814042-ec20c9a3-cfba-41d6-a888-fdec49e0c780.png)
   
- Record search is used to search records based on the provided information , If the documents are matched with the information entered then those records will be displayed to user in search results section

**Search Criteria**
- Click on the “Record Search” search template from “All Searches”.
- The following fields will be shown on the search criteria section.

   <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |TalentID|StartsWith, EndsWith, Is Not Empty, Equals|||9|
   |Capture Date|Equals, Between||||
   |DocumentTypeID|StartsWith, EndsWith, Is Not Empty, Equals|||7|
   |Document Date|Equals, Between||||
   |Completed Date|Equals, Between||||
   |Document Retention Date|Equals, Between||||

   </div>

   ![image](https://user-images.githubusercontent.com/119289294/204814350-0a4e0e13-e8da-42e2-8308-1a0cc628dbab.png)
   
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
	
	![image](https://user-images.githubusercontent.com/119289294/204814892-ae629f3b-fffe-4e28-99b5-d71735a22a4f.png)

- User can change the default order of the properties ,for that please refer [Result Display]
	




