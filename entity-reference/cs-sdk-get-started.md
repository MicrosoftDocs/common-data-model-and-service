---
title: "Get started with the CDS C# SDK | Microsoft Docs"
description: ""
author: "nimakms"
manager: "robinarh"
ms.date: "03/11/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "Common Data Service, CDS, C#, SDK"
audience: "Developer"
ms.assetid: "34eddae8-3715-4bd6-b921-5bfb82d9df1c"
---

# Get started with the Common Data Service C# SDK

## Overview
It's easy to get started programming against the Common Data Service (CDS). This topic walks you through getting a CDS console application up and running. 

There are four key steps:

1. **CDS database acquisition**. The Common Data Service is currently only available through **PowerApps**. You need to get access to a PowerApps environment and ensure it contains a CDS database. This allows you to configure the SDK to access that database.
1. **Application registration**. To allow your application access to the Common Data Service, you need to register your application in **Azure Active Directory**. This allows you to establish an identity for your application and specify the permission level it needs to access the CDS APIs.
1. **Console project creation and configuration**. You can skip most of this step if you choose to start from the sample console application we provide you. If you choose to start from scratch however, you need to create a new C# Console Application project in Visual Studio and apply the CDS SDK NuGet package. This will add all assembly references needed to start programming against CDS. You would also add configuration values obtained from previous steps to the app.config, which will allow the SDK to function properly.
1. **Programming and running your CDS application**. At this point, you can program against the CDS APIs. You can then run and debug your application like you would with any other .NET application. For a more advanced understanding of the SDK, you can also examine any data changes made by your applications, from the PowerApps portal, or dig deeper into the interactions between the CDS client library and CDS web service APIs, using Fiddler.

# CDS database acquisition

The Common Data Service is currently only available through **PowerApps**. You need to get access to a PowerApps environment and ensure it contains a CDS database. This allows you to configure the SDK to access that database.

