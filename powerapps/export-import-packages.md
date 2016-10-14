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
Each environment contains many types of resources, like entities, flows or apps, which would be created or modified in the development process, in order to add valuable functionality to the system. More commonly, development is done in the same environment as the one being used by the organization's end users. In such a case, managing resource changes is relatively simple within the same environment, where the App maker would validate changes ensuring all critical business processes and applications are functional.

Another common pattern is where development and testing are performed in separate environments, and where changes are subsequently moved to the organization's default environment. Sometimes a separate environment is used to initially evaluate the system. Often however, the reason for this isolation, is that critical business processes have critical dependencies on resource changes. As a result, the system administrator's concern about the risk of making changes in the default environment, will force them to isolate development from the default environment. Depending on the extent of these risks, additional testing or staging may be needed.

## Moving resource changes ##
When dealing with isolated development and default environments, the need arises for moving resource changes across these environments. This can be accomplished through separate export and import processes, and using a physical package file. Either, all resources can be exported as one package, or specific resources would have to be selected for export. In either case a package (.pkg) file is produced, which would have to be stored physically on disk, transferred to the target environment administrator, and subsequently imported to that environment. The process of importing into the target environment is often followed by validation testing in order to ensure no critical business processes have been adversely affected.

Both resource import and export functionality are available in the administrator portal's environments section and both corresponding buttons function in the context of a selected environment.

### Exporting all resources ###

When all resources is selected as an option, the export package will contain all changes to entities, pick lists, translation sets, permission sets and roles. This enables the scenario of moving all contents of an environment to another.
p!-- This feature will be turned on in subsequent sprints
### Exporting specific resources ###

When specific resources option is selected, the user will get a chance to manually select specific resources, at first from entities, pick lists, and translation sets. During the second step, security resources are automatically selected based on entity selection from previous step, but user will have a chance to manually modify selection.
-->

## Importing resources ##

A package (.pkg) file, exported from the source environment, will have to be selected as a first step. The import process will then validate, analyze and attempt to import the package. 
<!-- This feature will light up in later sprints
As part of the import process, if the analysis reveals conflicts, the details of those conflicts are presented to user before the final import step. Some of these conflicts will block the process from completing, and as such these are flagged, and the process will be terminated. Assuming there are no blocking conflicts, detailed information will be provided regarding any non-blocking conflicts, including the related resource information, the type of change being applied, the reason behind the conflict, what will happen as part of import, and next steps if applicable.

As an example, in cases where an entity field is removed, the conflict is handled by keeping the old field and underlying data, and instructing the user to manually delete it if needed.
-->

In the rare case that the package is partially applied, an error message will describe specifically what was imported and what was not.

## Resource Types

Development process can involve changes to many types of resources. Take for example a scenario of changing an App and its underlying entities and connections, however there are many other combinations possible. Changes to most, if not all, resource types would eventually be movable across environments.

### Entities, pick lists and translation sets

Entities can be of Standard type of Custom type. While the original definition of Standard entities cannot be changed, any customizations will be included in the export process. New custom entities or modifications to existing ones can also be moved across environments. Similar to entities, pick lists can be of Standard type or of Custom type. The Standard entities cannot currently be changed, however addition of custom pick lists or changes to existing ones can also be handled by the export process. Translation sets can also be moved across environments. For more details about translation sets see [Translation Sets Topic Link].

### Permission sets and roles

Permission Sets and Roles are security resources governing access to data inside CDM.<!-- This feature will light up in later sprints   -- When going with the option of selecting specific resources, some permission sets may be automatically selected, if the user already selected entities referencing them. Similarly, some roles may be automatically selected, if any contained permission sets are already selected. User will be able to manually modify selection. --> After moving Permission Sets and Roles, the administrator should ensure that the Permission Sets are referenced by the appropriate Roles, and that the appropriate users are assigned to any new Roles. For more details please refer to [Security Role Topic Link]

### Other resources coming soon

Over time, resource export functionality will support most if not all of the resources used within CDM, Power Apps and Flow. These will include but will not be limited to resources like Connections, Flows and Apps.

## Moving data ##

Moving CDM data is not supported as part of the export and import of resources. Data can be moved by using the [data import export](/pwoerapps/data-platform-export-data.md) feature.


## Migrating from Public Preview ##

For the limited number of users who signed up for our Public Preview, given that their environments will not be upgraded to the latest version, documentation will be provided, in order to enable moving resources and data from the old environment to a new one. Please refer to [Public Preview to GA Migration Topic]
