---
title: "Get started with the Common Data Service SDK | Microsoft Docs"
description: ""
author: "nimakms"
manager: "robinarh"
ms.date: "05/15/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "Common Data Service, CDS, C#, SDK"
audience: "Developer"
ms.assetid: "34eddae8-3715-4bd6-b921-5bfb82d9df1c"
ms.reviewer: robinr
ms.author: nimak
---

# Get started with the Common Data Service SDK

[!INCLUDE [](../includes/new-version.md)]


<!-- [!NOTE]
> This feature is preview. If you are interested in participating in the preview program, contact us at [cdspreviewprogs_at_microsoft.com](mailto:cdspreviewprogs@microsoft.com). -->

## Overview

It's easy to start to program against the Common Data Service. This topic walks you through the process of getting a console application up and running. 

There are four main steps:

1. **Database acquisition** – Currently, the Common Data Service is available only through Microsoft PowerApps. You must get access to a PowerApps environment and make sure that it contains a database. You can then configure the software development kit (SDK) to access that database.
1. **Application registration** – To enable your application to access the Common Data Service, you must register your application in Microsoft Azure Active Directory (Azure AD). You can then establish an identity for your application and specify the permission level that it requires in order to access the application programming interfaces (APIs).
1. **Console project creation and configuration** – You can skip most of this step if you choose to start from the sample console application that we provide. If you choose to start from scratch, you must create a new C# Console Application project in Microsoft Visual Studio and apply the Common Data Service SDK NuGet package. This step will add all the assembly references that are required in order to start programming. You also add configuration values that you obtain in previous steps to the app.config file, so that the SDK works correctly.
1. **Programming and running your application** – At this point, you can program against the APIs in the SDK. You can then run and debug your application as you would run and debug any other .NET application. For a more advanced understanding of the SDK, from the PowerApps portal, you can also examine any data changes that are made by your applications. Alternatively, you can dig deeper into the interactions between the client library and web service APIs by using Fiddler.

# Database acquisition




Currently, the Common Data Service is available only through PowerApps. You must get access to a PowerApps environment and make sure that it contains a Common Data Service database. You can then configure the SDK to access that database.

## Prerequisites

