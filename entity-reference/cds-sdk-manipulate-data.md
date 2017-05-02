---
title: "Manipulate your data using the Common Data Service SDK | Microsoft Docs"
description: ""
author: "pvillads"
manager: "robinarh"
ms.date: "02/03/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "C#, SDK"
audience: "Developer"
ms.assetid: "d4ee3160-96cb-47b7-8e24-cdc57c9d8420"
---

# Manipulate your data using the Common Data Service SDK

In this document we will discuss how the C# SDK for CDS can be used to do work with data stored in the CDS data cloud. The examples herein deal with CRUD operations on business data stored in relational data stores.

## Background
The C# CDS SDK is designed for building responsive applications that leverage the backing computational resources as effectively as possible. The operations performed by the SDK are made available in the target language (C# in this case) as an embedded domain specific language that is designed to handle any data access request against any data store. Even though you can access the data without using an SDK you will find that using one will raise the abstraction level, allowing you to focus on your business logic needs, rather than on transport protocols, JSON documents etc. You will  have seen this approach, that details about how data is access are hidden to the user, before - this is the same strategy used in LINQ, but the language used here is more geared towards ERP applications and is backed by a solid modeling framework describing your entitysets.

In the examples below we will be demonstrate common data access scenarios using the Out-of-Box entities (henceforth OOBs), i.e. the entitysets that are shipped along with the SDK. Using these entitysets makes the examples very simple since the tooling in the maker portal has created typesafe representations that are easy to work with. While this the recommended way to work with entitysets, it is quite possible to work with entitysets that are not defined in this way; you will see how this is done at the end of this document. You can see how the OOBs are defined (the fields, the relationships the entityset has to other entitysets and so on) in the maker portal in your environment. 

## Terminology
The SDK uses the term entityset where other material describing relational databases would use the term table. The individual row in the tables are called entities. While this is consistent with current nomenclature, it  may be confusing at first, since the maker portal, that allows editing of entitysets, used the work entity (instead of entityset) as a synonym for tables. 

## Programming model
The programming model chosen for the C# SDK uses all the facilities from C# to build an embedded domain specific language. The majority of the APIs offered by the SDK are implemented as aynchronous calls. Aynchronous calls are executed such that an awaited call will not block the thread that it is running on; instead the flow of control will immediately return to the caller. Once the call finishes, the execution will resume from the continuation of the await call. 

Most of the APIs are written to support lambda functions. We explain this below when we run through some examples. 

There is no concept of an explicit transaction to contend with. As you will see, you add all the records that are subject to modification to what is known as a batch executer. The batch executer is then charged with managing the transaction in the most effective manner, running as quickly as possible to maximize efficiency. 

## The client instance
Before you do any operation with the data in CDS you need to be authenticated by the Azure Active Directory (AAD). The system will do this based on a set of configuration settings that are set up in configuration files in your project. In that configuration file (that is typically called App.config) you will specify the Application Id that you registered on the Azure portal, the ID of the environment that contains your data, and how you want to authenticate.

## Inserting data
We will start our discussion with inserting data into an entityset in the backend database, since it is very simple to do. Since the entitysets are represented as plain old C# classes, they can easily be dealt with in C#. Let us walk through an example below:

```cs
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace SdkConsoleApp
{
    // Include the CDS namespaces for readability
    using Microsoft.CommonDataService;
    using Microsoft.CommonDataService.CommonEntitySets;
    using Microsoft.CommonDataService.Configuration;
    using Microsoft.CommonDataService.ServiceClient.Security;

    using System.Threading.Tasks; // Needed for async

    class Program
    {
        private static async Task InsertAsync(Client client)
        {
            // Insert Surface and Phone product lines
            var surfaceCategory = new ProductCategory()
            {
                Name = "Surface",
                Description = "Surface produce line"
            };
            var phoneCategory = new ProductCategory()
            {
                Name = "Phone",
                Description = "Phone produce line"
            };

            var executor = client.CreateRelationalBatchExecuter(
                    RelationalBatchExecutionMode.Transactional);

            executor
                .Insert(surfaceCategory)
                .Insert(phoneCategory);

            await executor.ExecuteAsync();
        }

        static void Main(string[] args)
        {
            using (var client = ConnectionSettings.Instance.CreateClient().Result)
            {
                Task.Run(async () => await InsertAsync(client));
            }
            System.Console.ReadLine();
        }
    }
}

```
The code start by creating a client instance. In this case, the user name is used to create the security principal htat is then used to create the client. Since the client holds unmanaged resources and it implements IDisposable, it is a good practice to create the client in a using statement. The client instance is passed to the InsertAsync method that does the actual work.

