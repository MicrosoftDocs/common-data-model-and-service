---
title: "Get started with the CDS C# SDK | Microsoft Docs"
description: ""
author: "pvillads"
manager: "robinarh"
ms.date: "02/03/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "Common Data Service, CDS, C#, SDK"
audience: "Developer"
ms.assetid: "34eddae8-3715-4bd6-b921-5bfb82d9df1c"
---

# Get started with the CDS C# SDK

## Overview
It's easy to get started programming against the Common Data Service (CDS). This tutorial shows you how to get a CDS application up and running. 

There are four key steps:

1. **CDS database acquisition through PowerApps**. The Common Data Service is currently only available through PowerApps. You need to get access to a PowerApps environment and ensure it contains a CDS database. This allows you to configure the SDK to access that database.
1. **Application registration in Azure AD**. To allow your application access to the Common Data Service, you need to register your application in Azure AD. This allows you to establish an identity for your application and specify the permission levels it needs in order to access the CDS APIs.
1. **Console project creation and configuration**. The CDS C# SDK is delivered as part of a NuGet package. You need to apply this package to you new console app. This will add all assembly references needed to start programming against CDS. You would also add configuration values obtained from previous steps to the app.config, which will allow the SDK to function properly.
1. **Running your CDS application**. At this point, you can program against the CDS APIs. You can then run and debug your application like you would with any other .NET application. 

# CDS database acquisition through PowerApps

The Common Data Service is currently only available through PowerApps. You need to get access to a PowerApps environment and ensure it contains a CDS database. This allows you to configure the SDK to access that database.

