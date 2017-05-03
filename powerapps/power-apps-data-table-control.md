<properties
	pageTitle="Data table control in PowerApps"
	description="Data table control in PowerApps."
	services="powerapps"
	documentationCenter="na"
	authors="jasongre"
	manager="kfend"
	editor=""
	tags=""/>

<tags
   ms.service="powerapps"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="04/24/2017"
   ms.author="kfend"/>
   
# Data table control in PowerApps

A control that shows a set of data in a tabular format. 

## Description
The Data table control allows you to display a dataset in a tabular format, which includes column headers for each field that is visualized. As the maker, you have full control over the fields that you want to show from the data source and the order in which the fields appear. The Data table control maintains a Selected property that, like the Gallery, points to the single row that is currently selected, which can be used to link the Data table to other controls.  

## Key properties
[**Items**](https://powerapps.microsoft.com/en-us/tutorials/properties-core/ "Items") – The source of data that appears in the control

**Selected** – The selected row in the Data table


 ## Additional properties
**NoDataText** – The message shown to the user when there are no records to show in the Data table

**SelectedFill** – The background color of the selected row

**SelectedColor** – The color of text in the selected row

[**HoverFill**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "HoverFill") – The background color of the row that the mouse is currently pointing at

[**HoverColor**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "HoverColor") – The color of text in the row that the mouse is currently pointing at

**HeadingFont** – The font of the column headings

**HeadingSize** – The font size of the column headings

**HeadingFontWeight** – The font weight of the column headings

**HeadingFill** – The background color of the column headings

**HeadingColor** – The text color for the column headings

[**Fill**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "Fill") – The default background color for all data rows

[**Color**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "Color") – The default text color for all data rows

[**BorderColor**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "BorderColor") – The color of a Data table’s border

[**BorderStyle**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "BorderStyle") – Determines whether a Data table’s border is Solid, Dashed, Dotted, or None

[**BorderThickness**](https://powerapps.microsoft.com/en-us/tutorials/properties-color-border/ "BorderThickness") – The thickness of the Data table’s border

[**Font**](https://powerapps.microsoft.com/en-us/tutorials/properties-text/ "Font") – The default font for all data rows

[**FontWeight**](https://powerapps.microsoft.com/en-us/tutorials/properties-text/ "FontWeight") – The default font weight for all data rows

[**Size**](https://powerapps.microsoft.com/en-us/tutorials/properties-text/ "Size") – The default font size for all data rows

[**X**](https://powerapps.microsoft.com/en-us/tutorials/properties-size-location/ "X") – The distance between the left edge of a Data table and the left edge of its parent container (or screen if there is no parent container)

[**Y**](https://powerapps.microsoft.com/en-us/tutorials/properties-size-location/ "Y") – The distance between the top edge of a Data table and the top edge of its parent container (or screen if there is no parent container)

[**Width**](https://powerapps.microsoft.com/en-us/tutorials/properties-size-location/ "Width") – The distance between a Data table’s left and right edges

[**Height**](https://powerapps.microsoft.com/en-us/tutorials/properties-size-location/ "Height") – The distance between a Data table’s top and bottom edges

[**Visible**](https://powerapps.microsoft.com/en-us/tutorials/properties-core/ "Visible") – Determines whether a Data table appears or is hidden


## Related functions
[**Filter(DataSource, Formula)**](https://powerapps.microsoft.com/en-us/tutorials/function-filter-lookup/ "Filter(DataSource, Formula)")

[**Search(DataSource, SearchString, Column)**](https://powerapps.microsoft.com/en-us/tutorials/function-filter-lookup/ "Search(DataSource, SearchString, Column)")

[**Lookup(DataSource, Formula)**](https://powerapps.microsoft.com/en-us/tutorials/function-filter-lookup/ "Lookup(DataSource, Formula)")

## Examples
### Basic data table usage 
1. Create a blank Tablet app.
2. On the **Insert** tab, click or tap Data table.

   ![Add a data table control to a screen](Media/insertDataTable.png "Add a data table control to a screen")

   A Data table control is added to the screen. 

3. Rename the Data table control to SalesOrderTable, and resize it to cover the entire screen. 
4. In the right-hand pane, click or tap the down arrow next to the *No data source selected* text, and then click or tap **Add a data source**.

   ![Add a data source](Media/addDataToDataTable.png "Add a data source")
    
5. In the list of connections, click or tap the connection for your database.

   ![Choose the connection for your data source](Media/chooseCDSDataTable.png "Choose your data connection")

6. In the list of entities, click or tap **Sales order**, and then click or tap **Connect**.

   ![Choose the **Sales order** entity](Media/chooseSODataTable.png "Choose the Sales order entity")

   The Data table is now attached to the **Sales order** data source; however, no data will be shown until the user picks the desired fields.   

7. In the right-hand pane, select the fields you want to display. For this example, choose SalesOrderId, Account, OrderDate, and Status. 

   The Data table is populated with data that is based on the selected fields.
   
   ![Data table](Media/preOrderDataTable.png "Data table")

8. Reorder the fields by dragging and dropping them in the right hand pane.

   ![Reorder fields as desired](Media/fieldReorderDataTable.png)

   The Data table will update to show the fields in the new order.
   ![Data table](Media/postOrderDataTable.png "Data table")

### Restyle the Data table header
1. Click the **Advanced** tab in the right hand pane.
2. Click or tap the input box for the **HeadingFill** property, and change the value to **RGBA(62,96,170,1)**.
3. Click or tap the input box for the **HeadingColor** property, and change the value to **White**.
4. Click or tap the input box for the **HeadingSize** property, and change the value to **14**. 
   ![Data table](Media/restyledDataTable.png "Data table")

### Connecting a data table to another control
1. Add an Edit form to the screen.
2. Resize the Data table and Edit form so that the Data table uses the left portion of the screen and the Edit forms occupies the right portion of the screen.

   ![Data table and edit form on the same screen](Media/dataTableEmptyForm.png "Data table and edit form on the same screen")
   
3. Connect the Edit form to the Sales order data source. 
4. In the right-hand pane, select the fields you want to display in the Edit form. For this example, select SalesOrderId, Status, Name, Description, and Total amount.

   ![Edit form showing five fields](Media/dataTableDisconnectedForm.png "Edit form showing five fields")
   
3. Click the **Advanced** tab in the right hand pane. 
4. Set the Item property on the Edit form to **SalesOrderTable.Selected** so that the edit form shows information from the Data table's selected row. 

   ![Edit form connected to data table](Media/connectedFormDataTable.png "Edit form connected to data table")
