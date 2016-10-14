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
   ms.date="08/03/2016"
   ms.author="robinr"/>

# Create a Common Data Model database
You can create a database and build apps using the Common Data Model as a data store. Create your own custom entities, or choose from hundreds of entities, such as account, customer, contact, and leads. In order to create a database in an environment, you would have to be an administrator and have the proper license assigned to you.

## Create a database in the Admin Portal
1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the left navigation pane.
1. Select your environment by clicking on it.
1. Select the **Database** tab.
1. Click on **Create a database**. By default, the database is created in Open access mode.
1. If you want to enforce security, click on **Restrict access**.

## Create a database under Maker Portal Home pane
1. On [powerapps.com](https://web.powerapps.com), select **Home** in the left navigation pane.
1. Look for the button under **User the Microsoft Common Data Model** section

Depending on your license and permission assignments you may or may not be allowed to create a database in the current environment.

### Allowed to create database
You will see the **Create database** button.

1. Click on **Create database**. You will see a dialog.
1. Check the **Restrict access to database** box if you want to enforce security. Otherwise leave unchecked.
1. Click on **Create my database**.

### Not allowed to create database
You will see the **Get started** button.

1. Select the **Get started** button. You will see a dialog.
1. Select **Create new environment** to start creating a new environment and database.
1. Add a unique **Environment name** and select the appropriate **Region**.
1. Check the **Restrict access to database** box if you want to enforce security. Otherwise leave unchecked.
1. Click on **Create**.

## Create a database under Maker Portal Entities pane
1. On [powerapps.com](https://web.powerapps.com), select **Common data model** in the left navigation pane.
1. Select **Entities** in the left navigation pane.
1. Click on **Create a database**. The database is created in Open access mode.
1. If you want to enforce security, click on **Restrict access**.

## Open and restricted databases
By default, a database will be created in Open mode, meaning security is not enforced for accessing entity. The environment administrator can choose to Restrict access on the database, where entity access security will be enforced based on permissions sets and roles.

1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the left navigation pane.
1. Select your environment by clicking on it.
1. Select the **Database** tab. The tab will show the database security state.
2. If database has open access, you can click on **Restrict Access** to enforce security.
2. If database has restricted access, you can click on **Open Access** to disable security.

## License and security permissions
In order to create a database, you have to be an administrator in a given environment, and have the appropriate license assigned to you. You can further configure security permission for other users from the environment **Security** tab. See [security topic link] for more information.

