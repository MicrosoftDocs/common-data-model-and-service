---
title: "Get started with the C# SDK using Azure Functions | Microsoft Docs"
description: ""
author: "nimakms"
manager: "robinarh"
ms.date: "03/11/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "Common Data Service, CDS, C#, SDK, Azure Functions"
audience: "Developer"
ms.assetid: "2308e302-ec0b-437a-82a3-dc71150b9d81"
---

# Get started with the C# SDK using Azure Functions

## Overview
It's easy to get started programming against the Common Data Service (CDS) using Azure Functions. This topic walks you through getting a CDS Azure Function up and running. 

There are five key steps:

1. **CDS database acquisition through PowerApps**. The Common Data Service is currently only available through PowerApps. You need to get access to a PowerApps environment and ensure it contains a CDS database. This allows you to configure the SDK to access that database.
1. **Application registration in Azure AD**. To give your Azure function access to the Common Data Service, you need to register a few applications in Azure AD. This allows you to establish an identity for your applications and specify the permission levels they needs in order to access the CDS APIs.
1. **Azure Function creation and configuration**. 

1. **Programming and running your CDS Azure Function**. At this point, you can use the Azure Function to program against the CDS APIs. You can then run and debug your function by making HTTP calls from the client console app like you would with any other Azure Function. 
1. **Console client application creation and configuration**. 

In addition, you can use this function from a PowerApp. There are two key steps:
1. **Custom API creation and configuration**
2. **Programming and running your PowerApp**


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

To give your Azure function access to the Common Data Service, you need to register a **Web app / API** applications in Azure AD. This allows you to establish an identity for your applications and specify the permission levels it needs in order to access the CDS APIs. You will also need to register the applications that calls into the Azure function, as they are also required to authenticate the calling user with Azure AD. In this guide, we will first use a simple console applciation to call into the Azure function, for this step we will require a **Native application** registration. Later, as a bonus steps, we will configure a PowerApps Custom API which requires registering another **Web app / API**. All these apps will have to be configured in Azure AD with the correct **Required permissions** and **known client applications**, for the end to end flow to work correctly.

[ToDo] Diagram of call sequence and agents

## Prerequisites

