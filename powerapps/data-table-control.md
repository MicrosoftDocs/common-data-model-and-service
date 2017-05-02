
<properties
	pageTitle="Introducing the data table control in PowerApps"
	description="Introduction of the data table control in PowerApps."
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
   
# Introducing the Data table control in PowerApps
   
Imagine you have a collection of data (a list sales orders, a set of service tickets, a directory of contacts, etc.) that you want to display in your PowerApp in a table-like form, where each column represents a field and each row represents a record. While you could have roughly simulated that rendering in the past with some effort, you now have an easy and quick way to achieve this very standard visualization by using the new Data table control that was recently added to PowerApps. You simply need to link your Data table to a data source and then select the fields you want to display. 

![Data table control](Media/dataTableExample.png "Data table control")

## What’s included in this initial version of the Data table control?

+ **Connected data sources** – The Data table can currently be used with in conjunction with connected data sources.  We will be adding support for static data sources like Excel and Collections soon.  

+ **Single-record selection** – Users can only select one row at a time from the Data table control.  The Selected property can then be used to access field values from that row and to provide data context to other PowerApps controls.    

+ **Read-only data** – Like the Gallery control, the data shown in the Data table control is read-only.  Record editing can be accomplished by linking the selected row in the Data table to an Edit form (or other editable controls).  

+ **Column headings** – A row of column headings is shown at the top of the Data table for reference. The Data table currently allows you to restyle the column headings to get just the visual appearance you’re looking for.  

+ **Broad customization support** – Several properties have been exposed to allow restyling and customization of the Data table.  This notably includes being able adjust the styling for the entire set of data rows, the selected row, and the row the mouse is currently pointing to.  Finer-grained customization is planned for an upcoming release of the control.   

## What features are coming soon

+ Instead of the Data table starting with no fields, we plan to seed the Data table with default fields for connectors that support this capability (e.g. Common Data Service).  
+ Data source support will soon be expanding to cover static data sources like Excel and Collections.
+ We plan to allow fields in the Data table to render as hyperlinks for navigating to other screens or performing other actions.  
+ Finer-grained control of the Data table is planned by allowing selection of individual columns to expose more targeted customizations at the column level. 
+ Support for copy and paste of the Data table control is being looked at to improve the ability to reuse the control.
+ The Data table control will soon support paging through scrolling.

## We want to hear your feedback

We hope you find the Data table control useful in easily building apps with the visuals you want. To learn more about the Data table control, its properties, and its usage, please refer to this article: Data table controls in PowerApps.  As always, we are extremely interested in any feedback you have on this new feature.  You are free to leave comments on this page or on [PowerApps community](http://aka.ms/powerapps-community "PowerApps community").  I look forward to incorporating your feedback and suggestions to improve the control and PowerApps as a whole!   

