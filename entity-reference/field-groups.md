---
title: "Field groups"
description: ""
author: "Anees Ansari"
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: "Field Group"
audience: "Developer, IT Pro"
ms.assetid: "f5249803-d7e0-4244-8bb5-f3831695e402"
---

# Field Groups

Field groups provide a way to group one or more fields of a Common Data Service entity. Field groups can help speed up and simplify the creation and maintenance of apps using the Common Data Service. A field group can contain one or more fields and a field can appear in any number of field groups. 

Field groups are stored on Common Data Service entities and are therefore shared across all apps that use the same entity. At any given time there may be many different apps using the same entity and field groups of that entity. This centralization and sharing of field groups helps enforce consistency since a field group will always display the exact same fields wherever it is used. It also eases maintenance since a change to a field group is automatically reflected in all the places using that field group. Field groups help speed up the app authoring and customization process since an application author works with groups of fields rather than individual fields. 

## Default Field Groups
Common Data Service includes a number of default field groups on entities. These field groups are used in various places to help speed up and ease app creation and customization.

| Default Field Group Name | Description |
|:-------------------------|-------------|
|DefaultCard |Used to display a list of records when the display width available is narrow such as small screen devices.|
|DefaultList |Used to display a list of records when the display width available is wide such as small tablet and laptop devices.|
|DefaultLookup |Used to display a lookup (picklist) to select a record.|
|DefaultIdentification |This group should contain one or more fields that serve as an end-user friendly alternate key for an entity. This group of fields helps end-users to identify records and is used instead of an auto-generated system primary key, which in most cases is just a large number.|
|DefaultDetails |Used to display the details of a single record (view and edit).|
|DefaultReport |Used to display a single record in a report. Similar to DefaultDetails.|

## Working with Field Groups

**Pre-requisite**: Sign up for powerapps.com, and then sign in

### Viewing a Field Group
1. In the left navigation bar, click on “Entities”.
2. If you have access to more than one database ensure you have the right database selected using the dropdown above the list of entities.
3. In the list of entities, click on the entity you want to view the field group for.
4. In the header above the list of fields, click on “Field groups”.
5. You should now see all the field groups that currently exist for the entity.
6. In the list of field groups, click on the field group you want to view the details for.
7. In the field group details you will see two lists side-by-side. The first one is titled “Entity fields” and it lists all the field for the entity.  The second one is titled “Field group fields” and it lists the fields that are currently a part of the field group that you are viewing.

### Modifying a Field Group
1. Follow steps outlined earlier to View a Field Group
2. To add a field to a field group, double-click on a field name in the “Entity fields” list. You can also drag and drop fields from the “Entity fields” list to the “Field group fields” list.
3. To remove from a field group, click on the “X” next to the field name in the “Field group fields” list.
4. At the bottom of the page, click on the “Save” button to save your changes.

### Creating a new Field Group
1. In the left navigation bar, click on “Entities”.
2. If you have access to more than one database ensure you have the right database selected using the dropdown above the list of entities.
3. In the list of entities, click on the entity you want to view the field group for.
4. In the header above the list of fields, click on “Field groups”.
5. Towards the top of the screen, click on the “New field group” action.
6. Provide a name, display name and description for the field group.
7. In the header above, click on “FieldGroupFields”.
8. To add a field to a field group, double-click on a field name in the “Entity fields” list. You can also drag and drop fields from the “Entity fields” list to the “Field group fields” list.
9. Towards the bottom of the screen, click on the “Save” button to save your changes.

### Deleting a Field Group
* Deleting a field group is not currently supported. This will be enabled sometime in the future.

### Viewing and editing Field Group data in Excel
1. In the left navigation bar, click on “Entities”.
2. If you have access to more than one database ensure you have the right database selected using the dropdown above the list of entities.
3. In the list of entities, click on the entity you want to export the field group data for.
4. In the header above the list of fields, click on “Field groups”.
5. You should now see all the field groups that currently exist for the entity.
6. You should also see an Excel icon beside each field group. Note that the Excel icon will only be enabled if the field group has fields.
7. Click on the Excel icon for the field group that you want to Open in Excel. A workbook will be generated containing the entity field list, the Excel Add-in, and a pointer to your environment. 
8. Open the generated workbook that is provided by the browser. 
9. Once the workbook is open, enable editing. The Excel Add-in will then read the desired data into the workbook. For more details please see: [Open entity data in Excel](https://powerapps.microsoft.com/en-us/tutorials/data-platform-interactive-excel/ "Open entity data in Excel")

## Framework usage of Field Groups
The framework uses default field groups to help speed up application authoring and customization. Listed below are some places where you can currently see field groups in action. This list of places where field group will be used will continue to grow in future releases.

* **Lookup control**: If one of the fields you add on your screen is a reference to another linked entity, the field is rendered as a lookup control (picklist). When a user clicks on the lookup control to select a record from the linked entity the fields displayed are determined by the DefaultLookup field group on the linked entity. *Note: Currently only the first two fields of the DefaultLookup field group are used.*

* **Creating an app from the Common Data Service data**: When you jump start an app by choosing the option to create an app from data *(PowerApps Studio > New  > Create an app > Start with your data > Common Data Service)* the framework automatically generates screens for you for the entity you specify. The Display Form control and Edit Form control used on the Display and Edit screens use the DefaultDetails field group to determine which fields will be added by default to those screens.