If you have already signed up for an Azure subscription, go to [Azure portal](https://portal.azure.com) and ensure you can create an application registration under Azure Active Directory. If not however, you can go to the [Azure](https://azure.microsoft.com) site and sign up for a free trial.

1. In [Azure portal](https://portal.azure.com) go to **Azure Active Directory** 
1. Click on **Properties** and copy the **Directoy ID** value. Alternatively you can use the domain name from your AAD login email. Record this value as **AAD tenant** configuration value for next steps.

## Azure function application registration

Follow these steps to register and configure your Azure funtion in Azure AD:

1. Go back to **Azure Acitve Directory** then click on **App registrations**. 
1. Create the Azure function application resource that we will use to call into CDS directly:
    1. Click on **Add** to see a Create pane.
    1. Enter a **Name** for your registered Azure function application.
    1. Select **Web app / API** as application type.
    1. Add a **Sign-on URL**, it could be any valid URI string. For example: http://localhost.    
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
1. Setup **known client applications** for seamless propogation of required permissions to clients:
    1. **Note** that this step may have to be performed after setting up the client application(s), given application ID values are used below.
    1. Modify the application's JSON manifest directly, by clicking on **Manifest** on top of the registered app pane.
    1. Add client application IDs as JSON string entries under the JSON array named `knownClientApplications` while maintainting validity of the manifest, then click **Save**. The manifest will look something like this:

```javascript
  "knownClientApplications": [
    "f60bee48-2341-4528-a91c-ec97f3ded8c1",
    "b3b3d65c-5cbf-4323-b32d-68fd40778ea5"
  ],
```

## Client application registration

Follow these steps to register and configure your client application in Azure AD:

1. Go back to **Azure Acitve Directory** then click on **App registrations**. 
1. Create the application resource that we will be used when prompting you to login:
    1. Click on **Add** to see a Create pane.
    1. Enter a **Name** for your registered client application.
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
    1. Search for and select the **Name** of the Azure function web app from previous step then click on **Select**.
    1. Check the **Delegated permissions** box to select all entries, then click on **Select**.
    1. Click on **Done** to finalize setting up permissions to this service.    

## Bonus - PowerApps Custom API application registration

Skip these steps if you are not planning to use the Azure function from PowerApps. Otherwise, follow these steps to register and configure your PowerApps Custom API application in Azure AD:

1. Go back to **Azure Acitve Directory** then click on **App registrations**. 
1. Create the application resource that we will be used when prompting you to login:
    1. Click on **Add** to see a Create pane.
    1. Enter a **Name** for your registered client application.
    1. Select **Web app / API** as application type.
    1. Add a **Sign on URL**, it could be any valid URI string. For example: http://localhost.
    1. Click on **Create**.
1. Open the **Registered app**:
    1. Search for your newly registered app by name
    1. Click on it after finding it in the list of applications.
    1. Record value for **Application ID** for configuration in later steps.
1. Setup **Required permissions** for connecting to CDS services:
    1. Click on **Required permissions** to opne a new pane.
    1. Click on **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select the **Name** of the Azure function web app from previous step then click on **Select**.
    1. Check the **Delegated permissions** box to select all entries, then click on **Select**.
    1. Click on **Done** to finalize setting up permissions to this service.

# Azure Function creation and configuration

You can create and configure functions from the [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) expereince. There you will be able to use the appropriate Functions template, and configure the CDS C# SDK's NuGet references, authentication, and target environment.

## Prerequisites

As with the previous step you need an Azure subscription, and access to [Azure portal](https://portal.azure.com). If you don't already have a subscription, go to the [Azure](https://azure.microsoft.com) site and sign up for a free trial.

Enusre you have the following configuration values from previous steps:

1. **AAD tenant**. This value identifies the tenant your database resides in.
1. **AAD application ID**. This value identifies the AAD web app you registered earlier.
1. **AAD application secret**. This value identifies secret of the AAD web app you registered earlier.
1. **PowerApps environment ID**. This value identifies the PowerApps environment that contains your target CDS database.

## Azure Function creation and configuraion

Assuming you already have an Azure subscription set up, create a new function app from the [Azure Portal](https://portal.azure.com/#create/Microsoft.FunctionApp):
1. Enter a unique name for the for **App name**.
1. Select your current **Subscription**.
1. Select an existing **Resource group** or provide a unique name for a new one.
1. Select your existing hosting plan.
1. Select the **Location** of the function.
1. Select an existing **Storage account** or follow steps to create one that will be used by the function.

Create a new Azure function under the newly created function app using templates:
1. Click on **New Function** under Functions from the left pane.
1. Select **GenericWebHook-CSharp** from the list of templates.
1. Name the new Function **ResetProductCategories**, and click **Create**.
1. You should see sample code under the **Develop** section in the left pane.

Configure the target environment, and security setting of the app:
1. Click on **Function app settings** on the bottom of the left pane.
1. Click **Configure app settings** under the Develop section.
1. Scroll down to **App settings** and clock on the last row.
1. Enter **Microsoft.CommonDataService.EnvironmentId** under **Key** and the **PowerApps environment ID** configuration value from previous steps, under **Value**.
1. Enter **Microsoft.CommonDataService.TenantNameOrId** under **Key** and the **AAD tenant** configuration value from previous steps, under **Value**.
1. Enter **Microsoft.CommonDataService.CredentialsType** under **Key** and **UserImpersonation** under **Value**, to denote authentication on-behalf-of calling user.
1. Enter **Microsoft.CommonDataService.ApplicationId** under **Key** and the **AAD application** configuration value from previous steps, under **Value**.
1. Enter **Microsoft.CommonDataService.ApplicationSecret** under **Key** and the **AAD application secret** configuration value from previous steps, under **Value**.
1. Enter **Microsoft.CommonDataService.AzureFunction** under **Key** and the **True** under **Value**.
1. [Issue] - Enter **Microsoft.CommonDataService.IsProd** under **Key** and the **True** under **Value**.
1. Click on **Save** at the top of the pane.

Copy the following JSON snippet under the **project.json** file of the project. On the Azure portal Function experience, you can get to this file by going to the **View files** tab on the top right of the pane, and creating a new file by clicking on **Add**. 

```javascript
{
  "frameworks": {
    "net46":{
      "dependencies": {
        "Castle.Core": "3.3.3",
        "Google.Protobuf": "3.0.0",
        "Microsoft.AspNet.WebApi.Client": "5.2.3",
        "Microsoft.IdentityModel.Clients.ActiveDirectory": "3.13.8",
        "Newtonsoft.Json": "9.0.1",
        "System.IdentityModel.Tokens.Jwt": "5.1.2",
        "Microsoft.IdentityModel.Tokens": "5.1.2"
      }
    }
  }
}
```

**Issue** - Before the SDK NuGet is available publicly, the Azure funtion binary dependencies have to be manually copied to the hosted Azure function:
1. Click on **Function app settings** on the bottom of the left pane.
1. Click on **Go to Kudu**.
1. To Do
1. Create a **/bin** folder under **ResetProductCategories** .
1. Copy the contents from [samples repository](https://msazure.visualstudio.com/OneAgile/_git/CommonDataService-Samples?path=%2FSampleFunctionApp%2FResetProductCategories%2Fbin&version=GBmaster&_a=contents) to the bin folder.

## Starting from Visual Studio

You have the option to either preferrably start from the Azure Functions portal experience or to start from Visual Studio. If you choose to start from Visual Studio however, you will need the latest [Azure Functions tools for Visual Studio](https://aka.ms/azfunctiontools) installed on your computer.

Even though the instructions below detail how to create and configure an Azure fuction using the preferred Azure Functions portal experience, you can follow the same instructions to create and configure the Azure function in Visual Studio. You can then publish the Azure Function project onto your Azure subscription by right clicking on the project and clicking on **Publish**.

### [Microsoft Internal] - Sample Azure Function

You can obtain a final Visual Studio version of the console application below from the internal [samples repository](https://msazure.visualstudio.com/OneAgile/_git/CommonDataService-Samples?path=%2FSampleFunctionApp&version=GBmaster&_a=contents). We will also publish this externally through GitHub. Replace the brackets in App.cofig with configuration values mentioned in the **prerequisites** section. 

### Configuration from Visual Studio

To perform the same configuration steps in Visual Studio, copy the following snippet under **Values** in the **appsettings.json** file from the Azure Function project and replace the values with ones acquired in previous steps.

```javascript
    "Microsoft.CommonDataService.TenantNameOrId": "[[Replace with AAD tenant value]]",
    "Microsoft.CommonDataService.EnvironmentId": "[[Replace with PowerApps environment ID value]]",
    "Microsoft.CommonDataService.CredentialsType": "UserImpersonation",
    "Microsoft.CommonDataService.ApplicationId": "[[Replace with AAD application ID value]]",
    "Microsoft.CommonDataService.ApplicationSecret": "[[Replace with AAD application secret value]]",
    "Microsoft.CommonDataService.AzureFunction": "True",
    "Microsoft.CommonDataService.IsProd": "True"
```

# Programming and running the CDS Azure Function
At this point, you can program against the CDS APIs. You can then run and debug your application like you would with any other .NET application. 

From Solution Explorer, open the run.csx file, and add the following using statements:

```
#r ".\bin\Microsoft.CommonDataService.Common.dll"
#r ".\bin\Microsoft.CommonDataService.CommonEntitySets.dll"
#r ".\bin\Microsoft.CommonDataService.InternalContracts.dll"
#r ".\bin\Microsoft.CommonDataService.RemoteDispatcher.dll"
#r ".\bin\Microsoft.CommonDataService.Serialization.dll"
#r ".\bin\Microsoft.CommonDataService.ServiceClient.dll"
#r ".\bin\Microsoft.CommonDataService.ServiceClient.Security.dll"
#r ".\bin\Microsoft.CommonDataService.ServiceContracts.dll"

using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;
using Microsoft.CommonDataService.Configuration;
using Microsoft.CommonDataService.ServiceClient.Security;
using Microsoft.CommonDataService.ServiceClient.Security.Credentials;
using System;
using System.Collections.Generic;
using System.Net;
```

In run.csx copy the following code snippet inside the method body.

```
      using (var client = await ConnectionSettings.Instance.CreateClient(req))
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
        var surfaceCategory = new ProductCategory() { Name = "Surface", Description = "Surface produce line" };
        var phoneCategory = new ProductCategory() { Name = "Phone", Description = "Phone produce line" };
        await client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
            .Insert(surfaceCategory)
            .Insert(phoneCategory)
            .ExecuteAsync();
        
        log.Info($"C# HTTP trigger function completed.");
        return req.CreateResponse(HttpStatusCode.OK);
    }
```

Start the console client app, by clicking on **Start** or pressing **F5**.

Login using **your credentials** when the Azure AD prompt appears. The first time you do this, you will be prompted to allow the AAD application registered earlier to access the services CDS uses.

Verify that the program runs and retrieves the newly inserted `ProductCategory` entities.


# Console client app creation and configuration

## Prerequisites
To create a new console project, obtain the NuGet package, then compile and build the application, you'll need [Visual Studio 2015](https://www.visualstudio.com/) or above installed on your computer.

Enusre you have the following configuration values from previous steps:

1. **AAD tenant**. This value identifies the tenant your database resides in.
1. **AAD client console application ID**. This value identifies the AAD app you registered earlier for the client console application.
1. **AAD client console application redirect URI**. This value speciifies the redirect URI used when you are prompted to login.
1. **AAD function application resource URI**. This value uniquely identifies the function application your client application will be calling. Think of this as an alternative ID for you function's AAD application registration.

## Project creation and configuraion

1. Start **Visual Studio**.
1. From the **File** menu select **New project**.
1. In the **New Project** dialog box, click **Installed > Templates > Visual C#**.
    1. Choose **Console Application**.
    1. Make sure that .NET Framework 4.5.2 is selected as the target framework.
    1. Specify a name for your project and create the new Visual Studio solution.
1. **Microsoft internal** - Add the wanuget-dev interanl feed:
    1. Go to **Tools > NuGet Package Manager > Package Manager Settings**, and nvafigate to **Package Sources**.
    1. Add a new source by clicking on the plus symbol on top.
    1. Set **Name** to wanuget-dev.
    1. Set **Source** to http://wanuget/dev/nuget.
    1. In the next step you may see many packages named similarly. Make sure to **only** add the one named **Microsoft.CommonDataService**.
1. Find your project on the Solution Explorer, right click on it and select **Manage NuGet packages**. 
    1. [Microsoft internal] Select **wanuget-dev** under **package source**.
    1. Check the **Include prerelease** box.
    1. Search for **?**.
    1. Select the ? NuGet package and click on **Install**, to get the latest package.
    1. Proceed through the **License acceptance** dialog. **Note** that by clicking accept you are agreeing with all package license terms.
1. **Issue** - Add the **Microsoft.AspNet.WebApi.Client** package from **nuget.org** package source.
1. In Solution Explorer, open the App.config and add the following XML, right after the openning `<configuration>` tag.

# Troubleshooting

This section will contain the most commonly issue encountered and reported by consumers of this topic.

## Required permissions service not found

In some AAD configurations, like with with nested tenants, you may be unable to find the **PowerApps Runtime Service** and **Windows Azure Service Management API** when setting up required permissions in the previous step. In such a case you need to modify the application's JSON manifest directly, by clicking on **Manifest** on top of the registered app pane. Add the following entries under the JSON array named `requiredResourceAccess` while maintainting validity of the manifest, then click **Save**.

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