---
title: "Manipulate your data by using the Common Data Service SDK | Microsoft Docs"
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

# Manipulate your data by using the Common Data Service SDK

> [!NOTE]
> This feature is preview. If you are interested in participating in the preview program, contact us at [cdspreviewprogs_at_microsoft.com](mailto:cdspreviewprogs@microsoft.com).

This topic explains how you can use the C# software development kit (SDK) for the Common Data Service to work with data that is stored in the Common Data Service data cloud. The examples in this topic involve create, read, update, and delete (CRUD) operations on business data that is stored in relational data stores.

## Background

The C# Common Data Service SDK is designed for building responsive applications that use the backing computational resources as effectively as possible. The operations that the SDK performs are made available in the target language (C# in this case), as an embedded domain-specific language that is designed to handle any data access request against any data store. Although you can access the data without using an SDK, an SDK raises the abstraction level, so that you can focus on your business logic requirements instead of transport protocols, JavaScript Object Notation (JSON) documents, and so on.

In this approach, details about how data is accessed are hidden to the user. This is the same strategy that is used in Language Integrated Query (LINQ). However, the language that is used here is geared more toward enterprise resource planning (ERP) applications and is backed by a solid modeling framework that describes your entitysets.

The examples that follow demonstrate typical data access scenarios by using the out-of-box (OOB) entities. These entities are the entitysets that are released together with the SDK. These entitysets simplify the examples, because the tooling in the maker portal has created type-safe representations that are easy to work with. Although this way of working with entitysets is the recommended way, you can also work with entitysets that aren't defined in this manner. An example is provided at the end of this topic. In the maker portal in your environment, you can see how the OOB entities are defined (the fields, the relationships that the entityset has to other entitysets, and so on). 

## Terminology

The SDK uses the term _entityset_ where other material that describes relational databases would use the term _table_. The individual rows in the tables are known as entities. Although this terminology is consistent with the current nomenclature, you might find it confusing at first, because the maker portal, where you can edit entitysets, uses the word _entity_ (not _entityset_) as a synonym for _table_. 

## Programming model

The programming model that was chosen for the C# SDK uses all the facilities from C# to build an embedded domain-specific language. Most of the application programming interfaces (APIs) that the SDK offers are implemented as asynchronous calls. Asynchronous calls are run in such a manner that an awaited call doesn't block the thread that it's running on. Instead, the flow of control immediately returns to the caller. After the call is completed, execution resumes from the continuation of the await. You may want to peruse https://docs.microsoft.com/en-us/dotnet/articles/csharp/async for an overview of this technique.

Most of the APIs are written to support lambda functions. We will explain this term later in the topic when we go through some examples. 

There is no concept of an explicit transaction to contend with. As you will see, you add all the records that are subject to modification to what is known as a batch executor. The batch executor is then responsible for managing the transaction in the most effective manner. It runs as quickly as possible to maximize efficiency. 

## The client instance

Before you perform any operation with the data in the Common Data Service, you must be authenticated by Microsoft Azure Active Directory (Azure AD). The system does this authentication, based on a set of configuration settings in the configuration file in your project. In that configuration file, which is typically named App.config, you specify the application ID that you registered in the Azure portal, the ID of the environment that contains your data, and how you want to authenticate.

## Inserting data

We will start our discussion by inserting data into an entityset in the back-end database, because this operation is very easy to do. Because the entitysets are represented as plain C# classes, they are easily handled in C#. Here is an example.

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

The code first creates a client instance. In this case, the user name is used to create the security principal that is then used to create the client. Because the client holds unmanaged resources and implements **IDisposable**, it's a good practice to create the client in a **using** statement. The client instance is then passed to the **InsertAsync** method that does the actual work.

As the **async** keyword indicates, the **InsertAsync** method is asynchronous. (Per another good practice, the naming convention also reflects the fact that the method is asynchronous.) In this example, two product categories are created by instantiating the OOB entityset types. These entities are the entities that must be inserted.

Insertions, like all other data manipulation, are done through executors, such as the executor that is created in the next lines. The entities that are created are then added to the executor by using the **Insert** method. When the **ExecuteAsync** method is called on this executor, the system serializes the entities, sends them to the server side over the wire, starts a transaction, and inserts the entities. Because the call to the **ExecuteAsync** method is asynchronous, the call isn't a blocking call. As we mentioned above, this paradigm is used extensively in the C# SDK. You never explicitly manage a transaction. Instead, you let executors manage transactions on your behalf.