## Prerequisites
1. If you have already signed up for PowerApps, you can go to [PowerApps](https://powerapps.microsoft.com) and sign in. If you have not signed up yet, you can follow instructions to [sign up](https://powerapps.microsoft.com/en-us/tutorials/signup-for-powerapps/).
1. Ensure you have admin access to an environment containing a CDS database, by going to the [PowerApps](https://powerapps.microsoft.com) portal, clicking on the **gear icon** located on top right of the screen, then clicking on **Admin center**. If you do not have admin access to any environments containing a database, follow these instructions to [create a database](https://powerapps.microsoft.com/en-us/tutorials/create-database/).

## Getting the environment ID

After acquiring an environment that contains a CDS database, you can use that environment's identifier to configure your CDS SDK application. The **environment ID** can be found as part of the URI you are using to access the environment. Record this value as it will be used in the upcoming configuration step. An example of such a URI and environment Id are as follows:

    URI: https://web.powerapps.com/environments/d1ec10fa-74d5-44e5-b0f7-e448e3ca7509/home
    Environment ID: d1ec10fa-74d5-44e5-b0f7-e448e3ca7509

# Application registration

To allow your application access to the Common Data Service, you need to register your application in **Azure Active Directory**. This allows you to establish an identity for your application and specify the permission level it needs in order to access the CDS APIs.

## Prerequisites

If you have already signed up for an Azure subscription, go to [Azure portal](https://portal.azure.com) and ensure you can create an application registration under Azure Active Directory. If not however, you can go to the [Azure](https://azure.microsoft.com) site and sign up for a free trial.

1. In [Azure portal](https://portal.azure.com) go to **Azure Active Directory** 
1. Click on **Properties** and copy the value of **Directoy ID** and record it as config variable **AAD tenant** for upcoming steps. Alternatively, you can use the domain name from your AAD login email.

## Application registration

Follow these steps to register and configure an application in Azure AD:

1. Go back to **Azure Acitve Directory** then click on **App registrations**. 
1. Create the application resource used to prompt and login the user:
    1. Click on **Add** to see a Create pane.
    1. Enter a **Name** for your registered application.
    1. Select **Native** as application type.
    1. Add a **Redirect URI**, it could be any valid URI string. For example: http://localhost.
    1. Record value for **Redirect URI** for configuration in later steps.
    1. Click on **Create**.
1. Open the **registered app**:
    1. Search for your newly registered app by name
    1. Click on it after finding it in the list of applications.
    1. Record configuration value **Application ID** for upcoming steps.
1. Setup **required permissions** for connecting to CDS:
    1. Click on **Required permissions** to open a new pane.
    1. Click on **Add**.
    1. Navigate to **Select an API**.
    1. Search for and choose **PowerApps Runtime Service**, then click **Select**. If you cannot find this service refer to the **Troubleshooting** section under **Required permissions service not found**.
    1. Check all entries under **Delegated permissions**, then click **Select**.
    1. Click on **Done** to finalize setting up permissions for this service.
    1. Repeat the 3 steps above for **Windows Azure Service Management API**.

# Console project creation and configuration

You can skip most of this step if you choose to start from the sample console application we provide you. If you choose to start from scratch, you need to create a new Visual Studio C# Console Application project and apply the CDS SDK NuGet package. This will add all assembly references needed to start programming against CDS. You would also add configuration values obtained from previous steps to the app.config, which will allow the SDK to function properly.

## Prerequisites
To create a new console project, you'll need [Visual Studio 2015](https://www.visualstudio.com/) or above installed on your computer. 

Ensure you have the following configuration values from previous steps:

1. **AAD tenant**. This value identifies the tenant your database resides in.
1. **AAD application ID**. This value identifies the AAD app you registered earlier.
1. **AAD application redirect URI**. This value specifies the redirect URI used when you are prompted to login.
1. **PowerApps environment ID**. This value identifies the PowerApps environment that contains your target CDS database.

## Sample console application

For the private preview release, a project called `SampleConsoleApplication` will be included in the CDS SDK material. If you choose to go with the sample project, perform the following:

1. Replace the brackets in **App.config** with configuration values mentioned in the **prerequisites** section above.
1. Skip to the last part of **Programming and running the CDS console application** to **Compile and run the project**. 

## Project creation and configuraion

1. Start **Visual Studio**.
1. From the **File** menu select **New project**.
1. In the **New Project** dialog box, click **Installed > Templates > Visual C#**.
    1. Choose **Console Application**.
    1. Make sure that .NET Framework 4.5.2 is selected as the target framework.
    1. Specify a name for your project and create the new Visual Studio solution.
1. **Note** - During private preview, the CDS SDK NuGet package is not searchable. It shouold be directly applied from the **Package Manager Console**:
    1. Go to **Tools > NuGet Package Manager > Package Manager Console**.
    1. Enter the install command for your specific target version of the SDK, using a command like: `Install-Package Microsoft.CommonDataService -Version 1.0.188-preview -Pre`
1. In Solution Explorer, open the **App.config** file and paste in the XML at the bottom of this section, starting right after the opening `<configuration>` tag.
1. Replace the bracket text with configuration values mentioned in the **prerequisites** section.

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
Note that `Type` is set to **User** inside the `<Credentials>` XML element, which signifies that you will be prompted to login at startup. If you want to save time by automating your login, remove the XML element `<UserSource>Prompt</UserSource>` under Credentials. This element and value indicates you will always be prompted at runtime.


# Programming and running the CDS console application
At this point, you can program against the CDS APIs. You can then run and debug your application like you would with any other .NET application. 

From Solution Explorer, open the **Program.cs** file, and replace `using` statements on top with following code:

```cs
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;
using Microsoft.CommonDataService.Configuration;
using Microsoft.CommonDataService.ServiceClient.Security;
using System;
using System.Collections.Generic;
```

In **Program.cs**, add a **`[STAThread]`** attribute to the **`Main()`** entry method, then copy the following code snippet inside that same method.

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

1. Ensure the project compiles by right clicking on the project and clicking **Build**.
1. Set a breakpoint on the line of code declaring `updateProductCategory` and run your code by clicking on **Start** or pressing **F5**.
1. Login using **your credentials** when the Azure AD prompt appears. The first time you run the application, you will be prompted to allow the AAD application you registered earlier to access the services CDS uses.
1. Verify that the program runs and retrieves the newly inserted `ProductCategory` entities.

## Advanced - Examining data changes

You can examine the data changes made by your console applications, from the PowerApps portal. Go to [PowerApps](https://powerapps.microsoft.com), sign in, and go to the **Common Data Service** section in the left navigation pane.

Click on **Entities**, search for and select **Product category**,  then click on the **Data** tab in the top navigation section. You will be able to see the changes made to this entity by your console application.

You can build an application in PowerApps on this data and have the SDK and PowerApps work with the same data.

## Advanced - Inspecting CDS HTTPS interactions

You can dig a bit deeper into the interactions the CDS client library is making with the CDS web service APIs.

For this step you need to download [Fiddler](http://www.telerik.com/fiddler), a free web debugging proxy. After registering, downloading and installing the Fiddler tool, you can follow the steps to [configure Fiddler to decrypt HTTPS traffic](http://docs.telerik.com/fiddler/configure-fiddler/tasks/decrypthttps) since the CDS web service APIs are based on HTTPS. 

**Note**: By performing the steps described in Telerik Fiddler documentation and allowing HTTPS traffic to be decrypted, you are exposing your computer to security risks, for which Microsoft cannot be held responsible. Please consult Telerik Fiddler documentation for details of these risks.

Use Fiddler to capture and inspect the traffic generated by the console application:

1. Go to **File**, then select **Capture traffic** for the tool to record network activity. Alternatively you can press **F12** to enable and disable traffic capture.
1. To remove noise, you can right click on any repeating calls, select **Filter Now**, then click on **Hide '{process name}'**. Verify that the process name is not one you want to monitor.
1. Run the console program above while capturing traffic and examine its request and response contents by clicking on the **Inspectors** tab on the details pane, then selecting the **JSON** or **Raw** tabs corresponding to the request and response.
1. A few interesting calls will be made to hosts named as follows:
    1. **login.windows.net**, **login.microsoftonline.com**. These calls perform authentication against Azure AD.
    1. **management.azure.com**. This call discovers where the CDS endpoint for your database is located.
    1. **https://[unique-id].rsu.powerapps.com**. These calls perform data operations against the CDS.

Request and response content of calls above will describe the operation type, data and metadata, that the SDK passed to and from CDS. Also, you can find authentication information in these calls, in the form of the request `Authorization` header going to **management.azure.com** and **https://[unique-id].rsu.powerapps.com**. 

You can inspect these security tokens in more detail by decoding them at [jwt.io](https://jwt.io/). The following is an example of a security token used to call the CDS, with some properties removed. Note that `appid` value matches **AAD application ID**, `upn` value matches the logged in AAD user, and `aud` value matches the resource ID for **PowerApps Runtime Service**. Alternatively, in security tokens from calls to **management.azure.com**, `aud` value will match the resource ID of **Windows Azure Service Management API**.

```javascript
{
  "aud": "http://rts.powerapps.com",
  "iss": "https://sts.windows.net/00000000-0000-0000-0000-000000000001/",    
  "appid": "00000000-0000-0000-0000-000000000002",
  "appidacr": "0",
  "deviceid": "00000000-0000-0000-0000-000000000003",
  "family_name": "Kamoosi",
  "given_name": "Nima",
  "name": "Nima Kamoosi",
  "oid": "00000000-0000-0000-0000-000000000004",
  "scp": "user_impersonation",
  "tid": "00000000-0000-0000-0000-000000000005",
  "unique_name": "nimak@microsoft.com",
  "upn": "nimak@microsoft.com",
  "ver": "1.0"
}
```

# Troubleshooting

This section will contain the common issues encountered and reported by consumers of this topic.

## Required permissions service not found

In some AAD configurations, like with nested tenants, you may be unable to find the **PowerApps Runtime Service** and **Windows Azure Service Management API** when setting up required permissions described in the secion **Application registration** above. In this case, you need to modify the application's JSON manifest directly, by clicking on **Manifest** on top of the registered app pane. Add the following entries under the JSON array named `requiredResourceAccess` while maintaining validity of the manifest, then click **Save**.

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

## Offline NuGet package

If you are using an offline version of the NuGet package for any reason, you can add the offline feed as follows:

1. Go to **Tools > NuGet Package Manager > Package Manager Settings**, and navigate to **Package Sources**.
1. Add a new source by clicking on the plus symbol on top.
1. Set **Name** to "Local CDS Packages".
1. Set **Source** to the local folder path. For example: C:\Users\user1\Desktop\NuGet
1. Follow the main instructions on applying **Microsoft.CommonDataService**.

<!---
# [Microsoft internal]

## Sample console application

You can obtain a final version of the console application below from the internal [samples repository](https://msazure.visualstudio.com/OneAgile/_git/CommonDataService-Samples?path=%2FSampleConsoleApplication&version=GBmaster&_a=contents). We will also publish this externally through GitHub. Replace the brackets in App.cofig with configuration values mentioned in the **prerequisites** section. 

### NuGet feed

1. Add the wanuget-dev interanl feed:
    1. Go to **Tools > NuGet Package Manager >Package Manager Settings**, and navigate to **Package Sources**.
    1. Add a new source by clicking on the plus symbol on top.
    1. Set **Name** to wanuget-dev.
    1. Set **Source** to http://wanuget/dev/nuget.
    1. **[Issue]** - If you don't have access to the NuGet feed, follow **troubleshooting** instructions under the **Offline NuGet** subsection.
    1. In the next step you may see many packages named similarly. Make sure to **only** add the one named **Microsoft.CommonDataService**.
1. Find your project on the Solution Explorer, right click on it and select **Manage NuGet packages**. 
    1. [Microsoft internal] Select **wanuget-dev** under **package source**.
    1. Check the **Include prerelease** box.
    1. Search for **Microsoft.CommonDataService**.
    1. Select the **Microsoft.CommonDataService** NuGet package and click on **Install**, to get the latest package.
    1. Proceed through the **License acceptance** dialog. **Note** that by clicking accept you are agreeing with all package license terms.

## Offline NuGet package

If you don't have access to the internal NuGet feed, you can use an offline NuGet package. Obtain the .nupkg file from the [feed location](https://msazure.visualstudio.com/OneAgile/PowerApps-AppPlatform/_packaging?feedName=Dev&protocolType=NuGet&packageName=microsoft.commondataservice) and clicking on the **Download** button on the top right. Either download the file yourself or asking a Microsoft employee to download it for you. Place the file in a folder on your machine.

Then add the offline feed as follows:

1. Go to **Tools > NuGet Package Manager > Package Manager Settings**, and navigate to **Package Sources**.
1. Add a new source by clicking on the plus symbol on top.
1. Set **Name** to "Local CDS Packages".
1. Set **Source** to the local folder path. For example: C:\Users\user1\Desktop\NuGet
1. Follow the main instructions on applying **Microsoft.CommonDataService**.
--->