The InsertAsync method is asynchronous (as indicated by the async keyword and reflected in the naming convention, which is another good practice). In this example, two product categories are created by instantiating the out-of-box entityset types. These are the entities to be inserted. Insertions (and all other data manipulation) is done through executors, like the one created in the next lines. The entities created are then added to the executor by using the Insert method. When the ExecuteAsync method is called on this executor, the system will serialize the entities, send them to the server side over the wire, start a transaction and insert the entities. Since the call to the ExecuteAsync method is asynchronous, the call is not blocking. As mentioned above, this paradigm is used extensively in the C# SDK: You never explicitly manage a transaction, you let executers do that on your behalf. The code inserts two entities in the executer, through a fluent syntax chaining the calls. The APIs are created to encourage this style, but you can certainly do the insertions as two different calls to Insert.

<!---
Describe the InsertAndRetrieveEntity
TODO: Create a more elaborate example where 1:n data is stored in one transaction.

-->

## Reading data from Out of Box Entitysets
In this section we will go through how to select data that is stored in the CDS relational backend. We will start with some very simple examples and build on them to understand more complex scenarios.

Let's start by walking through getting some data from the ProductCategory OOB entityset. This entityset (and most of the other entitysets that are shipped out of the box) have data in them, so you can see the effect of the operations. The easiest way to do this is to use the View Data on the entityset from within the maker portal.

```cs
static async Task SimpleSelectAsync(Client client)
{
    var queryBuilder = client.GetRelationalEntitySet<ProductCategory>()
        .CreateQueryBuilder();

    var query = queryBuilder
        .Where(pc => pc.Name == "Electronics")
        .OrderByAscending(pc => new object[] { pc.CategoryId })
        .Project(pc => pc.SelectField(f => f.CategoryId)
            .SelectField(f => f.Name)
            .SelectField(f => f.Description));

    // Execute the query:
    OperationResult<IReadOnlyList<ProductCategory>> queryResult = null;
    var executor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult);

    await executor.ExecuteAsync();

    foreach (var pc in queryResult.Result)
    {
        Console.WriteLine(pc.Name);
    }
}
```
Again we do the work with an asynchronous method. We start off by creating a queryBuilder based on the entityset that we wish to query (ProductCategory in this case). The query builder is used as a starting point to adding the parts that define the query. In this case we are looking for product categories with the name "Electronics", ordered by the category Id. We only need three field values: The category Id, the name and the description. Once the query has been created, it can be used by another executor to fetch the records. 

<!---
You can do multiple queries at the time.

            selectExecutor
                .Query(queryProductExtension, out productExtensionResult)
                .Query(querySampleEntity, out productCategoryResult)
                .Query(queryTeam, out teamResult)
                .ExecuteAsync().Wait();
-->                

There are a few interesting things to notice here. The where clause is expressed using a lambda function. It is crucial to understand that the lambda functions used in this context are never actually executed. They merely serve to express the intention of the programmer. When the query is executed (in the executer), the lambda functions is translated to a query that is understood by the backend: The lambda function, then, serves as a structure in which the expression is expressed. 

Using lambdas has several benefits, the most important being that the tooling in Visual Studio provides a great experience based on its knowledge of the entitysets involved. The same strategy is used when specifying the sorting option; here a lambda is presented that maps a ProductCategory instance (called pc in this case, but this naming has no significance except in the scope of the lambda function) onto an array of fields to order by. Finally, the projection is specified, i.e. the data required from each entity matched by the query. In this case we are interested in the fields listed in the projection clauses, another lambda taking a ProductCategory instance and returning the fields to include. Note that, for performance reasons, there is no option to automatically select all fields.

The out parameter of the Query method on the executer is used to enumerate the results when the await returns in the queryResult variable. The type of this variable indicates that the result is a read only list of product category entities, which can be conveniently be enumerated.