## Prerequisites
If you have already signed up for PowerApps, you can go to [PowerApps](https://powerapps.microsoft.com), sign in and ensure you have admin access to an environment containing a CDS database. If not however, follow these instructions:

1. To get access to PowerApps, follow the [sign up](https://powerapps.microsoft.com/en-us/tutorials/signup-for-powerapps/) process instructions.
1. To acquire a CDS database, follow instructions to [create a database](https://powerapps.microsoft.com/en-us/tutorials/create-database/).

## Getting the environment ID

After acquiring an environment that contains a CDS database, you can use that environment's identifier to configure your CDS SDK application. The **environment ID** can be found as part of the URI under which you are accessing the above environment. Record this value as it is used in the upcoming configuration step. An example of such a URI and environment Id is as follows:

    URI: https://web.powerapps.com/environments/d1ec10fa-74d5-44e5-b0f7-e448e3ca7509/home
    Environment ID: d1ec10fa-74d5-44e5-b0f7-e448e3ca7509

# Application registration in Azure AD

To allow your application access to the Common Data Service, you need to register your application in Azure AD. This allows you to establish an identity for your application and specify the permission levels it needs in order to access the CDS APIs.

## Prerequisites

If you have already signed up for an Azure subscription, go to [Azure portal](https://portal.azure.com) and ensure you can create an app registration under Azure Active Directory. If not however, you can go to the [Azure](https://azure.microsoft.com) site and sign up for a free trial.

## Application registration

Follow these steps to register and configure an application in Azure AD:

1. In [Azure portal](https://portal.azure.com) go to **Azure Active Directory** 
1. Click on **Properties** and copy the **Directoy ID** value. Alternatively you can use the domain name from your AAD login email. Record this value as **AAD tenant** configuration value for next steps.
1. Go back to **Azure Acitve Directory** then click on **App registrations**. 
1. Create the application resource that we will be used when prompting you to login:
    1. Click on **Add** to see a Create pane.
    1. Enter a **Name** for your registered application.
    1. Select **Native** as application type.
    1. Add a **Redirect URI**, it could be any valid URI string. For example: http://localhost.
    1. Record value for **Redirect URI** for configuration in later steps.
    1. Click on **Create**.
1. Open the **Registered app**:
    1. Search for your newly registered app by name
    1. Click on it after finding it in the list of applications.
    1. Record value for **Application ID** for configuration in later steps.
1. Setup **Required permissions** for connecting to CDS services:
    1. Click on **Required permissions** to opne a new pane.
    1. Click on **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select **PowerApps Runtime Service**, then click on **Select**.
    1. Check the **Delegated permissions** box to select all entries, then click on **Select**.
    1. Click on **Done** to finalize setting up permissions to this service.
    1. Repeat the 3 steps above for **Windows Azure Service Management API**.
    
# Console project creation and configuration

The CDS C# SDK is delivered as part of a NuGet package. You need to apply this package to you new console app. This will add all assembly references needed to start programming against CDS. You would also add configuration values obtained from previous steps to the app.config, which will allow the SDK to function properly.

## Prerequisites
To create a new console project, obtain the NuGet package, then compile and build the application, you'll need [Visual Studio 2015](https://www.visualstudio.com/) or above installed on your computer.

Enusre you have the following configuration values from previous steps:

1. **AAD tenant**. This value identifies the tenant your database resides in.
1. **AAD application ID**. This value identifies the AAD app you registered earlier.
1. **AAD application redirect URI**. This value speciifies the redirect URI used when you are prompted to login.
1. **Environment ID**. This value identifies the PowerApps environment that contains your target CDS database.

## [Microsoft internal] Sample console application

You can obtain a pre-created version of the console application below from the internal [Samples repository](https://msazure.visualstudio.com/OneAgile/_git/CommonDataService-Samples?path=%2FSampleConsoleApplication&version=GBmaster&_a=contents). The configuration values will wtill need to be replaced with values from previous steps.

## Project creation and configuraion

1. Start **Visual Studio**.
1. From the **File** menu select **New project**.
1. In the **New Project** dialog box, click **Installed > Templates > Visual C#**.
    1. Choose **Console Application**.
    1. Make sure that .NET Framework 4.5.2 is selected as the target framework.
    1. Specify a name for your project and create the new Visual Studio solution.
1. [Microsoft internal] Add the wanuget-dev interanl feed:
    1. Go to **Tools > NuGet Package Manager > Package Manager Settings**, and nvafigate to **Package Sources**.
    1. Add a new source by clicking on the plus symbol on top.
    1. Set **Name** to wanuget-dev.
    1. Set **Source** to http://wanuget/dev/nuget.
    1. In the next step you may see many packages named similarly. Make sure to **only** add the one named **Microsoft.CommonDataService**.
1. Find your project on the Solution Explorer, right click on it and select **Manage NuGet packages**. 
    1. [Microsoft internal] Select **wanuget-dev** under **package source**.
    1. Check the **Include prerelease** box.
    1. Search for **Microsoft.CommonDataService**.
    1. Select the **Microsoft.CommonDataService** NuGet package and click on **Install**, to get the latest package.
    1. Proceed through the **License acceptance** dialog. **Note** that by clicking accept you are agreeing with all package license terms.
1. [To be resolved] Add the **Microsoft.AspNet.WebApi.Client** package from **nuget.org** package source.
1. In Solution Explorer, open the App.config and add the following XML, right under the openning `<configuration>` tag.
1. Replace the brackets with configuration values mentioned in the **prerequisites** section. `Type` attribute of `<Credentials>` XML element is set to **User** to specify that you will be prompted to login when the application runs.
```xml
    <configSections>
        <section name="Microsoft.CommonDataService.Connection" type="Microsoft.CommonDataService.Configuration.ConnectionSettingsSection, Microsoft.CommonDataService.ServiceContracts" />
    </configSections>
    <Microsoft.CommonDataService.Connection>
        <Tenant>[[Replace with AAD tenant value]]</Tenant>
        <EnvironmentId>[[Replace with PowerApps environment ID value]]</EnvironmentId>
        <Credentials Type="User">
            <ApplicationId>[[Replace with AAD application ID value]]</ApplicationId>
            <RedirectUri>[[Replace with AAD application redirect URI value]]</RedirectUri>
        </Credentials>
    </Microsoft.CommonDataService.Connection>
```

# Running the CDS console application
At this point, you can program against the CDS APIs. You can then run and debug your application like you would with any other .NET application. 

From Solution Explorer, open the Program.cs.config file, and add the following using statements:

```
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;
using Microsoft.CommonDataService.Configuration;
using Microsoft.CommonDataService.ServiceClient.Security;
using System;
using System.Collections.Generic;
```

In Program.cs, add the `[STAThread]` attribute to the `Main()` entry method, then copy the following code snippet inside the same method.

```
    using (var client = ConnectionSettings.Instance.CreateClient().Result)
    {
        // Insert Surface and Phone product lines
        var surfaceCategory = new ProductCategory() { Name = "Surface", Description = "Surface produce line" };
        var phoneCategory = new ProductCategory() { Name = "Phone", Description = "Phone produce line" };
        client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
            .Insert(surfaceCategory)
            .Insert(phoneCategory)
            .ExecuteAsync().Wait();

        // Query for Surface and Phone Product lines
        var query = client.GetRelationalEntitySet<ProductCategory>()
            .CreateQueryBuilder()
            .Where(pc => pc.Name == "Surface" || pc.Name == "Phone")
            .OrderByAscending(pc => new object[] { pc.CategoryId })
            .Project(pc => pc.SelectField(f => f.CategoryId).SelectField(f => f.Name).SelectField(f => f.Description));

        OperationResult<IReadOnlyList<ProductCategory>> queryResult = null;
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

Ensure the project compiles by right clicking on the project and clicking **Build**.

Set a breakpoint on the line of code declaring `updateProductCategory` and run your code by clicking on **Start** or pressing **F5**.

Login using **your credentials** when the Azure AD prompt appears. The first time you do this, you will be prompted to allow the AAD application registered earlier to access the services CDS uses.

Verify that the program runs and retrieves the newly inserted `ProductCategory` entities.

## [Optional] Examining data changes on PowerApps portal

Optionally, you can examine the changes made by your console applications, from the PowerApps portal. Go to [PowerApps](https://powerapps.microsoft.com), sign in, and go to the **Common Data Service** section on the left navigation pane.

Click on **Entities**, search for and select **Product category**,  then click on the **Data** tab in the top navigation section. You will be able to see the changes made to this entity by your console application.

You can build an application in PowerApps on this data and have the SDK and PowerApps work with the same data.

## [Optional] Inspecting CDS HTTPS interactions

You can optionally dig a bit deeper into the interactions the CDS client library is making with the CDS web service APIs.

For this step you need to download [Fiddler](http://www.telerik.com/fiddler), a free web debugging proxy. After registering, downloading and installing the Fiddler tool, you can follow the steps to [configure Fiddler to decrypt HTTPS traffic](http://docs.telerik.com/fiddler/configure-fiddler/tasks/decrypthttps) since the CDS web service APIs are based on HTTPS. **Note**: By performing the steps described in Telerik Fiddler documention, you are exposing your computer to security risks, for which Microsoft cannot be held responsible. Please consult Telerik Fiddler documentation for details of these risks.

1. Go to **File**, then select **Capture traffic** for the tool to record network activity. Alternatively you can press **F12** to enable and disable traffic capture.
1. To remove noise, you can right click on any repeating calls, select **Filter Now**, then click on **Hide 'process name'**. Verify that the process name is not one you want to monitor.
1. Run the console program above while capturing traffic and examine its request and response contents by clicking on the **Inspectors** tab on the details pane, and selecting the **JSON** or **Raw** tabs corresponding to the request and response.
1. Some interesting calls will be made to hosts named as follows:
    1. **login.windows.net**, **login.microsoftonline.com**. These calls perform authentication against Azure AD.
    1. **management.azure.com**. This call discovers where the CDS endpoint for your databse is located.
    1. **https://[unique-id].rsu.powerapps.com/namespaces/[unigue-id]/v001/entities/relational/$execute**. These calls perform data operations agaisnt the CDS.

The JSON content of the data operation calls described above will describe the operation type, data and metadata infromation about the responses from CDS. 


