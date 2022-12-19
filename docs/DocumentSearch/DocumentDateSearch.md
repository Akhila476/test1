---
layout: default
title: Document Date Search
parent: Document Search
nav_order: 4
---
- For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Search
- Select Search from All Searches or Recent Searches section
- “Document Date Search” is searching into the respository for the documents.    
     
**Search Criteria:**
- Select the “Document Date Search” From “All Searches”.
- The following list of fields will be displayed on the search criteria section.
    <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |CNUM|Like, EndsWith, Equals|||9|
   |Capture Source|Equlas, Like, StartsWith, EndsWith|||12|
   |Capture Date|Equals, Between||||
   |DocumentTypeID|Equlas,Like, StartsWith, EndsWith|||7|
   |Document Date|Equals, Between|Yes|||
   |Scan User|Equals|||50|

   </div>

    ![image](https://media.github.ibm.com/user/369573/files/1bc97880-c604-11ec-9cd4-ab451fcaab83)

1.	Mandatory field
	- Mandatory field should not be empty.  
	- If its empty, then Search button will be disabled and Error popup message will be shown to User 

    ![image](https://media.github.ibm.com/user/369573/files/4c111700-c604-11ec-9c9d-a26d1f45f359)


2. Operator for string,

    <div class="code-example" markdown="1">

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |CNUM|Like, EndsWith, Equals|String|
    |Capture Source|Equlas, Like, StartsWith, EndsWith|String|
    |DocumentTypeID|Equlas,Like, StartsWith, EndsWith|String|
    |Scan User|Equals|String|        

    </div>

3.	Operators for the date and time Format  
    - Equals
    - Between

4. Search Button
    - After filling all the mandatory fields Click on “Search Button”.
    - Based on the values entered by the user, search results section will be loaded with documents.

**Search Results:**
- User can view all the information on the document in the “Search Results” page.
- Please refer [Search Results](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/CommonFunctionalities/SearchResults.html), for the list of document properties that will be visible to the user on search results section.


**Document Date Search using Between Operator:**
 If the user want to search the documents with specific document date then uesr must select between operator 

1. Select the "Between" operator
2. Provide previous day date of the ActualDate and ActualDate 

 **Example:**
 search the documents which are having Document Date as 09-18-2022,then in search criteria users must select between operator and provide (Previous Day Date) i.e., 09-17-2022 and (Actual Date) 09-18-2022.

 ![Untitled](https://media.github.ibm.com/user/369573/files/09becf80-385c-11ed-9508-1dd1b85cfc51)