### Joining data from multiple entitysets
In the examples above we have been dealing with single entitysets. However, this is a rare scenario: Typically the requirements specify that entities should be read from several entitysets and joined together to create useful results. In this section we see how this is done in the C# SDK.

#### Joins
The most common way of acheiving joins is by specifying the join clause on the query. Since the entitysets carry with them a lot of metadata describing the relationships that hold between them, there is typically no need to specify the fields used to do the join in the query.

<!---
TODO: Create a more elaborate example where 1:n data is stored in one transaction.
Use PRoduct / Product categories. Notice how the children appear as a collection, rather than the flat model that is used in SQL
Show what the markup on the POCO to link the 1:n looks like.
Use Project related 

This example is found in 
C:\Users\pvillads\Desktop\D365-CDM-SampleClient\src\Samples\SampleLibrary\WorkWithManyToManyRelationship\WorkWithManyToManyRelationship.cs:

           var query = courseRegistrationEntitySet
                .CreateQueryBuilder()
                .InnerJoin(c => c.StudentID)
                .InnerJoin((c, s) => c.CourseID)
                .Where((r, s, c) => s.Name == "Tom")
                .Project(
                        r => r.SelectField(i => i.CourseRegistrationID),
                        s => s.SelectField(i => i.StudentID).SelectField(i => i.Name),
                        c => c.SelectField(i => i.CourseName));


-->

#### Zips
In the example above you saw how joins internally took advantage of the relationships that are set up between the entitysets that are involved in the joins. While this has several advantages in terms of simplicity, there is still cases where you have not modeled any relationships and you need to do a join regardless. For this purpose you can use the Zip clause, where you specify both the joined entityset and the relationship that defines the join.

<!---
C:\Users\pvillads\Desktop\D365-CDM-SampleClient\src\Samples\SampleLibrary\ProdVarianceCalc\VarianceCalcWorker.cs

            var producedProducts = cdmClient.GetRelationalEntitySet<ProducedProducts>();

            var producedProductQuery = producedProducts
                .CreateQueryBuilder()
                .InnerZip<ProductVarianceCalc>((pp, p) => pp.ProductId == p.Id)
                .Where((pp, p) => pp.ProductionOrderId == order.Id)
                .Project(
                    pp => pp.SelectField(i => i.Quantity).SelectField(i => i.QuantityUoM).SelectField(i => i.ProductId)
                    .IncludeRelated(i => i.ProductPrice)
                        .ProjectRelated(price => price.SelectField(i => i.PriceQtyUoM))
                    .IncludeRelated(i => i.Product)
                        .ProjectRelated(product => product.SelectField(i => i.CostingMethod).SelectField(i => i.InventoryUnit)),
                    price => price.SelectField(i => i.CostingMethod));

-->

### Grouping data
In this section we introduce the group by clause that allows you to group data.

<!---
Here is a description from a LINQ site: https://visualstudiomagazine.com/articles/2017/02/01/grouping-results-in-linq.aspx

The first step is to process the collection of SalesOrders, using the group clause to organize the SalesOrder objects into a new collection held in a class that implements the IGrouping interface. Each item in the collection will itself be a collection of the SalesOrder objects that share a common value. The by clause allows you to specify the property whose value is to be used to organize the SalesOrders and the into clause lets you name the generated collection. This example organizes SalesOrders into a collection called TotaledOrders using the SalesOrder CustomerId property:

CustomerOrdersContext db = new CustomerOrdersContext();
var OrdersByCustomer = from so in db.SalesOrders
                       group so by so.CustomerId 
                       into TotaledOrders
Each of the IGrouping collections in the TotaledOrders collection has all of the members you'd expect a collection to have (they each have a Count method, for example). In addition, IGrouping collections have a property called Key that holds the shared value (the value from the CustomerId property, in this case).

However, to support the user's request, I don't want just this "collection of SalesOrders collections" -- I want a collection of objects with properties holding the shared CustomerId, the total value of all the SalesOrders in each collection and the SalesOrders themselves. To do that, in my query's select clause, I create an anonymous object with these properties:

Orders: A List of all of the Orders in each collection
CustomerId: The shared SalesOrders CustomerId which I can get from each collection's Key property
TotaledValue: The sum of the TotalValue property for all of the orders in each collection
Putting that together with the rest of the code, the code that creates the collection of anonymous objects I want looks like this:

var OrdersByCustomer = from so in db.SalesOrders
                       group so by so.CustomerId into TotaledOrders
                       select new {
                                    CustomerId = TotaledOrders.Key,
                                    TotaledValue = TotaledOrders.Sum(s => s.TotalValue),
                                    Orders = TotaledOrders.ToList()
                                  };
The next section is the material I've just covered, but in Visual Basic. If you've read this section, you'll probably want to skip the next section.

-->
<!---
using System.Collections.Generic;
using System.Threading.Tasks;
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;

namespace Microsoft.CommonDataService.Samples.SampleLibrary.WorkWithGroupBy
{
    public class WorkWithGroupBy
    {
        public static async Task RunSample(Client client, ITelemetryService telemetryService)
        {
            // Insert data
            var insertProductExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            var insertCatExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            telemetryService.TraceInformation("Running WorkWithGroupBy sample...");

            await ResetTestData(client);

            OperationResult<RelationalEntityReference<ProductCategory>> insertCatResult;
            OperationResult<RelationalEntityReference<ProductCategory>> insertCatResult2;

            var productCat = new ProductCategory()
            {
                Name = "Surface Pro",
                Description = "Description of Surface Pro",
                CategoryId = "C_S1"
            };

            var productCat2 = new ProductCategory()
            {
                Name = "Surface Studio",
                Description = "Description of Surface Studio",
                CategoryId = "C_S2"
            };

            telemetryService.TraceInformation("Inserting test data ... ");

            await insertCatExecutor
                .Insert(productCat, out insertCatResult)
                .Insert(productCat2, out insertCatResult2)
                .ExecuteAsync();

            // Insert Surface Pro
            var product = new Product()
            {
                Name = "Surface Pro",
                ProductType = ProductType.Item,
                Status = ProductStatus.Active,
                ProductCategory = insertCatResult.Result
            };

            var product2 = new Product()
            {
                Name = "Surface Pro",
                ProductType = ProductType.Item,
                Status = ProductStatus.Active,
                ProductCategory = insertCatResult.Result
            };

            var product3 = new Product()
            {
                Name = "Surface Pro",
                ProductType = ProductType.Item,
                Status = ProductStatus.Inactive,
                ProductCategory = insertCatResult.Result
            };

            // Insert Surface Studio
            var product_studio1 = new Product()
            {
                Name = "Surface Studio",
                ProductType = ProductType.Item,
                Status = ProductStatus.Active,
                ProductCategory = insertCatResult2.Result
            };

            var product_studio2 = new Product()
            {
                Name = "Surface Studio",
                ProductType = ProductType.Item,
                Status = ProductStatus.Inactive,
                ProductCategory = insertCatResult2.Result
            };

            await insertProductExecutor
                .Insert(product)
                .Insert(product2)
                .Insert(product3)
                .Insert(product_studio1)
                .Insert(product_studio2)
                .ExecuteAsync();

            var productSet = client.GetRelationalEntitySet<Product>();

            // Query 1:
            // SELECT Name, COUNT(Status) FROM Product
            // GROUP BY Status;
            var query1 = productSet
               .CreateQueryBuilder()
               .Group().By(
                     s => s.SelectField(p => p.Status))
                 .Into((p, aggregationFieldBuilder) => new { ProductCount = aggregationFieldBuilder.Count(p) })
               .Where((f, c) => f.Name == "Surface Studio" || f.Name == "Surface Pro")
               .Project(
                    p => p.SelectField(e => e.Status),
                    a => a.SelectField(e => e.ProductCount));

            var queryResult = query1.CreateQueryResultType();

            // Query 2:
            // SELECT Product.Name, COUNT(Product.OrderID) FROM Product
            // INNER JOIN ProductCategory
            // GROUP BY ProductCategory.id;

            var query2 = productSet
              .CreateQueryBuilder()
              .InnerJoin(p => p.ProductCategory)
              .Group().By(
                   p => p.SelectField(e => e.ProductCategory),
                    pc => pc.SelectField(i => i.Name))
                .Into((p, pc, aggregationFieldBuilder) => new { ProductCount = aggregationFieldBuilder.Count(p) })
              .Project(
                   p => p.SelectField(e => e.Name),
                   pc => pc.SelectField(e => e.Name),
                   a => a.SelectField(e => e.ProductCount));

            var queryResult2 = query2.CreateQueryResultType();

            var selectExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

            await selectExecutor
                .Query(query1, out queryResult)
                .Query(query2, out queryResult2)
                .ExecuteAsync();

            telemetryService.TraceInformation("Query1 result:");

            foreach (var entry in queryResult.Result)
            {
                telemetryService.TraceInformation("Product : Product status: {0} - Count: {1}", entry.Item1.Status, entry.Item2.ProductCount);
            }

            telemetryService.TraceInformation("Query2 result:");

            foreach (var entry in queryResult2.Result)
            {
                telemetryService.TraceInformation("Product : Product status: {0} - Count: {1}", entry.Item1.Name, entry.Item3.ProductCount);
            }
        }

