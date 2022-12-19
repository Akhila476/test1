---
layout: default
title: Document Type Search
parent: Document Search
nav_order: 5
---
- For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Search
- Select Search from All Searches or Recent Searches section
- “Document Date Search” is searching into the respository for the documents.    
  
**Search Criteria:**
- Select the “Document Type Search” From “All Searches”.
- The following list of fields will be displayed on the search criteria section.
    <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |CNUM|Like, EndsWith, Equals|||9|
   |Capture Source|Equlas, Like, StartsWith, EndsWith|Yes||12|
   |Capture Date|Equals, Between||||
   |DocumentTypeID|Equlas,Like, StartsWith, EndsWith|||7|
   |Document Date|Equals, Between||||
   |Scan User|Equals|||50|

   </div>

    ![image](https://media.github.ibm.com/user/369573/files/17518f80-c605-11ec-86fd-c3cad0ab59e8)

1.	Mandatory field
	- Mandatory field should not be empty.  
	- If its empty, then Search button will be disabled and Error popup message will be shown to User 

    ![image](https://media.github.ibm.com/user/369573/files/32bc9a80-c605-11ec-985a-0cfdff3739f8)


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

![image](https://media.github.ibm.com/user/369573/files/58e23a80-c605-11ec-9437-cb477fc6bc77)

**Note:**
Before providing value on DocumentDate field please refer [Document Date Search using Between Operator section in Document Date Search](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/DocumentDateSearch.html)
