<properties
	pageTitle="Generate an app using a Common Data Service database | Common Data Service"
	description="Generate an app to add, update, and delete records"
	services="powerapps"
	documentationCenter="na"
	authors="robinarh"
	manager="robinarh"
	editor=""
	tags=""/>

<tags
   ms.service="powerapps"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="10/18/2016"
   ms.author="robinarh"/>

# Generate an app using a Common Data Service database #

[AZURE.VIDEO nb:cid:UUID:e0d83908-aedd-4db3-8ea9-2dbd4695c662]

Generate an app automatically to manage data that's stored in the Common Data Model. Manage data in one of many standard entities (which are built in to the model) or a custom entity (which you or someone else in your organization created).

If you're unfamiliar with the Common Data Service, see [Understand entities](data-platform-intro.md).

As this topic describes, you can automatically generate an app based on a single entity that you specify. As [build an app from scratch](data-platform-create-app-scratch.md) describes, you can also build an app based on more than one entity.

Every app that PowerApps generates has three screens by default:

- The browse screen shows a subset of fields (perhaps just one), a search bar, and a sort button so that users can easily find a specific record.

	![Browse screen](./media/data-platform-create-app/browse-screen.png)

- The details screen shows more or all fields for a specific record.

	![Details screen](./media/data-platform-create-app/details-screen.png)

- The edit screen provides UI elements in which users can create or update a record and save the changes.

	![Edit screen](./media/data-platform-create-app/edit-screen.png)

**Note**: When you generate an app from the Common Data Service, you don't need to create a connection from PowerApps, as you do with data sources such as SharePoint, Dynamics CRM, and Salesforce. You need only specify the entity that you want to show, manage, or both in the app.

