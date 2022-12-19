---
layout: default
title: Employee Serial Number – Migrated Documents Search
parent: Document Search
nav_order: 8
---

Employee Serial Number – Migrated Documents Search” is used for searching the documents based on the serial number of the employee for documents migrated from the legacy CM application.

**Search Criteria:**
- Select the “Employee Serial Number - Migrtaed Document Search” From “All Searches”.
- The following list of fields will be displayed on the search criteria section.
    <div class="code-example" markdown="1">

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |Employee Serial Number|StartsWith, Like, EndsWith, Equals|Yes||9|
   |Capture Source|Equlas, Like, StartsWith, EndsWith|||12|
   |Capture Date|Equals, Between||||
   |DocumentTypeID|Equlas,Like, StartsWith, EndsWith|||7|
   |Document Date|Equals, Between||||

   </div>

   ![image](https://media.github.ibm.com/user/369573/files/e1fa7100-c607-11ec-8eab-620f0950a8f9)


1.	Mandatory field
	- Mandatory field should not be empty.  
	- If its empty, then Search button will be disabled and Error popup message will be shown to User 

    ![image](https://media.github.ibm.com/user/369573/files/f6d70480-c607-11ec-92bf-e7d8bd9c1d51)


2. Operator for string,

    <div class="code-example" markdown="1">

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |Employee Serial Number|Like, EndsWith, StartsWith, Equals|String|
    |Capture Source|Equlas, Like, StartsWith, EndsWith|String|
    |DocumentTypeID|Equlas,Like, StartsWith, EndsWith|String|
   
    </div>

3.	Operators for the date and time Format  
    - Equals
    - Between

4. Search Button
    - After filling all the mandatory fields Click on “Search Button”.
    - User can view the documents based on value entered on the search criteria.

**Search Results:**
- User can view all the information on the document in the “Search Results” page.
- Please refer [Search Results](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/CommonFunctionalities/SearchResults.html), for the list of document properties that will be visible to the user on search results section.

![image](https://media.github.ibm.com/user/369573/files/24bc4900-c608-11ec-8845-d78edde83cbe)

**Note:**
Before providing value on DocumentDate field please refer [Document Date Search using Between Operator section in Document Date Search](https://pages.github.ibm.com/Global-EJS/gejs-user-manual/docs/DocumentSearch/DocumentDateSearch.html)
