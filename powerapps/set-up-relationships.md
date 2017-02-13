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

To represent data in a relational database, you must determine the data schema by defining the types of your fields and how your entities relate to each other. Typically, data becomes much more interesting when it's linked to other data through relationships. The creation of successful data models is partly an art and partly a science.

For example, you're defining entities to represent authors and the books that they write. Clearly, an author can have more than one book to his or her credit. In this case, the author and his or her books are said to be in a one-to-many (1:many) relationship. In this topic, we will explain how to create 1:many relationships in the maker portal. Note that this topic doesn't cover the issues that arise when you must manage more complicated cases, where more than one author is mapped to one or more books (a so-called many-to-many relationship).

## Create an Author entity
First, we will create an entity that is named **Author** in your environment. Be sure to choose the names of your entities carefully, because you can't rename entities after they have been created. For more information about entities, see [Understand entities in the common data service](https://powerapps.microsoft.com/en-us/tutorials/data-platform-intro/).

Enter the display name of the entity and a description. For our scenario, we require the name of the author. Therefore, create a field of the **PersonName** type, and name it **Name**. The field doesn't have to be unique, but it should be required. (You set the requirement options in the **Properties** pane.)

Next, we require a field for the author's date of birth. Therefore, create a field of the **Date** type, and name it **DOB**.

**Note:** You can easily identify the author in a powerapp by adding the **Name** field to the **Default lookup** field group.

When you added your fields, you might have noticed that some fields were automatically created. One of these fields is named **Primary ID**, and the **Autonumber** type is assigned to it. Select this field, and then look in the **Properties** pane. You will see that this field is unique. In other words, it's guaranteed that every value will be used only one time in this entity. You don't have to manage these values yourself. Every time that you add a new record to the entity, the system will assign a new value. This field is what is often known as the entity's _primary key_.

## Add data to the Author entity
Next, we will add some data to the Author entity. You can use several methods. For example, you can use Microsoft Excel. On the **Entity** page, click **Open in Excel**. Excel starts, and the PowerApps add-in is loaded. In the worksheet, add the following information.

| Primary ID | Given name of Name | Middle name of Name	| Surname of Name | Date of Birth |
| ----------:| -------------------| --------------------| ----------------| -------------:|
000001	| Edgar	| Frank | Codd | 1923-08-19 |
000002	| Christopher |	J. | Date | |

Notice that, when you click **Publish** on the left side of the PowerApps add-in pane, the values for the **Primary ID** field are automatically calculated, and the entity now contains data. To verify this fact, click **Refresh**, and then view the **Data** tab of the entity.

## Add the Book entity
Next, we will create the entity that represents the books that the authors wrote. This entity will be named **Book**, and it will have two required fields, **Title** and **ISBN**. A unique **Primary ID** field will be created automatically. You can add additional fields, such as **Date of publication** and **Synopsis**, as you require.

## Link two entities
Although we have now created the two entities, they aren't yet linked to show that there is a relationship between them. To establish that relationship, open the Book entity, and then, on the **Relationship** tab, enter information about the Author entity. 

**Note:** The relationship is always set up on the child entity. This entity is the "many" part in the term _1:many relationship_.

If you go back to the Book entity, you will see that a new field has been added. Because you added the relationship to the Author entity, the new field is named **Author\_** (the name of the parent entity, to which an underscore character (\_) has been appended). This field has a special type, **Lookup**. This field is what is known as the _foreign key_. The relationship between an author and his or her books is enforced by the fact that the foreign key field for the author's books (**Author\_**) is set to the author's primary key value. For example, if one author has a primary key value of **1234**, the **Author\_** field for the author's books is also set to **1234**. 

Next, we will add information about the books that have been written by the authors that we added earlier. In this way, we can see how the foreign key works together with the primary key. Select the Book entity again, and click **Open in Excel**.

Remember that the **Primary ID** field will be filled in when the data is published back to the database. However, you can enter information in the other fields. Start with the **ISBN** and **Name of Book** fields.

| Primary ID | ISBN | Name of Book | Author |
| ----------:|------| -------------| -------|
|            | 0-201-14192-2| The Relational Model for Database Management   |        |
|            | 10.1.1.86.9277 | Relational Completeness of Data Base Sublanguages | |  
|            | 978-0321197849 | An Introduction to Database Systems	| |

The **Author** field is the foreign key and is mapped to the primary key in the Author entity. When the cells in the **Author** column are selected, the primary keys in that entity appear in the pane on the right side of the Excel window, as shown in the following illustration.

	![Excel showing book data](./Media/Excel showing Book data.png "Excel showing book data")

To update the **Author** field, just select the row.

You can now easily create a powerapp that you can use when you go to a bookstore to stock up on great books. The powerapps designer will do all the "heavy lifting" for you if you have it base the app that is created on the definition of the two entities and their relationships. For more information about that process, see [Generate an app by using a Common Data Service database](https://powerapps.microsoft.com/en-us/tutorials/data-platform-create-app/).
