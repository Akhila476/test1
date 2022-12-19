---
layout: default
title: AutoPopulate First Name & Last Name
parent: Common Functionalities
#has_children: true
nav_order: 4
grand_parent: Document Import
---

1.	**FirstName** and **LastName** property values will be auto populated only for the existing documents based on the valid CNUM value
2.	In the “Other Attributes” tab, First Name and Last Name property values are prepopulated which are added manually.

    Example:
    1. Entered value is 0009VM744, FirstName , LastName will be auto populated because entered CNUM Value is valid.
    ![image](https://media.github.ibm.com/user/376381/files/39560c80-c61b-11ec-8557-91de60a6feca)

    2. Entered value is 123456789 , FirstName , LastName will not be populated because entered CNUM Value is Invalid.
    ![image](https://media.github.ibm.com/user/369573/files/2d5af200-cc8e-11ec-8907-538cdd73c719)


3.	In the properties, First Name and Last Name property values are prepopulated which are added by using scan option.

    Example:
    1. Entered value is 0009VM744, FirstName , LastName is autopopulate because entered CNUM Value is valid

        ![image](https://media.github.ibm.com/user/376381/files/cf8a3280-c61b-11ec-9e33-fe646cdd16c2)

    2. Entered value is 123456789 , FirstName , LastName is not populated because entered CNUM Value is Invalid

        ![image](https://media.github.ibm.com/user/376381/files/ddd84e80-c61b-11ec-8743-094fafcfd6bd)

