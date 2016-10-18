<properties
	pageTitle="Import or export resources | Microsoft Common Data Model"
	description="Import or export resources"
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
   ms.date="10/06/2016"
   ms.author=""/>

# Import or export resources #
If you have created multiple environments to support development of your database and apps, you will need to move changes from one environment to another. You can use **Export resources** and **Import resources** to move resources between environments.

## Why use multiple environments? ##
Each environment contains resources, such as entities, flows, and apps, that you create or modify in the development process. Usually, development is done in the same environment as the one being used by the organization's end users, called the default environment. In that case, managing resource changes is relatively simple within the same environment. The app maker validates that changes to ensure all critical business processes and applications are functional and releases the app.

Sometimes development and testing are performed in separate environments, and changes are moved to the default environment when they are ready for use by end users. This could be because a separate environment was used to initially evaluate the system. Another reason is that you might want to minimize the risks of making changes to the default environment. Separate environments provide isolation, allowing you to make changes in an environment separate from the default environment. Depending on the extent of these risks, you might create an additional staging environment. In that case, you would have a development environment, a staging environment, and a default environment.

## Moving resource changes ##
Moving resources is accomplished through separate export and import processes, by way of a package file.
<!--Either, all resources can be exported as one package, or specific resources would have to be selected for export. In either case a -->
The package (.pkg) file is exported, saved to local storage, sent to the target environment administrator, and then imported to the target environment. The import process is often followed by validation testing in order to ensure no critical business processes have been adversely affected.

Both resource import and export functionality are available in the administrator portal's environments section, and export and import happen in the context of a selected environment.

### Export all resources ###
When all resources is selected as an option, the export package will contain all changes to entities, pick lists, translation sets, permission sets and roles. This enables the scenario of moving all contents of an environment to another.
<!-- This feature will be turned on in subsequent sprints
### Exporting specific resources ###

When specific resources option is selected, the user will get a chance to manually select specific resources, at first from entities, pick lists, and translation sets. During the second step, security resources are automatically selected based on entity selection from previous step, but user will have a chance to manually modify selection.
-->

1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the left navigation pane.
1. Select your source environment.
1. On the top-right select on **Export resources**.
1. When **Export completed** appears, save the package file on local storage.

### Import resources ###

The first step is to select a package (.pkg) file that was exported from the source environment. The import process validates, analyzes, and attempts to import the package.
<!-- This feature will light up in later sprints
As part of the import process, if the analysis reveals conflicts, the details of those conflicts are presented to user before the final import step. Some of these conflicts will block the process from completing, and as such these are flagged, and the process will be terminated. Assuming there are no blocking conflicts, detailed information will be provided regarding any non-blocking conflicts, including the related resource information, the type of change being applied, the reason behind the conflict, what will happen as part of import, and next steps if applicable.

As an example, in cases where an entity field is removed, the conflict is handled by keeping the old field and underlying data, and instructing the user to manually delete it if needed.
-->

1. On [admin.powerapps.com](https://admin.powerapps.com), select **Environments** in the navigation pane.
1. Select your target environment.
1. On the top-right select on **Import resources**.
1. Select **Select** and browse to a package file from local storage.
1. Select **Import**.

If the package is partially applied, an error message will describe specifically what was imported and what was not.

## Resource Types

The development process can involve changes to many types of resources. For example, if you update an app, you might add, remove, or update several entities or connections. Changes to most, if not all, resource types are movable across environments. The types of resources you can move are described in the following sections.

### Entities, pick lists and translation sets

You can export and import entities, pick lists, and translation sets as follows:
+ Standard entities: Customizations will be moved across environments. (You cannot modify the out-of-box fields of standard entities.)
+ Custom entities: Custom entities will be moved across environments.
+ Standard pick lists: Standard pick lists will be moved across environments. (You cannot modify the out-of-box fields of standard pick lists.)
+ Custom pick lists: Custom pick lists will be moved across environments.
+ Translation sets: Translation sets will be moved across environments. For more information, see [Translation sets](translation-sets.md).

### Permission sets and roles

Permission sets and roles are security resources that control access to the database, and they can be moved across environments. After moving permission sets and roles, you should ensure that the permission sets are referenced by the appropriate roles, and that the appropriate users are assigned to any new roles. For more information, see [Configure database security](database-security.md).
<!-- This feature will light up in later sprints   -- When going with the option of selecting specific resources, some permission sets may be automatically selected, if the user already selected entities referencing them. Similarly, some roles may be automatically selected, if any contained permission sets are already selected. User will be able to manually modify selection. -->

<!--
### Other resources coming soon

Over time, resource export functionality will support most if not all of the resources used within CDM, Power Apps and Flow. These will include but will not be limited to resources like Connections, Flows and Apps.
-->

## Data ##

Moving database data is not supported as part of the export and import of resources. Data can be moved by using Excel. For more information, see [Import or export data](data-platform-export-data.md).

<!-- ## Migrating from Public Preview ##

For the limited number of users who signed up for our Public Preview, given that their environments will not be upgraded to the latest version, documentation will be provided, in order to enable moving resources and data from the old environment to a new one. Please refer to [Public Preview to GA Migration Topic]
-->
