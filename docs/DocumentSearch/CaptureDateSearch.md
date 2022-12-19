---
layout: default
title: Capture Date Search
parent: Document Search
nav_order: 2
---


- For Login information, refer to [User Login](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/UserLogin.html) section.
- From the Browse page, click the hamburger icon to expand the menu and select Search
- Select Search from All Searches or Recent Searches section
- “Capture Date Search” is used to search documents based on the date scanned or uploaded, if the documents are matched with the date entered then  those documents will be displayed to user in search results section.

![image](https://media.github.ibm.com/user/369573/files/85bfc000-cbb8-11ec-90d4-02d61f2f9d6c)


**Search Criteria**
- Click on the “Capture Date Search” From “All Searches”.
- The following fields will be shown on the search criteria section.
   <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |CNUM|Like, EndsWith, Equals|||9|
   |Capture Source|Equlas, Like, StartsWith, EndsWith|||12|
   |Capture Date|Equals, Between|Yes|||
   |DocumentTypeID|Equlas, Like, StartsWith, EndsWith|||7|
   |Document Date|Equals, Between||||
   |Scan User|Equals|||50|

   </div>
   
    ![image](https://media.github.ibm.com/user/369573/files/6e089a80-c600-11ec-82a4-a39f97e285ca)

1.	Mandatory field
    - Mandatory field should not be empty.  
    - If its empty, then Search button will be disabled and “This value is required” error message will be displayed against the field as shown below,

    ![image](https://media.github.ibm.com/user/369573/files/9395a400-c600-11ec-92c5-83c828ff2635)

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

![image](https://media.github.ibm.com/user/369573/files/2551e100-c602-11ec-9a92-d60673975f16)

**Note:**
Before providing value on DocumentDate field please refer [Document Date Search using Between Operator section in Document Date Search](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/DocumentDateSearch.html)



    