The code inserts two entities into the executor through a fluent syntax that chains the calls. The APIs are created to encourage this style, but you can also do the insertions as two separate calls to **Insert**.

There is another similar method available on the BatchExecutor called **InsertAndRetrieveEntity**:

```cs
private static async Task InsertAndRetrieveAsync(Client client)
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

    OperationResult<ProductCategory> category1, category2;
    executor
        .InsertAndRetrieveEntity(surfaceCategory, out category1)
        .InsertAndRetrieveEntity(phoneCategory, out category2);

    await executor.ExecuteAsync();

    // At this time (after the execution is finished) the out parameters 
    // will have their fields (including predefined fields and autonumber 
    // fields) populated.
}
```

As indicated, the out parameters will be populated with the values that are actually inserted into the database, including the values of autonumber fields, the createdBy fields and so on. Using this method can sometimes save a roundtrip to the server to get the data.

## Reading data from OOB entitysets

In this section, we explain how to select data that is stored in the Common Data Service relational back end. We start with some simple examples and then build on those examples to help you understand more complex scenarios.

First, we will go through the process for getting some data from the ProductCategory OOB entityset. This entityset, like most of the other OOB entitysets, has data in it, so that you can see the effects of the operations. The easiest way to see these effects is to use View Data on the entityset in the maker portal.

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

Once again, we do the work by using an asynchronous method. We first create a query builder that is based on the entityset that we want to query (ProductCategory in this case). The query builder is used as a starting point to add the parts that define the query. In this case, we are looking for product categories that have the name "Electronics", and we want them to be ordered by the category ID. We require only three field values: the category ID, the name, and the description. After the query has been created, another executor can use it to fetch the records. 

There are a few interesting things that you should notice. The **where** clause is expressed by using a lambda function. It's important that you understand that the lambda functions that are used in this context are never actually run. They are used only to express the programmer's intention. When the query is run (in the executor), the lambda function is translated to a query that is understood by the back end. Therefore, the lambda function serves as a structure that the expression is expressed in. 

Lambda functions have several benefits. The most important benefit is that the tooling in Microsoft Visual Studio provides a great experience because of its knowledge of the entitysets that are involved. The same strategy is used when the sorting option is specified. A lambda function is presented that maps a ProductCategory instance onto an array of fields to order by. (In this case, the instance is named pc, but this name has no significance outside the scope of the lambda function.) Finally, the projection is specified. The projection is the data that is required from each entity that is matched by the query. In this case, we are interested in the fields that are listed in the projection clauses. Another lambda takes a ProductCategory instance and returns the fields to include. Note that, for performance reasons, there is no option to automatically select all fields.

The **out** parameter of the **Query** method on the executor is used to enumerate the results when the await returns in the **queryResult** variable. The type of this variable indicates that the result is a read-only list of product category entities that can conveniently be enumerated.

Note, that in the simple examples we are showing here, there is rarely any need to do several things at once, but for more realistic scenarios it may be useful to do many things in one ExecuteAsync() call, i.e. within a single transaction. To accomplish that you can add any number of things to the executor before execution. 

```cs
var executor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
executor
    .Query(query1, out queryResult1);
    // Many more operations...
    .Query(query2, out queryResult2);

await executor.ExecuteAsync();
```

### Joining data from multiple entitysets

In the preceding examples, we have been working with single entitysets. However, this scenario is rare. Typically, the requirements specify that entities should be read from several entitysets and joined together to create useful results. In this section, we will describe how these joins are done in the C# SDK.

#### Using IncludeRelated
While it is perfectly valid to do joins in the typical manner, specifying the joined entityset and its join condition and type, there are more declarative ways of accomplishing joins in the CDS SDK. The entitysets can be defined to partake in relationships with other entities as they are designed. This declarative information can be leveraged in code without much effort, as we will show below.

Let us consider a case where where want to traverse the products, and for each of the products we want to know the details of the product category to which the product belongs.

