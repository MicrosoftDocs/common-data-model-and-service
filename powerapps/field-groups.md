 <properties
	pageTitle="Use field groups for app creation | Microsoft PowerApps"
	description="Use field group to standardized app creation across the database."
	services="powerapps"
	documentationCenter="na"
	authors="aneesmsft"
	manager="robinr"
	editor=""
	tags=""/>

<tags
   ms.service="powerapps"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="10/25/2016"
   ms.author="robinr"/>

# Field Groups

Field groups provide a way to group one or more fields of an entity. Field groups can help speed up and simplify the creation and maintenance of apps. A field group contains one or more fields and a field can appear in any number of field groups. A field can not appear more than once in a field group.

Field groups are stored on an entity and are therefore shared across all apps that use the same entity. At any given time there may be many different apps using the same entity and field groups of that entity. This centralization and sharing of field groups helps enforce consistency since a field group will always display the exact same fields wherever it is used. It also eases maintenance since a change to a field group is automatically reflected in all the places using that field group. Field groups help speed up the app authoring and customization process since an application author works with groups of fields rather than individual fields. 

# Default field groups
Common Data Service includes a number of default field groups on entities. These field groups are used in various places to help speed up and ease app creation and customization.

| Default Field Group Name | Description |
|-------------------------|-------------|
|DefaultDetails |Used to display the details of a single record in view and edit.|
|DefaultLookup |Used to display a lookup to select a record.|

# View a field group
1. On [powerapps.com](https://web.powerapps.com), expand the **Common Data Service** section and click or tap **Entities** in the left navigation pane.
1. If you have access to more than one database ensure you have the right database selected using the dropdown above the list of entities.
1. In the list of entities, click or tap the entity you want to view the field group for.
1. In the header above the list of fields, click or tap **Field groups**. You now see all the field groups that currently exist for the entity.
1. In the list of field groups, click or tap the field group you want to view the details for.
1. In the field group details you see two lists side-by-side. One is titled **Entity fields** and it lists all the field for the entity.  The other is titled **Field group fields** and it lists the fields included in the field group.

# Modify a field group
1. View the field group that you want to modify.
2. To add a field, double-click on a field name in the **Entity fields** list. You can also drag and drop fields from the **Entity fields** list to the **Field group fields** list.
3. To remove from a field group, click on the **X** next to the field name in the **Field group fields** list.
4. Click or tap the **Save** button.

# Create a field group
1. On [powerapps.com](https://web.powerapps.com), expand the **Common Data Service** section and click or tap **Entities** in the left navigation pane.
2. If you have access to more than one database ensure you have the right database selected using the dropdown above the list of entities.
3. In the list of entities, click on the entity you want to view the field group for.
4. In the header above the list of fields, click or tap **Field groups**.
5. Towards the top of the screen, click or tap the **New field group** action.
6. Provide a name, display name and description for the field group and click or tap **Next**.
7. Modify the field group as desired and click or tap **Save**.

# Delete a field group
Deleting a field group is not supported.

# View and edit field group data in Excel
1. View the field groups for the entity that you want to examine the data for.
1. There is an Excel icon beside each field group. The Excel icon will only be enabled if the field group has fields.
1. Click on the Excel icon for the field group that you want to Open in Excel. A workbook is generated containing the entity field list, the Excel Add-in, and a pointer to your environment. 
1. Open the generated workbook that is provided by the browser. 
1. Once the workbook is open, enable editing. The Excel Add-in will then read the desired data into the workbook. For more information, see [Open entity data in Excel](data-platform-interactive-excel.md).

# Lookup and app generation with field groups
The default field groups to help speed up application authoring and customization. Some places where you can currently see field groups in action are:

* **Lookup control**: If one of the fields you add on your screen is a reference to another linked entity, the field is rendered as a lookup control (picklist). When a user clicks on the lookup control to select a record from the linked entity the fields displayed are determined by the DefaultLookup field group on the linked entity. Only the first two fields of the DefaultLookup field group are used.

* **Creating an app**: When you generate an app by choosing the option to create an app from data, the screens for the entity you select are automatically created. The **Display Form** control on the **Display** screen and the **Edit Form** control on the Edit screen use the **DefaultDetails** field group to determine which fields will be added by default to those screens.