1. If you've already signed up for PowerApps, you can go to [PowerApps](https://powerapps.microsoft.com) and sign in. If you haven't yet signed up, you can follow [these instructions](https://powerapps.microsoft.com/tutorials/signup-for-powerapps/) to sign up.
1. Make sure that you have admin access to an environment that contains a Common Data Service database. Go to the [PowerApps portal](https://powerapps.microsoft.com), click the gear icon in the upper right of the page, and then click **Admin center**. If you don't have admin access to any environments that contain a database, follow [these instructions](https://powerapps.microsoft.com/tutorials/create-database/) to create a database.

## Getting the environment ID

After you acquire an environment that contains a database, you can use that environment's identifier to configure your application. The environment ID is part of the URI that you use to access the environment. Record this value, because you will use it in upcoming configuration steps. Here is an example of a URI and the environment ID that is part of it:

+ **URI:** https://web.powerapps.com/environments/d1ec10fa-74d5-44e5-b0f7-e448e3ca7509/home
+ **Environment ID:** d1ec10fa-74d5-44e5-b0f7-e448e3ca7509

# Application registration




To enable your application to access the Common Data Service, you must register your application in Azure AD. You can then establish an identity for your application and specify the permission level that it requires in order to access the APIs.

## Prerequisites

If you've already signed up for an Azure subscription, go to the [Azure portal](https://portal.azure.com), and make sure that you can create an application registration under Azure AD. If you haven't yet signed up, you can go to the [Azure site](https://azure.microsoft.com) and sign up for a free trial.

1. In [the Azure portal](https://portal.azure.com), go to **Azure Active Directory**.
1. Click **Properties**, copy the **Directory ID** value, and record it as the **AAD tenant** configuration variable for upcoming steps. Alternatively, you can use the domain name from your Azure AD sign-in email message.

## Application registration

Follow these steps to register and configure an application in Azure AD.

1. Go back to **Azure Active Directory**, and click **App registrations**. 
1. Create the application resource that is used to prompt and sign in the user:
    1. Click **Add** to open a **Create** pane.
    1. Enter a name for your registered application.
    1. Select **Native** as the application type.
    1. In the **Redirect URI** field, enter any valid URI string, such as **http://localhost**.
    1. Record the **Redirect URI** value for upcoming steps.
    1. Click **Create**.
1. Open the registered app:
    1. Search for your newly registered app by name.
    1. When you find the app in the list of applications, click it.
    1. Record the **Application ID** configuration value for upcoming steps.
1. Set up the required permissions for connecting to the Common Data Service:
    1. Click **Required permissions** to open a new pane.
    1. Click **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select **Common Data Service**, and then click **Select**. If you can't find this service, see "Required permissions service isn't found" in the "Troubleshooting" section, later in this topic.
    1. Select all the entries under **Delegated permissions**, and then click **Select**.
    1. Click **Done** to complete the setup of permissions for this service.
    1. Repeat the preceding steps for **Windows Azure Service Management API**.

# Console project creation and configuration




You can skip most of this step if you choose to start from the sample console application that we provide. If you choose to start from scratch, you must create a new Visual Studio C# Console Application project and apply the Common Data Service SDK NuGet package. This step will add all assembly references that are required in order to start programming. You also add configuration values that you obtained in previous steps to the app.config file, so that the SDK works correctly.

## Prerequisites

To create a new console project, you must have [Microsoft Visual Studio 2015](https://www.visualstudio.com/) or later installed on your computer. 

Make sure that you have the following configuration values from previous steps:

+ **AAD tenant** – This value identifies the tenant that your database resides in.
+ **AAD application ID** – This value identifies the Azure AD app that you registered earlier.
+ **AAD application redirect URI** – This value specifies the redirect URI that is used when you're prompted to sign in.
+ **PowerApps environment ID** – This value identifies the PowerApps environment that contains your target database.

## Sample console application

For the private preview release, a project that is named SampleConsoleApplication is included in the Common Data Service SDK material. If you choose to use the sample project, follow these steps.

1. Replace the brackets in the App.config file with the configuration values that are mentioned in the "Prerequisites" section earlier in this topic.
1. Skip to "Compile and run the project" in the "Programming and running the console application" section, later in this topic. 

## Project creation and configuration

1. Start Visual Studio.
1. On the **File** menu, click **New project**.
1. In the **New Project** dialog box, click **Installed** > **Templates** > **Visual C#**, and then follow these steps:
    1. Select **Console Application**.
    1. Make sure that the Microsoft .NET Framework version 4.5.2 is selected as the target framework.
    1. Specify a name for your project, and create the new Visual Studio solution.
1. Note that during private preview, the Common Data Service SDK NuGet package isn't searchable. It should be directly applied from the Package Manager Console:
    1. Go to **Tools** > **NuGet Package Manager** > **Package Manager Console**.
    1. Enter the install command for your specific target version of the SDK, such as **Install-Package Microsoft.CommonDataService -Version 1.0.188-preview -Pre**.
1. In Solution Explorer, open the App.config file, and paste in the XML at the bottom of this section, right after the opening **\<configuration\>** tag.
1. Replace the bracketed text with the configuration values that are mentioned in the "Prerequisites" section earlier in this topic.

```xml
<configSections>
    <section name="Microsoft.CommonDataService.Connection" type="Microsoft.CommonDataService.Configuration.ConnectionSettingsSection, Microsoft.CommonDataService.ServiceContracts" />
</configSections>
<Microsoft.CommonDataService.Connection>
    <Tenant>[[Replace with AAD tenant value]]</Tenant>
    <EnvironmentId>[[Replace with PowerApps environment ID value]]</EnvironmentId>
    <Credentials Type="User">
        <UserSource>Prompt</UserSource>
        <ApplicationId>[[Replace with AAD application ID value]]</ApplicationId>
        <RedirectUri>[[Replace with AAD application redirect URI value]]</RedirectUri>
    </Credentials>
</Microsoft.CommonDataService.Connection>
```
Note that **Type** is set to **User** inside the opening **\<Credentials\>** tag. This value indicates that you will be prompted to sign in at startup. To save time by automating your sign-in, remove the **\<UserSource\>Prompt\</UserSource\>** XML element inside the **Credentials** element. This element and its value indicate that you will always be prompted at run time.

# Programming and running the console application




At this point, you can program against the APIs. You can then run and debug your application as you would run and debug any other .NET application. 

From Solution Explorer, open the Program.cs file, and replace the **using** statements at the top with the following code.

```cs
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;
using Microsoft.CommonDataService.Configuration;
using Microsoft.CommonDataService.ServiceClient.Security;
using System;
using System.Collections.Generic;
```

In Program.cs, add a **[STAThread]** attribute to the **Main()** entry method, and then copy the following code snippet inside that same method.

```cs
using (var client = ConnectionSettings.Instance.CreateClient().Result)
{
    // Query product categories for Surfaces and Phones
    var query = client.GetRelationalEntitySet<ProductCategory>()
        .CreateQueryBuilder()
        .Where(pc => pc.Name == "Surface" || pc.Name == "Phone")
        .Project(pc => pc.SelectField(f => f.CategoryId).SelectField(f => f.Name));

    OperationResult<IReadOnlyList<ProductCategory>> queryResult = null;
    client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult)
        .ExecuteAsync().Wait();

    // Delete any Surfaces and Phones
    var deleteExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
    foreach (var entry in queryResult.Result)
    {
        deleteExecutor.DeleteWithoutConcurrencyCheck(entry);
    }
    deleteExecutor.ExecuteAsync().Wait();

    // Insert Surface and Phone product lines
    var surfaceCategory = new ProductCategory() { Name = "Surface", Description = "Surface product line" };
    var phoneCategory = new ProductCategory() { Name = "Phone", Description = "Phone product line" };
    client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
        .Insert(surfaceCategory)
        .Insert(phoneCategory)
        .ExecuteAsync().Wait();

    // Query for Surface and Phone Product lines
    query = client.GetRelationalEntitySet<ProductCategory>()
        .CreateQueryBuilder()
        .Where(pc => pc.Name == "Surface" || pc.Name == "Phone")
        .OrderByAscending(pc => new object[] { pc.CategoryId })
        .Project(pc => pc.SelectField(f => f.CategoryId).SelectField(f => f.Name).SelectField(f => f.Description));

    client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
        .Query(query, out queryResult)
        .ExecuteAsync().Wait();

    // Update all selected Product Lines with description
    var updateExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
    foreach (var entry in queryResult.Result)
    {
        var updateProductCategory = client.CreateRelationalFieldUpdates<ProductCategory>();
        string updatedDescription = $"Description: {entry.Name}";
        updateProductCategory.Update(pc => pc.Description, updatedDescription);

        updateExecutor.Update(entry, updateProductCategory);
    }
    updateExecutor.ExecuteAsync().Wait();
}
```

### Compile and run the project

1. Make sure that the project is compiled by right-clicking the project and then clicking **Build**.
1. Set a breakpoint on the line of code that declares **updateProductCategory**, and then run your code by clicking **Start** or pressing F5.
1. When the Azure AD prompt appears, sign in by using your credentials. The first that time you run the application, you are prompted to allow the Azure AD application that you registered earlier to access the services that are used.
1. Verify that the program runs and retrieves the newly inserted **ProductCategory** entities.

## Advanced: Examining data changes

From the PowerApps portal, you can examine the data changes that your console applications make. 

1. Go to [PowerApps](https://powerapps.microsoft.com), and sign in.
1. In the left navigation pane, go to the **Common Data Service** section.
1. Click **Entities**, search for and select **Product category**,  and then click on the **Data** tab in the top navigation section. You now see the changes that your console application made to this entity.

You can build an application on this data in PowerApps. The SDK and PowerApps can work with the same data.

## Advanced: Inspecting Common Data Service HTTPS interactions

You can dig a bit deeper into the client library's interactions with the web service APIs.

For this step, you must download [Fiddler](http://www.telerik.com/fiddler), which is a free web debugging proxy. After you register, download, and install the Fiddler tool, you can follow [these steps](http://docs.telerik.com/fiddler/configure-fiddler/tasks/decrypthttps) to configure Fiddler to decrypt HTTPS traffic, because the web service APIs are based on HTTPS. 

**Note:** By following the steps that are described in the Telerik Fiddler documentation and allowing decryption of HTTPS traffic, you expose your computer to security risks that Microsoft cannot be held responsible for. For details about these risks, see the Telerik Fiddler documentation.

To use Fiddler to capture and inspect the traffic that is generated by the console application, follow these steps.

1. On the **File** menu, click **Capture traffic** so that the tool records network activity. Alternatively, you can press F12 to enable and disable traffic capture.
1. To remove noise, you can right-click any repeating calls, select **Filter Now**, and then click **Hide '{process name}'**. Verify that the process name is not the name of a process that you want to monitor.
1. Run the preceding console program while the tool captures traffic. To examine the request and response contents, in the details pane, click the **Inspectors** tab, and then select the **JSON** or **Raw** tabs that correspond to the request and response.

Here are some of the interesting calls that will be made to hosts:

+ **login.windows.net**, **login.microsoftonline.com** – These calls perform authentication against Azure AD.
+ **management.azure.com** – This call discovers where the Common Data Service endpoint for your database is located.
+ **https://[unique-id].rsu.powerapps.com** – These calls perform data operations against the Common Data Service.

The request and response contents of the preceding calls will describe the operation type, data, and metadata that the SDK passed to and from the Common Data Service. You can also find authentication information in these calls, in the form of the **Authorization** request header that goes to **management.azure.com** and **https://[unique-id].rsu.powerapps.com**. 

You can inspect these security tokens in more detail by decoding them at [jwt.io](https://jwt.io/). The following example shows a security token that is used to call the Common Data Service. Some of the properties have been removed. Note that the **appid** value matches the **AAD application ID** configuration value, the **upn** value matches the signed-in Azure AD user, and the **aud** value matches the resource ID for **Common Data Service**. (In security tokens from calls to **management.azure.com**, the **aud** value will match the resource ID of **Windows Azure Service Management API**.)

```javascript
{
  "aud": "http://rts.powerapps.com",
  "iss": "https://sts.windows.net/00000000-0000-0000-0000-000000000001/",    
  "appid": "00000000-0000-0000-0000-000000000002",
  "appidacr": "0",
  "deviceid": "00000000-0000-0000-0000-000000000003",
  "family_name": "Smith",
  "given_name": "John",
  "name": "John Smith",
  "oid": "00000000-0000-0000-0000-000000000004",
  "scp": "user_impersonation",
  "tid": "00000000-0000-0000-0000-000000000005",
  "unique_name": "jsmith@contoso.com",
  "upn": "jsmith@contoso.com",
  "ver": "1.0"
}
```

# Troubleshooting




This section describes some common issues that are encountered and reported by consumers of this topic.

## Required permissions service isn't found

In Azure AD directories where PowerApps and Azure Resource Manager were first used during Preview, you might not be able to find the exact names **Common Data Service** and **Windows Azure Service Management API** when you set up the required permissions in the previous step. In this case, you must directly modify the application's JSON manifest by clicking **Manifest** at the top of the registered app pane. Add the following entries under the JSON array that is named **requiredResourceAccess**, but be sure to maintain the validity of the manifest. When you've finished, click **Save**.

```javascript
{
    "resourceAppId": "82f77645-8a66-4745-bcdf-9706824f9ad0",
    "resourceAccess": [
    {
        "id": "4ae1b148-ab4d-496d-8183-9292090fcca4",
        "type": "Scope"
    }
    ]
},
{
    "resourceAppId": "797f4846-ba00-4fd7-ba43-dac1f8f63013",
    "resourceAccess": [
    {
        "id": "41094075-9dad-400e-a0bd-54e686782033",
        "type": "Scope"
    }
    ]
}
```

If the required permission still shows as invalid, please make sure that a user of your active directory tenant, has already signed up for PowerApps and created a database as described in the Database Acquisition section.

## Offline NuGet package

If you're using an offline version of the NuGet package for any reason, you can add the offline feed by following these steps.

1. Go to **Tools** > **NuGet Package Manager** > **Package Manager Settings**, and then navigate to **Package Sources**.
1. Add a new source by clicking the plus sign (+) at the top.
1. Set the **Name** field to **Local CDS Packages**.
1. Set the **Source** field to the local folder path, such as **C:\Users\user1\Desktop\NuGet**.
1. Follow the main instructions for applying **Microsoft.CommonDataService**.