```cs
static async Task SelectWithRelatedAsync(Client client)
{
    var query = client.GetRelationalEntitySet<Product>()
        .CreateQueryBuilder()
        .Project(builder => builder.SelectField(p => p.Name)
            .IncludeRelated(f => f.ProductCategory)
                .ProjectRelated(pc => pc.SelectField(f => f.Name)));

    OperationResult<IReadOnlyList<Product>> result = null;

    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out result)
        .ExecuteAsync();

    foreach (Product p in await result)
    {
        Console.WriteLine("Product " + p.Name + " in category: " + p.ProductCategory.Entity.Name);
    }
}
```

The interesting part in this example is limited to the **Project** clause ion the query builder. Here an **IncludeRelated** clause if provided to specify that a related entity is required. The lambda function again serves to designate what relation to consume - In this case it is the name of the lookup field on the Product that provides the category. Once the relationship has been selected, you need to specify which fields are required on the related entity (i.e. on the category entity). This information is provided in the **ProjectRelated** call. In this case, we require only the category name.

Let us now concentrate on a more complicated example where we want to traverse the categories and want the collection of products in that category.

<!-- This does not currently work. Promised in 1.14 -->

```cs
static async Task SelectWithRelated1Async(Client client)
{
    var query = client.GetRelationalEntitySet<ProductCategory>()
        .CreateQueryBuilder()
        .Project(builder => builder.SelectField(category => category.Name)
            .IncludeRelated(category => category.Product_ProductCategory)
                .ProjectRelated(product => product.SelectField(f => f.Name)));

    OperationResult<IReadOnlyList<ProductCategory>> result = null;

    await client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional)
        .Query(query, out result)
        .ExecuteAsync();

    foreach (ProductCategory pc in await result)
    {
        Console.WriteLine("Product category " + pc.Name);
        foreach (var p in pc.Product_ProductCategory)
        {
            Console.WriteLine("     Product " + p.Entity.Name);
        }
    }
}
```
 
#### Join clause

Another way to do joins is by specifying the **join** clause on the query. Because the entitysets carry with them a lot of metadata that describes the relationships among them, you typically don't have to specify the fields that are used to do the join in the query.

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

In the preceding example, you saw how joins internally took advantage of the relationships that are set up between the entitysets that are involved in those joins. Although this approach has several advantages in terms of simplicity, there might still be cases where you must do a join, but you haven't modeled any relationships. For this purpose, you can use the **Zip** clause, where you specify both the joined entityset and the relationship that defines the join.

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

In this section, we introduce the **group by** clause that lets you group data.

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

### Using aggregates

All relational databases can do aggregations over results. This approach is preferable to manual aggregation, because the data isn't transported over the wire, and the aggregations are done very quickly. The following example shows how to create and run a query that counts the entities in a given entityset.

<!---
TODO example
-->

### Using group by clauses

### Nested Queries
It is possible to nest queries, which can make writing complex queries where you would otherwise use joins easier. It works by passing an extra parameter in the lambda in the where clause; this extra parameter is used to build the exists clause.

```cs
public async void TestSimpleExistsAsync(Client client)
{
    var employees = client.GetRelationalEntitySet<Employee>();
    var departments = client.GetRelationalEntitySet<Department>();

    // Use an exists join in there where clause to denote
    // "Give me the ids of employees that are work in a department this is not "Dept1",
    // ordered by the employee id
    var query = employees
        .CreateQueryBuilder()
        .Where((e, sb) => sb.Exists(
                                departments,
                                builder => builder
                                    .Where(d => d.DepartmentName != "Dept1" && e.Department == d.CreateReference())
                                    .Project(d => d.SelectNoFields())))
        .OrderByAscending(e => new object[] { e.Id })
        .Project(e => e.SelectField(i => i.Id));

    var queryResult = query.CreateQueryResultType();
    var executor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);

    await executor.Query(query, out queryResult).ExecuteAsync().Wait();
}
```

### Paging

In some scenarios, it's useful to be able to fetch a certain number of records after several records have been skipped. To achieve this result, you can add **Take** and **Skip** clauses to the query. The following example shows how to fetch the three most expensive products.

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

The **.Take(3)** clause instructs the system to fetch no more than three records, and **OrderByDescending** causes the data to be in the correct order (most expensive product first).

If you wanted to get the fourth, fifth, and sixth most expensive products without getting the first, second and third most expensive products, you can add a **.Skip** clause and pass the number of elements that should be skipped before the sample is returned. This approach is often used to fill a page in a grid view, where it's impractical to get all the data to the client at one time. The following example shows this paging.

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

