---
title: "Security model | Common Data Service"
description: "The Common Data Service provides a security framework to help protect your data."
author: "maertenm"
manager: "robinarh"
ms.date: "11/02/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "775f3c15-da19-450a-83b0-b363d77f9725"
---

# Security model

The Common Data Service provides a security framework to help protect your data. When running in restricted mode, your administrators have full control over who accesses the data using the role based concepts described in this topic. If you're just getting started or do not need strict access controls, open mode makes sharing your apps a breeze.

## Open mode and restricted mode
There are two modes in which the Common Data Service can run, open or restricted. In open mode, the data stored in the common data service is open to all users. This means that you can share apps and view data without having to worry about managing permissions to your data. Everyone will always have the needed permissions to use any app.
When using Microsoft PowerApps, your database will be created in open mode by default, but you can optionally choose to restrict access at creation time. After your database is created you can always toggle between open mode and restricted access on the database tab of the admin center. If you choose to store sensitive data, you should turn off the open mode setting and grant specific data permissions to users by using the admin center. When running in restricted mode, you will need to configure the role-based security described in the following section.

## Role-based security
A role-based system is used to grant users permissions to data. The security model is a hierarchy, with each level representing a different level of access. At the lowest level are individual create, read, update, and delete permissions on a single entity. A collection of these entity level permissions form a permission set. Multiple permission sets can then be combined to create a role. A role is the top-level artifact that encompasses all the permissions needed by a user or a group of users.

### Permission sets
Permission sets are the building blocks of the role-based security framework. A permission set specifies the level of access that is granted to a set of entities. Create, read, update, and delete permissions can be granted to any entity included in the permission set. A permission set should contain a set of entities needed to perform a specific task or run a single app.
There is also a set of out-of-the-box permission sets that grant access to the out-of-the-box entities. Add these permission sets to a role to leverage the out-of-the-box entities, or create your own .

### Roles
In restricted mode every user must have one or more role assigned to them. Managing security through roles allows you save time by not having to set up security for each user. A role can be set up for a given position within your company, and assigned to any person who is in that position. Users can also be automatically added to a role based on the Azure Active Directory groups they belong to.

Roles combine the permissions granted across the permission sets added to them. In this way, members of a role can access all the data provided to them by the permission sets included in the role.

## Out-of-the-box security roles
### Database Owner
The Database Owner role is intended for users in an administrative function. Users in this role will always have full access to all entities in the database, even as new entities are added. The database owner role also provides users the ability to create and edit entity schema in the environment.

### Organization User
The Organization User role is the default role assigned to all users. This role is intended to provide all users access to the entities that contain public data.
