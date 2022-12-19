---
layout: default
title: Auto populate the field values
parent: Manual Upload
grand_parent: Document Import
nav_order: 3
---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

| Property Name    |Auto Populate for the New Documents |
|:------------------|:---- |
| Scan User        | Yes|
| Capture Source   | Yes|
| Doc No           | Yes|
| Business Unit    | Yes|
| Country          | Yes|
| First Name       | Set once document is stored via API|
| Last Name        | Set once document is stored via API|
| Mark for Deletion| Yes|

### Scan User
In the “Manual Upload Attributes” tab of Add Document Template, **Scan User** field value is pre-populated with logged in user id & will be read-only. 

Example:
If the logged in User Id is Indu.Emandi@ibm.com then scan user field will be auto populated as Indu.Emandi@ibm.com.

<img width="449" alt="image" src="https://media.github.ibm.com/user/369573/files/9f954d80-c58f-11ec-8dcb-0540638ff0fe">


### Capture Source & Doc No
In the “Other Attributes” tab, **Capture Source** and **Doc No** is prepopulated with the value of ‘Manual’ & will be read-only.

<img width="449" alt="image" src="https://media.github.ibm.com/user/369573/files/f0a54180-c58f-11ec-90b4-e35cb6af6342">


### Business Unit
In the “Other Attributes” tab, **Business Unit** field is prepopulated with the value of ‘Payroll’ & will be read-only.

<img width="449" alt="image" src="https://media.github.ibm.com/user/369573/files/26e2c100-c590-11ec-819a-ee502041b15f">

### Country
In the “Other Attributes” tab, **Country** field is prepopulated with ‘USA’& will be read-only.

<img width="449" alt="image" src="https://media.github.ibm.com/user/369573/files/3bbf5480-c590-11ec-82f8-7448ae09d130">


### Mark for Deletion
In the “Other Attributes” tab, **Mark For Deletion** property is prepopulated as False & will be editable by the user.

<img width="449" alt="image" src="https://media.github.ibm.com/user/369573/files/6362ec80-c591-11ec-83fd-bdc5f3759c36">