        internal static async Task ResetTestData(Client client)
        {
            var productExtension = client.GetRelationalEntitySet<Product>();
            var productCategory = client.GetRelationalEntitySet<ProductCategory>();

            var queryProductExtension = productExtension
                .CreateQueryBuilder()
                .Where(f => f.Name == "Surface Studio" || f.Name == "Surface Pro")
                .Project(pc => pc.SelectField(f => f.Name));

            var querySampleEntity = productCategory
                .CreateQueryBuilder()
                .Where(f => f.Name == "Surface Studio" || f.Name == "Surface Pro")
                .Project(pc => pc.SelectField(f => f.Name));
            
            var selectExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            var deleteExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

            OperationResult<IReadOnlyList<Product>> productExtensionResult = null;
            OperationResult<IReadOnlyList<ProductCategory>> productCategoryResult = null;

            await selectExecutor
                .Query(queryProductExtension, out productExtensionResult)
                .Query(querySampleEntity, out productCategoryResult)
                .ExecuteAsync();

            foreach (var entry in productExtensionResult.Result)
            {
                deleteExecutor.DeleteWithoutConcurrencyCheck(entry);
            }

            foreach (var entry in productCategoryResult.Result)
            {
                deleteExecutor.DeleteWithoutConcurrencyCheck(entry);
            }
            await deleteExecutor.ExecuteAsync();
        }
    }
}
-->

### Using Aggregates
All relational databases have the ability to do aggregations over results. This is much preferred over doing aggregations manually, since the data is not transported over the wire, and performed very quickly. In this example we create and execute a query that counts the entities in a given entityset.

<!---
TODO example
-->

### Using Group by clauses

### Paging
In some scenarios it is useful to be able to fetch a certain number of records after a number of records have been skipped. It is possible to add Take and Skip clauses to the query to accomplish this. In this example we will fetch the 3 most expensive products:

```cs
private static async Task TakeExampleAsync(Client client)
{
    var query = client.GetRelationalEntitySet<Product>()
        .CreateQueryBuilder()
        .OrderByDescending(p => new object[] { p.SellingUnitPrice })
        .Project(p => p.SelectField(f => f.SellingUnitPrice)
            .SelectField(f => f.Name)
            .SelectField(f => f.Description))
        .Take(3);

    OperationResult<IReadOnlyList<Product>> queryResult = null;
    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult)
        .ExecuteAsync();

    foreach (var product in queryResult.Result)
    {
        Console.WriteLine(product.SellingUnitPrice.ToString() + ": " + product.Name);
    }
}
```
The .Take(3) clause instructs the system to fetch no more than three records, and the OrderByDescending causes the data to come in the correct order (most expensive first).

If you wanted to get the fourth, fifth and sixth most expensive products without getting the first, second and third, you would use the .Skip clause, passing the number of elements to skip before returning the sample. This is often used to fill a page in a grid view, where it is impractical to get all the data to the client at once. This paging is shown below:

```cs
private static async Task TakeAndSkipExampleAsync(Client client)
{
    var query = client.GetRelationalEntitySet<Product>()
        .CreateQueryBuilder()
        .OrderByDescending(p => new object[] { p.SellingUnitPrice })
        .Project(p => p.SelectField(f => f.SellingUnitPrice)
            .SelectField(f => f.Name)
            .SelectField(f => f.Description))
        .Skip(3).Take(3);

    OperationResult<IReadOnlyList<Product>> queryResult = null;
    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult)
        .ExecuteAsync();

    foreach (var product in queryResult.Result)
    {
        Console.WriteLine(product.SellingUnitPrice.ToString() + ": " + product.Name);
    }

}
```