Currently, updates of existing data are done by fetching the data that must be updated, updating the data, and then inserting it into an executor for updating. In this example, we will traverse all the products and calculate a new price for each. The new selling price (of the **Currency** type) is calculated and added to the set of fields that will be updated (that is, the call to **.Update** on the **updates** instance). When all the fields have been updated, the field updater is added to the update executor. (In this example, only one field must be updated.) When all the entities have been handled, the updates are done in the **ExecuteAsync** call.  

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
The system uses optimistic concurrency control (OCC) where no locking is performed, and the system will throw an UpdateConflict exception if it turns out that changes have been to the same data from several transactions. The user needs to decide what to do in this case. One approach is to restart the transaction.

There is a useful method on the RelationalBatchExecutor called UpdateAndRetrieveEntity that will return the record after the updates have been applied, which can sometime save a roundtrip to the server.

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
        updates.UpdateAndRetrieve(pc => pc.SellingUnitPrice, newPrice);

        updateExecutor.Update(entry, updates);
    }

    await updateExecutor.ExecuteAsync();
}
```

## Deleting data
Currently, data is deleted by enumerating the data that must be deleted, inserting that data into a delete executor, and firing the **ExecuteAsync** method as usual. Here is an example.

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

In this example, we are using **Delete** on **deleteExecutor** to indicate that we want the record to be deleted. **Delete** deletes the entity but will throw an optimistic concurrency check exception if the entity was edited after it was first selected. Another method that is named **DeleteWithoutConcurrencyCheck**  will delete the record without considering whether changes were made since the entity was selected. 

## Working with documents in Azure storage
Sometimes you need to store things that do not fall within the other types that available for fields. This could be the case if you wanted to store sound bites, video clips, PDF files, word documents etc. For this purpose the CDS SDK has the concept of **blob storage**.

The idea is quite simple. You store the information in the form of a stream (i.e. in an instance of a class derived from System.IO.Stream). When you insert this into blob storage, you get a blob reference back. With this in hand you can get the data back from blob storage through the use of the **GetBlob** method on the **BlobBatchExecutor**.  

The following code should make this easier to understand:

```cs
public static async void BlobExampleAsync(Client client)
{
    // Blobs are stored in Azure blob storage. When inserted, a reference
    // is passed back to you, so you can save that in your entity.

    // Let's save a picture. Here we are getting the picture from the wikipedia 
    // article describing databases:
    // https://en.wikipedia.org/wiki/Database#/media/File:Postgres_Query.jpg

    WebRequest request = WebRequest.Create("https://en.wikipedia.org/wiki/Database#/media/File:Postgres_Query.jpg");
    WebResponse response = await request.GetResponseAsync();

    System.IO.Stream responseStream = response.GetResponseStream();
    // Bitmap bitmap2 = new Bitmap(responseStream);

    // We now have a stream to work with. Let's insert it into blob storage. 
    // The example may be a little contrived since there is an Image type
    // already available, but we will go with it anyway.
    var blobExecuter = client.CreateBlobBatchExecuter();
    OperationResult<BlobReference> uploadBlobResult = null;

    await blobExecuter
        .UploadBlob(responseStream, out uploadBlobResult)
        .ExecuteAsync();

    BlobReference photoReference = await uploadBlobResult;

    // Now that we have the blob reference, we can use it in a field
    // of type Blob reference.

    // When you have the blob reference you can access it by:
    blobExecuter = client.CreateBlobBatchExecuter();

    OperationResult<System.IO.Stream> getBlobResult = null;

    await blobExecuter.GetBlob(photoReference, out getBlobResult)
        .ExecuteAsync();
}
``` 

## Reflecting over definitions of entitysets
Sometimes it is useful to be able to see the details about the entities that you are working with programmatically. In .NET you do this through the Type object - In the SDK we have a lot more information recorded in metadata. There is a subsystem of the SDK that allows you to query this information. 

```cs
public static async void GetClassMetadata(IClient client, string entityName)
{
    OperationResult<RelationalEntitySetModel> resmResult;
    var executor = client.CreateModelingBatchExecuter(ModelingBatchExecutionMode.Transactional);

    executor.ReadEntitySet(new Microsoft.CommonDataService.EntitySetIdentifier(entityName),
        out resmResult);
                        
    await executor.ExecuteAsync();

    var res = await resmResult;

    Console.WriteLine("Name        " + res.Identifier);
    Console.WriteLine("DisplayName " + res.DisplayName);
    Console.WriteLine("Fields");

    foreach (var field in res.Fields)
    {
        Console.WriteLine("    " + field.Identifier + "(" + field.DisplayName + ") : " + field.Type.ToString());
    }
}
```
The sample works by using a special executor, the **ModelingBatchExecutor**. There is a **ReadEntitySet** method that asks the server to return the metadata when the executor executes. There is a lot of additional metadata, like the content of field groups, teh entity and field descriptions added by the maker, that the example above does not illustrate. Take it for a spin to explore.

## Working with non-typed entitysets

Earlier in this topic, we were working with a fully designed OOB entityset. Therefore, to write the code, we could use the full range of features in C# and the Visual Studio tooling (especially IntelliSense and debugging support). However, in some cases, you won't have the fully compiled classes to work with. For example, you're working with your custom entitysets, but you haven't generated a C# class for them. Another case where the following techniques become interesting is when you've customized an OOB entityset (for example, by adding a new field). In these cases, you can refer to fields by using a weaker model where fields are described by their names.

The following example shows some code that uses this approach.

```cs
public static async Task GenericEntitySetUsageAsync(Client client)
{
    var genericEntitySet = client.GetRelationalEntitySet(
        new EntitySetReference("Microsoft.CommonDataService.CommonEntities",
        "ProductCategory",
        Version.Create("1.0.0")));

    // Create a few product categories
    var genericEntitySurface = genericEntitySet.CreateEntity();
    genericEntitySurface.SetValue<string>("Name", "Surface");
    // The compiler can infer the type, so the generic argument describing
    // the type of the value is not strictly required. This is a shorthand.
    genericEntitySurface.SetValue("Description", "Surface produce line");

    var genericEntityPhone = genericEntitySet.CreateEntity();
    genericEntityPhone.SetValue("Name", "Phone");
    genericEntityPhone.SetValue("Description", "Phone produce line");

    var insertExecutor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional);

    await insertExecutor
        .Insert(genericEntitySurface)
        .Insert(genericEntityPhone)
        .ExecuteAsync();

    // Create a query using the indexing operators
    var query = genericEntitySet.CreateQueryBuilder()
        .Where(pc => pc["Name"] == "Surface" || pc["Name"] == "Phone")
        .OrderByAscending(pc => new[] { pc["CategoryId"] })
        .Project(pc => pc.SelectField(f => f["CategoryId"])
            .SelectField(f => f["Name"])
            .SelectField(f => f["Description"]));

    var selectExecutor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional);

    OperationResult<IReadOnlyList<RelationalEntity>> queryResult = null;
    await selectExecutor
        .Query(query, out queryResult)
        .ExecuteAsync();

    var updateExecutor = client.CreateRelationalBatchExecuter(
        RelationalBatchExecutionMode.Transactional);

    // Traverse the results
    foreach (var entry in queryResult.Result)
    {
        string categoryId = "";
        object name = null;
        string description = "";

        // The same shorthand is applied there, where the generic type
        // parameter can be omitted. The expected type can also be 
        // passed as a parameter of type Type.
        if (entry.TryGetValue<string>("CategoryId", out categoryId)
            && entry.TryGetValue("Name", out name, typeof(string))
            && entry.TryGetValue("Description", out description))
        {
            Console.WriteLine("{0} - {1} - {2}", categoryId, name, description);
        }
    }
}
```

You will notice a few things. The C# compiler allows for some syntactic sugar, so that the user can omit the generic **type** parameter when the compiler can determine the type from the type of the arguments that are provided. In this case, the call to the **SetValue** method is defined as shown in the following example.

```cs
Entity Entity.SetValue<T>(string fieldName, T val);
```

For example, the compiler sees the following call.

```cs
genericEntitySurface.SetValue("Name", "Surface");
```

In this case, the compiler determines that the type of **T** is **string**, based on the type of the string literal. To make things clearer, we could have written the code like this.

```cs
genericEntitySurface.SetValue<string>("Name", "Surface");
```

Similar considerations are in place for the **TryGetValue** calls. The conclusion is that the type of the field must be known at compile time, either because  a generic **type** argument is provided (either implicitly or explicitly) or because a **System.Type** instance is provided.
