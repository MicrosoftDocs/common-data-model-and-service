<properties
	pageTitle="Set up relationships | Microsoft PowerApps"
	description="Setting up relationships."
	services="powerapps"
	documentationCenter="na"
	authors="pvillads"
	manager="kfend"
	editor=""
	tags=""/>

<tags
   ms.service="powerapps"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="02/13/2017"
   ms.author="kfend"/>

# Set up relationships

When you want to represent data in a relational database, you must determine the data schema by defining the types of your fields, and how your entities relate to each other. Typically, data becomes much more interesting when it is linked to other data through relationships. Creating successful data models is part art and part science. In this topic we will explain how to create 1 to Many relationships in the maker portal.

Let's say you were defining entities to represent authors and the books they write. Clearly, an author can have more than one book to his credit, which is what is known as a 1:Many relationship. In this topic we will not explore the problems involved in managing more complicated cases of mapping more than one author to one or more books, what is colloquially known as a Many to Many relationship.

## Create an Author entity
Let’s start by creating an entity called **Author** in your environment. Make sure that you choose the name of entities judiciously, as there is no way to rename them once they are created. For more information about entities, see [Understand entities in the common data service](https://powerapps.microsoft.com/en-us/tutorials/data-platform-intro/).

Enter the entity display name and description. For the purpose of our scenario, we need the name of the author, so create a field called **Name** of the type **PersonName**. The field does not need to be unique, but it should be required. REquirement options are set in the **Properties** window. Next, add a Date of Birth field called **DOB** with the type, **Date**. 
**Note:** You can easily identify the author in a powerapp by adding the **Name** field to the **Default lookup** field group, .

When you added your fields, you may have noticed that a few fields were automatically created. One of these fields is called **Primary ID** with an assigned type, **Autonumber**. If you select this field, you can see in the **Properties** pane that this field is unique in that each value is guaranteed to be used only once in this entity. You do not need to manage these values yourself. Every time tha tyou add a new record to the entity, the system will assign a new value. This is what is often called the entity’s **_primary key_**.

## Add data to the Author entity
Now we will add some data to the Author entity. One way to do this is to use Microsoft Excel. On the **Entity** page, click **Open in Excel**. Excel will open with the PowerApps add-in loaded. In the worksheet, add the following information:

| Primary ID | Given name of Name | Middle name of Name	| Surname of Name | Date of Birth |
| ----------:| -------------------| --------------------| ----------------| -------------:|
000001	| Edgar	| Frank | Codd | 1923-08-19 |
000002	| Christopher |	J. | Date | |

Notice that when you click **Publish** on the left side of the PowerApps add-in window, the values for the **Primary ID** field are automatically calculated and the entity now contains data. To verify, click **Refresh**, and on the **Data** tab of the entity.

## Add the Book entity
Next, we will create the entity that represents the books that the authors wrote. For this, we will create an entity called Book, with two required fields, **Title** and **ISBN**. A unique **Primary ID** field will automatically be created. Add additional fields, such as **Date of publication** and **Synopsis** as needed.

## Link two entities
We have created the two entities, but but they are not yet linked to show that there is a relationship between them. To establish that relationship, open the Book entity, click the **Relationship** tab, and enter information about the Author entity. 
**Note** The relationship is always set up on the child entity, which is also the the Many part of the 1 to Many relationship.

If you go back to the Book entity, you will see that because you added the relationship to the Author entity, a new field called Author\_ (the field name is the name of the parent entity with an underscore character appended to it) was added. This field has a special type called **Lookup**. This is  what is known as the **_foreign key_**. For example, there is an author that has a primary key value of **1234**. The relationship between this author and their books is enforced by the fact that the author's books have the foreign key field, Author_, set to that value.

Now, we will add information about books that are written by the authors, we added earlier so that we can see how the foreign key works with the primary key. Select the Book entity again, and click **Open in Excel**.

Remeber that the **Primary ID** field will be populated when the data is published back to the database. However, you can enter information in the rest of the fields. Start with the **ISBN** and **Name of Book** fields: 

| Primary ID | ISBN | Name of Book | Author |
| ----------:|------| -------------| -------|
|            | 0-201-14192-2| The Relational Model for Database Management   |        |
|            | 10.1.1.86.9277 | Relational Completeness of Data Base Sublanguages | |  
|            | 978-0321197849 | An Introduction to Database Systems	| |

The **Author** field is the foreign key, that maps back to the primary key in the Author entity. When Excel has the cells in this column selected, it will show the primary keys in that entity in the pane on the right hand side, as shown below:

	![Excel showing book data](./Media/Excel showing Book data.png "Excel showing book data")

To update the **Author** field, just select the row.

You can now easily create a powerapp that you can use when you are in the bookstore wanting to stock up on great books. The powerapps designer will do all the heavy lifting for you if you ask it to create the app based on the definition of the two entities and their relationships. For more information about that process, see [Generate an app by using a Common Data Service database](https://powerapps.microsoft.com/en-us/tutorials/data-platform-create-app/).