## Updating data
Currently updating existing data is done by fetching the data to be updated, updating the data, and then inserting it into an executer for updating. In this example we will traverse all the products, and calculate a new price for each of them. The new selling price (of type Currency) is calculated and added to the set of fields to update (i.e. the call to .Update on the updates instance). When all the fields have been updated (there is only one field in this case), the field updater is added to the update executor. When all the entities have been dealt with, the updates are performed in the ExecuteAsync call.  

```cs
private static async Task UpdateExampleAsync(Client client)
{
    // In this example we will markup our product prices by 10 percent
    var query = client.GetRelationalEntitySet<Product>()
        .CreateQueryBuilder()
        .Project(p => p.SelectField(f => f.SellingUnitPrice));

    OperationResult<IReadOnlyList<Product>> allProducts = null;
    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out allProducts)
        .ExecuteAsync();

    var updateExecutor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional);

    foreach (Product entry in allProducts.Result)
    {
        ITypedRelationalFieldUpdates<Product> updates = 
            client.CreateRelationalFieldUpdates<Product>();

        Currency newPrice = new Currency()
        {
            Amount = entry.SellingUnitPrice.Amount * 1.10m,
            Code = entry.SellingUnitPrice.Code
        };
        updates.Update(pc => pc.SellingUnitPrice, newPrice);

        updateExecutor.Update(entry, updates);
    }

    await updateExecutor.ExecuteAsync();
}
```

## Deleting data
Deleting data is currently achieved by enumerating the data to delete, inserting them into a delete executor and firing off the ExecuteAsync method as usual. This is illustrated in the code below:

```cs
static async Task SimpleDeleteTestAsync(Client client)
{
    var query = client.GetRelationalEntitySet<ProductCategory>()
        .CreateQueryBuilder()
        .Where(pc => pc.Name == "Surface" || pc.Name == "Phone")
        .Project(pc => pc.SelectField(f => f.CategoryId)
            .SelectField(f => f.Name));

    OperationResult<IReadOnlyList<ProductCategory>> queryResult = null;
    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult)
        .ExecuteAsync();

    // Delete any Surfaces and Phones by looping through the results of the query
    var deleteExecutor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional);

    // Loop through results and insert rows in delete executor
    foreach (var entry in queryResult.Result)
    {
        deleteExecutor.Delete(entry);
    }

    // Goodbye data...
    await deleteExecutor.ExecuteAsync();

    // Insert, so we can run the test again
    var surfaceCategory = new ProductCategory() { 
        Name = "Surface", 
        Description = "Surface produce line" 
    };

    var phoneCategory = new ProductCategory() 
    { 
        Name = "Phone", 
        Description = "Phone produce line" 
    };
    
    await client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
                .Insert(surfaceCategory)
                .Insert(phoneCategory)
                .ExecuteAsync();
}
```

In this sample we are using Delete on the deleteExecutor to indicate that we want the record to be deleted. Delete deletes the entity but will throw an optimistic concurrency check exception if the entity was edited it was first selected. There is another method called DeleteWithoutConcurrencyCheck that will go ahead and delete the record without considering if changes were made since the entity was selected. 

## Reading data using generic Entitysets
In the previous case we had the advantage of dealing with a fully designed OOB entityset, and because of it we were able to use the full complement of features in C# and the tooling (intellisense and debugging support) to write your code. However, there may be cases where an entityset is defined in the portal, but no C# representation is defined. In this case you can refer to values using a weaker model where fields are described by their names, and field types are represented as generic (i.e. type) parameters.

<!---
//----------------------------------------------------------------------------
// Copyright (c) Microsoft Corporation. All rights reserved.
//----------------------------------------------------------------------------

using System.Collections.Generic;
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.Builders;
using Microsoft.CommonDataService.Entities;
using Microsoft.CommonDataService.Executers;
using Microsoft.CommonDataService.Services;

