<properties
	pageTitle="Create a Common Data Model database | Microsoft Common Data Model"
	description="Create a Common Data Model database"
	services="powerapps"
	documentationCenter="na"
	authors="nimakms"
	manager="robinarh"
	editor=""
	tags=""/>

<tags
   ms.service="powerapps"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="10/16/2016"
   ms.author="robinr"/>

# Create a Common Data Model database
You can create a database and build apps using the Common Data Model as a data store. You can create your own custom entities or use the predefined entities. If you want to create a database in an environment, you have to be an administrator and have the proper license assigned to you.

There are three ways to create database:
+ In the Admin Portal.
+ In the Maker Portal.
+ In the Entities pane.

## Create a database in the Admin Portal
1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the left navigation pane.
1. Select your environment.
1. Select the **Database** tab.
1. Select **Create a database**. By default, the database is created in Open access mode.
1. If you want to enforce security, select **Restrict access**.

## Create a database in the Maker Portal
1. On [powerapps.com](https://web.powerapps.com), select **Home** in the navigation pane.
1. Look for the button in the section labeled **User the Microsoft Common Data Model**. The button labeled either **Create database** or **Get started**. The label is determined by your license and permission assignments. You may or may not be allowed to create a database in the current environment.

### Create database
1. Select **Create database**.
1. In the dialog box, check the **Restrict access to database** box if you want to enforce security. Otherwise leave unchecked.
1. Select **Create my database**.

### Get started
1. Select **Get started**.
1. In the dialog box, select **Create new environment** to start creating a new environment and database.
1. Add a unique **Environment name** and select the appropriate **Region**.
1. Check the **Restrict access to database** box if you want to enforce security. Otherwise leave unchecked.
1. Select **Create**.

## Create a database in the Entities pane
1. On [powerapps.com](https://web.powerapps.com), select **Entities** in the navigation pane.
1. Select **Create a database**. The database is created in Open access mode.

## Open and restricted databases
By default, a database will be created in Open mode, meaning security is not enforced for accessing entities. The environment administrator set the database to Restrict mode, where entity access security will be enforced based on permissions sets and roles.

1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the  navigation pane.
1. Select your environment.
1. Select the **Database** tab.
    + Select **Restrict Access** to enforce security.
    + Select **Open Access** to disable security.

## License and security permissions
To create a database, you have to be an administrator in the selected environment, and  the appropriate license has to be assigned to you. You can further configure security permission for other users from the environment **Security** tab. See [Secure the database](database-security.md) for more information.