## Generate an app ##
1. Create a Common Data Service database. For more information, see [Create a Common Data Service database](create-cdm-database.md).
1. On [powerapps.com](https://web.powerapps.com), in the left navigation pane, click **New app**.
1. In the dialog box that appears, click or tap **PowerApps Studio for web**. (You can also choose **PowerApps Studio for Windows** and follow the instructions to install **PowerApps Studio for Windows**. The instructions that follow use **PowerApps Studio for web**, but are similar for the Windows app.)
1. Under **Start with your data**, click or tap **Phone layout** on the **Common Data Service** tile.
1. Under **Choose an entity**, click or tap the **Contact** entity.
1. Click or tap **Connect** to automatically generate an app. (You can choose to take an intro tour at this point. You can always take the tour later by clicking or tapping the question-mark icon near the upper-right corner and then clicking or tapping **Take the intro tour**.)

## Customize the browse screen ##
1. In the right-hand pane, click or tap the layout that shows just a heading.

	![Choose layout](./media/data-platform-create-app/choose-layout.png)

1. Under the search box on the **Contact** screen, click or tap the **Text box** control to select it. The control doesn't have a border by default, so it doesn't appear until you select it. Whenever you select a control, a selection box (with resize handles) surrounds that control.
1. In the right-hand pane, click or tap on Data Sources and then click or tap the down arrow under **Contact** to open the list of fields.
1. Click or tap **Last Name** to show data from that field in the **Text box** control that you selected.
1. Select the gallery on the **Contact** screen by clicking or tapping any name except the top one. A selection box surrounds the gallery.
1. Copy this formula by highlighting it and then pressing Ctrl-C.
<br>**SortByColumns(Search(Contact, TextSearchBox1.Text, "LastName"), "LastName", If(SortDescending1, Descending, Ascending))**
1. Near the upper-left corner, ensure that the property list shows **Items**.
1. In the formula bar, highlight the default formula.

	![Default value of the Items property](./media/data-platform-create-app/default-items.png)

1. Press Delete to delete the default formula, and then paste the formula that you just copied.	The names are sorted alphabetically in the gallery.
1. (optional) If the users of this app won't have touch screens or mousewheels, click or tap the **Gallery** tab, and then click or tap **Show Scrollbar**.

	**Note**: If the **Gallery** tab doesn't appear, ensure that the gallery is still selected.

	![ShowScrollbar property](./media/data-platform-create-app/show-scrollbar.png)

## Test the browse screen ##
1. Open Preview mode by pressing F5 (or by clicking or tapping the play icon near the upper-right corner).

	![Open Preview mode](./media/data-platform-create-app/open-preview.png)

1. Scroll through all the records by using a touch screen, by using a mousewheel, or by pointing to the gallery with a mouse so that the scrollbar appears.

	![Scroll records](./media/data-platform-create-app/scroll-records.png)

1. Near the upper-right corner, click or tap the sort button one or more times to change order in which the names are listed.

	![Change sort order](./media/data-platform-create-app/sort-button.png)

1. In the search box, type a letter such as "w" to show only those names that contain the letter that you typed.

	![Filter list](./media/data-platform-create-app/search-w.png)

1. Click or tap the arrow to the right of the first name in the list.

	![Right arrow](./media/data-platform-create-app/right-arrow.png)

1. Return to the design workspace by pressing Esc (or by clicking or tapping the close icon near the upper-right corner, under the title bar).

	![Close Preview mode](./media/data-platform-create-app/close-preview.png)

## Customize the details screen ##
1. Click or tap the **CellPhone** card to select it.

	![Select card](./media/data-platform-create-app/select-card.png)

1. In the right-hand pane, click or tap the eye icon for the **CellPhone** card to hide it.

	![Hide card](./media/data-platform-create-app/hide-card.png)

1. Repeat the previous step for each of these cards:

	- **Description**
	- **Facebook**
	- **FullName**

1. Click or tap the **FirstName** card to select it.

	![Select FirstName card](./media/data-platform-create-app/select-firstname.png)

1. Drag its title up until the **BusinessPhone** card is highlighted.

	![Move FirstName card](./media/data-platform-create-app/move-card.png)

1. Release the mouse button so that the **FirstName** card appears above the **BusinessPhone** card.

	![Drop FirstName card](./media/data-platform-create-app/drop-card.png)

1. Repeat the last three steps except move the **LastName** card so that it appears between the **FirstName** card and the **BusinessPhone** card.

## Customize the edit screen ##
1. Near the upper-right corner of the details screen, click or tap the pencil icon to select it, and then click or tap it again to open the edit screen.

	![Edit record](./media/data-platform-create-app/edit-record.png)

1. Repeat the steps in the previous procedure to hide and move the cards on the edit screen as you did on the details screen.

## Test the details and edit screens ##
1. In the left navigation bar, click or tap the top thumbnail to display the browse screen.

	![Thumbnail for browse screen](./media/data-platform-create-app/browse-thumbnail.png)

1. Open Preview mode by pressing F5 (or by clicking or tapping the play icon near the upper-right corner).

	![Open Preview mode](./media/data-platform-create-app/open-preview.png)

1. In the upper-right corner of the browse screen, click or tap the plus icon to create a record.

	![Add record](./media/data-platform-create-app/add-record.png)

1. Add whatever data you want, and then click or tap the checkmark icon to save your new record and return to the browse screen.

	![Save record](./media/data-platform-create-app/save-record.png)

1. If you haven't already, show all records by removing any text from the search bar (near the top of the browse screen).

	![Clear the search box](./media/data-platform-create-app/clear-search.png)

1. Find the record that you just created, and click or tap the arrow to its right to show the record in the details screen.

	![Save record](./media/data-platform-create-app/show-details.png)

1. In upper-right corner, click or tap the pencil icon to show the record in the edit screen.

	![Edit record](./media/data-platform-create-app/edit-record.png)

1. Change the data in one or more fields, and then click or tap the checkmark icon to save your changes and return to the browse screen.

	![Save record](./media/data-platform-create-app/save-record.png)

1. Find the record that you just updated, and click or tap the arrow to its right.

	![Show details](./media/data-platform-create-app/show-details.png)

1. Near the upper-right corner, click or tap the trash-bin icon to delete the record that you created and updated.

	![Delete record](./media/data-platform-create-app/delete-record.png)