namespace Microsoft.CommonDataService.Samples.SampleLibrary.WorkWithGenericEntity
{
    public class WorkWithGenericEntity
    {
        //----------------------------------------------------------------------------
        // This sample is working. You need to have the cert installed locally.
        //----------------------------------------------------------------------------

        public static void RunSample(Client client, ITelemetryService telemetryService)
        {
            Utility.ResetTestData(client);

            telemetryService.TraceInformation("Insert some product categories");

            var genericEntitySet = client.GetRelationalEntitySet(new EntitySetReference("Microsoft.CommonDataService.CommonEntities", "ProductCategory", Version.Create("1.0.0")));

            var genericEntitySurface = genericEntitySet.CreateEntity();
            genericEntitySurface.SetValue("Name", "Surface");
            genericEntitySurface.SetValue("Description", "Surface produce line");

            var genericEntityPhone = genericEntitySet.CreateEntity();
            genericEntityPhone.SetValue("Name", "Phone");
            genericEntityPhone.SetValue("Description", "Phone produce line");

            var genericEntityD365 = genericEntitySet.CreateEntity();
            genericEntityD365.SetValue("Name", "D365");
            genericEntityD365.SetValue("Description", "D365 produce line");

            var insertExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            insertExecutor
                .Insert(genericEntityD365)
                .Insert(genericEntitySurface)
                .Insert(genericEntityPhone)
                .ExecuteAsync().Wait();

            var query = genericEntitySet
                .CreateQueryBuilder()
                .Where(pc => pc["Name"] == "Surface" || pc["Name"] == "Phone" || pc["Name"] == "D365")
                .OrderByAscending(pc => new[] { pc["CategoryId"] })
                .Project(pc => pc.SelectField(f => f["CategoryId"]).SelectField(f => f["Name"]).SelectField(f => f["Description"]));

            var selectExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            var updateExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

            OperationResult<IReadOnlyList<GenericRelationalEntity>> queryResult = null;

            selectExecutor
                .Query(query, out queryResult)
                .ExecuteAsync().Wait();

            telemetryService.TraceInformation("Select product categories");

            foreach (var entry in queryResult.Result)
            {
                string categoryId;
                string name;
                string description;

                if (entry.TryGetValue("CategoryId", out categoryId) && entry.TryGetValue("Name", out name) && entry.TryGetValue("Description", out description))
                {
                    telemetryService.TraceInformation("Product category: {0} - {1} - {2}", categoryId, name, description);

                    var updateProductCategory = client.CreateRelationalFieldUpdates(genericEntitySet);
                    string newDescription = "Desc: " + name;
                    updateProductCategory.Update(e => e["Description"], newDescription);

                    updateExecutor.Update(entry, updateProductCategory);
                }
            }

            telemetryService.TraceInformation("Update product categories");

            updateExecutor.ExecuteAsync().Wait();

            var selectAfterUpdateExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
            var deleteExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

            OperationResult<IReadOnlyList<GenericRelationalEntity>> queryAfterUpdateResult = null;

            selectAfterUpdateExecutor
                .Query(query, out queryAfterUpdateResult)
                .ExecuteAsync().Wait();

            telemetryService.TraceInformation("Select again, to check the update");

            foreach (var entry in queryAfterUpdateResult.Result)
            {
                string categoryIdValue;
                string nameValue;
                string descriptionValue;
                entry.TryGetValue("CategoryId", out categoryIdValue);
                entry.TryGetValue("Name", out nameValue);
                entry.TryGetValue("Description", out descriptionValue);
                telemetryService.TraceInformation("Product category: {0} - {1} - {2}", categoryIdValue, nameValue, descriptionValue);
                deleteExecutor.DeleteWithoutConcurrencyCheck(entry);
            }

            telemetryService.TraceInformation("Now delete everything");
            deleteExecutor.ExecuteAsync().Wait();

            var selectAfterDeleteExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

            OperationResult<IReadOnlyList<GenericRelationalEntity>> queryAfterDeleteResult = null;

            selectAfterDeleteExecutor
                .Query(query, out queryAfterDeleteResult)
                .ExecuteAsync().Wait();

            telemetryService.TraceInformation("Select again, to check the delete");

            int i = queryAfterDeleteResult.Result.Count;

            telemetryService.TraceInformation("{0} Product category found", i);
        }
    }
}

-->
