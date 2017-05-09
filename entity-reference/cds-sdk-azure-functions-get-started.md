---
title: "Get started with the Common Data Service SDK by using Azure Functions | Microsoft Docs"
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

# Get started with the Common Data Service SDK by using Azure Functions

> [!NOTE]
> This feature is preview. If you are interested in participating in the preview program, contact us at [cdspreviewprogs_at_microsoft.com](mailto:cdspreviewprogs@microsoft.com).

## Overview

It's easy to start to program against the Common Data Service by using Microsoft Azure Functions. This topic walks you through the process to get a Common Data Service Azure Function up and running. 

There are four main steps in the process.

1. **Database acquisition** – Currently, the Common Data Service is available only through Microsoft PowerApps. You must get access to a PowerApps environment and make sure that it contains a database. You can then configure the software development kit (SDK) to access that database.
1. **Application registration** – To give your Azure Function access to the Common Data Service, you must register a few applications in Azure Active Directory (Azure AD). You can then establish an identity for your applications and specify the permission levels that they require in order to access the application programming interfaces (APIs).
1. **Azure Function creation, configuration, and programming** – You can create and configure your [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) from the web portal. There, you can use the appropriate Azure Functions template, and configure the Common Data Service SDK's NuGet references, authentication, and target environment.
1. **Console client application creation and configuration** – You can run and debug your Azure Function by running the client console app and making HTTP calls to the Azure Function. 

In addition, you can use the Azure Function from a PowerApps application. There are two main steps in the process.
1. **PowerApps Custom API creation and configuration** – Before the Azure Function can be called from an app, it must be wrapped by a Custom API that defines its API structure and authentication settings.
1. **PowerApps app building and testing** – The Custom API that is created can be used to call the Azure Function from an app. You can create the app and configure a button control to connect with the Custom API inside PowerApps Studio. You can also test calls to the Azure Function from PowerApps Player. 

# Database acquisition

Currently, the Common Data Service is available only through PowerApps. You must get access to a PowerApps environment and make sure that it contains a database. You can then configure the SDK to access that database.

## Prerequisites

1. If you've already signed up for PowerApps, go to [PowerApps](https://powerapps.microsoft.com), and sign in. If you've signed up yet, follow [these instructions](https://powerapps.microsoft.com/en-us/tutorials/signup-for-powerapps/) to sign up.
1. Make sure that you have admin access to an environment that contains a Common Data Service database. Go to the [PowerApps portal](https://powerapps.microsoft.com), click the gear symbol in the upper right of the page, and then click **Admin center**. If you don't have admin access to any environments that contain a database, follow [these instructions](https://powerapps.microsoft.com/en-us/tutorials/create-database/) to create a database.

## Getting the environment ID

After you acquire an environment that contains a database, you can use that environment's identifier to configure your SDK application. The environment ID is part of the URI that you using to access the environment. Record this value, because you will use it in the upcoming configuration step. Here is an example of a URI and the environment ID that is part of it:

+ **URI:** https://web.powerapps.com/environments/d1ec10fa-74d5-44e5-b0f7-e448e3ca7509/home
+ **Environment ID:** d1ec10fa-74d5-44e5-b0f7-e448e3ca7509

# Application registration

To give your Azure Function access to the Common Data Service, you must register applications of the **Web app / API** type in Azure AD. You can then establish an identity for your applications and specify the permission level that they require in order to access the APIs. You must also register the applications that call the Azure Function. In this topic, we will use a simple console application to call into the Azure Function. For this step, we will require a **Native application** registration. Later, as an advanced step, we will configure a PowerApps Custom API to call the Azure Function. For this step, we will have to register another **Web app / API** application. In order for the end-to-end flow to work correctly, all these apps will have to be configured in Azure AD so that they have correct **Required permissions** and **known client applications** values.

<!--- [ToDo] Diagram of call sequence and AAD applications --->

## Prerequisites

If you've already signed up for an Azure subscription, go to the [Azure portal](https://portal.azure.com), and make sure that you can create an application registration under Azure AD. If you can't create a registration, go to the [Azure site](https://azure.microsoft.com), and sign up for a free trial.

1. In the [Azure portal](https://portal.azure.com), go to **Azure Active Directory** 
1. Click **Properties**, copy the value of the **Directory ID** field, and record it as the **AAD tenant** configuration variable for upcoming steps. Alternatively, you can use the domain name from your Azure AD sign-in email message.

## Azure Function application registration

Follow these steps to register and configure your Azure Function in Azure AD.

1. Go back to **Azure Active Directory**, and click **App registrations**. 
1. Create the Azure Function application resource that we will use to call directly into the Common Data Service:
    1. Click **Add** to open a **Create** pane.
    1. Enter a name for your Azure Function application.
    1. Select **Web app / API** as the application type.
    1. In the **Sign-on URL** field, enter any valid URI string, such as **http://localhost**.
    1. Click **Create**.
1. Open the registered app:
    1. Search for the newly registered app by name.
    1. When you find the app in the list of applications, click it.
    1. Record the **Function application ID** configuration value for upcoming steps.
1. Get the application secret:
    1. Click **Keys** to open a new pane.
    1. Add a new key description, such as **key**, set the duration to **Never expires**, and then click **Save**.
    1. Record the **Function application secret** configuration value by copying and pasting the contents of the **Value** cell.
1. Set up the required permissions for connecting to the Common Data Service:
    1. Click **Required permissions** to open a new pane.
    1. Click **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select **PowerApps Runtime Service**, and then click **Select**. If you can't find this service, see "Required permissions service isn't found" in the "Troubleshooting" section, later in this topic.
    1. Select all the check boxes under **Delegated permissions**, and then click **Select**.
    1. Click **Done** to complete the setup of permissions for this service.
    1. Repeat the previous three steps for **Windows Azure Service Management API**.
1. Get the Azure Function application's resource ID:
    1. Open the application's JSON manifest directly, by clicking **Manifest** at the top of the registered app pane.
    1. Record the **AAD function resource ID** config value from any entry under **identifierUris**. Here is an example: **https://[your_domain_name]/4598e084-55a7-4d57-88ae-59902d8e3a52**

**Note:** You must configure known client applications after you've finished registering the other applications. The step is required for seamless propagation of the required permissions to clients. After you've completed all registrations, go to the "Add known applications to Azure Function app" section, later in this topic.

## Client application registration

Follow these steps to register and configure your client application in Azure AD.

1. Go back to **Azure Active Directory**, and then click **App registrations**. 
1. Create the application resource that will be used during the sign-in process:
    1. Click **Add** to open a **Create** pane.
    1. Enter a name for your client application.
    1. Select **Native** as the application type.
    1. In the **Redirect URI** field, enter any valid URI string, such as **http://localhost**.
    1. Record the **Redirect URI** configuration value for upcoming steps.
    1. Click **Create**.
1. Open the registered app:
    1. Search for the newly registered app by name.
    1. When you find the app in the list of applications, click it.
    1. Record the **Application ID** configuration value for upcoming steps.
1. Set up the required permissions for connecting to the Azure Function:
    1. Click **Required permissions** to open a new pane.
    1. Click **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select the name of the Azure Function web app that you created in previous steps, and then click **Select**.
    1. Select all the check boxes under **Delegated permissions**, and then click **Select**.
    1. Click **Done** to complete the setup of permissions for this service.    

## Advanced: PowerApps Custom API application registration

You can skip these steps if you aren't planning to use the Azure Function from PowerApps. However, if you're interested in using PowerApps, follow these steps to register and configure your PowerApps Custom API application in Azure AD.

1. Go back to **Azure Active Directory**, and then click **App registrations**. 
1. Create the application resource that will be used during the PowerApps sign-in process:
    1. Click **Add** to open a **Create** pane.
    1. Enter a name for your registered client application.
    1. Select **Web app / API** as the application type.
    1. Set the **Sign on URL** field to **https://msmanaged-na.consent.azure-apim.net/redirect**, and record this value for upcoming steps.
    1. Click on **Create**.
1. Open the registered app:
    1. Search for the newly registered app by name.
    1. When you find the app in the list of applications, click it.
    1. Record the **Custom API application ID** configuration value for upcoming steps.
1. Get the application secret:
    1. Click **Keys** to open a new pane.
    1. Add a new key description, such as **key**, set the duration to **Never expires**, and then click **Save**.
    1. Record the **Custom API application secret** configuration value by copying and pasting the contents of the **Value** cell.
1. Set up the required permissions for connecting to the Azure Function:
    1. Click **Required permissions** to open a new pane.
    1. Click **Add**.
    1. Navigate to **Select an API**.
    1. Search for and select the name of the Azure Function web app that you created in previous steps, and then click **Select**.
    1. Select all the check boxes under **Delegated permissions**, and then click **Select**.
    1. Click **Done** to complete the setup of permissions for this service.  

## Add known applications to the Azure Function app

For seamless propagation of the required permissions to clients, set up known client applications. Then, the first time that users sign in to a client application, they will be asked to provide all the permissions that are required in order to run this flow. If you skip this step, you might have to manually authorize the Common Data Service to be used for each user.
   
1. Go back to **Azure Active Directory**, and then click **App registrations**. 
1. Open the registered app:
    1. Search for the Azure Function web app that you created in previous steps.
    1. When you find the app in the list of applications, click it.
    1. Directly modify the application's JSON manifest by clicking **Manifest** at the top of the registered app pane.
    1. Click **Download**, and save a backup of the manifest. Then click **Edit** to go back.
    1. Get the application IDs for both your client application and your PowerApps custom API application.
    1. Add the application IDs as JSON string entries under the JSON array that is named **knownClientApplications**, but be sure to maintain the validity of the manifest. Then click **Save**. The manifest will resemble the following example.

```javascript
  "knownClientApplications": [
    "f60bee48-2341-4528-a91c-ec97f3ded...",
    "b3b3d65c-5cbf-4323-b32d-68fd40778..."
  ],
```

# Azure Function creation, configuration, and programming

<!---You can skip most of this procedure if you choose to start from the Azure Function project that we provide for you, and publish it to Azure. If you choose to start from scratch however, follow this procedure.--->

You can create and configure your [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) from the web portal. There, you can use the appropriate Azure Functions template, and configure the Common Data Service SDK's NuGet references, authentication, and target environment.

## Prerequisites

As for the previous step, you must have an Azure subscription and access to the [Azure portal](https://portal.azure.com). If you don't already have a subscription, go to the [Azure site](https://azure.microsoft.com), and sign up for a free trial.

Make sure that you have the following configuration values from previous steps:

+ **AAD tenant** – This value identifies the tenant that your database resides in.
+ **AAD function application ID** – This value identifies the Azure AD web app that you registered earlier for the Azure Function.
+ **AAD function application secret** – This value identifies the secret for the Azure AD web app that you registered earlier for the Azure Function.
+ **PowerApps environment ID** – This value identifies the PowerApps environment that contains your target Common Data Service database.

<!---
## Sample Azure Function project

For the private preview release, a project called `SampleFunctionApplication` is included in the Common Data Service SDK material. If you choose to go with this sample project, you will need to install **WebToolsAzure2015.exe** from version **2.9.6** of [Microsoft Azure SDK for .NET](https://www.microsoft.com/en-us/download/details.aspx?id=54289) on your computer. Then you should Download and install [Visual Studio Tools for Azure Functions](https://aka.ms/azfunctiontools). **Note** that later versions of the Microsoft Azure SDK for .NET, like version **3.0.0**, are incompatible with the provided samples.

1. Replace the brackets in **appsettings.json** with configuration values mentioned in the **Prerequisites** section.
1. Right click on the Function project and click **Publish ...**
1. Select the publish target **Microsoft Azure App Service**.
1. Enter your credentials.
1. Click **New** and crate a new app service in your existing subscription.
1. Create new **Resource Group**, **App Service Plan** or **Storage Account** as appropriate.
1. Skip to the **Console client app creation and configuration** section.
1. **Note** that after publishing, you might have to delete the published **project.lock.json** file as detailed in the troubleshooting section **Assembly load issue after publish to Azure**.

You can also follow the similar instructions as below to create and configure the Azure function in Visual Studio, then publish it as shown above.
--->

## Azure Function creation and configuration

If you already have an Azure subscription set up [create and open a new Azure Function app from the Azure Portal](https://portal.azure.com/#create/Microsoft.FunctionApp).

1. Enter a unique app name.
1. Select your current subscription.
1. Select an existing resource group, or provide a unique name for a new resource group.
1. Select the existing consumption plan as your hosting plan.
1. Select the location of the Azure Function.
1. Select an existing storage account, or follow the steps to create a new storage account.
1. Click **Create**.
1. Under **All resources**, search for and select the app that you created.

Create a new Azure Function by using templates.

1. In the left pane, under **Functions**, click **New Function**.
1. In the list of templates, select **GenericWebHook-CSharp**.
1. Name the new Azure Function **UpdateProjectCategory**, and then click **Create**.

    **Note:** The sample code window opens under the header section that is marked with an **f** symbol.

1. Record the **Function URL** configuration value for upcoming steps by clicking **Get function URL** in the upper right and then clicking **Copy**.

Copy the following JSON snippet to the project.json file of the Function project. In the Azure Portal Functions experience, you can follow these steps to update the file.

1. Click the **View files** tab in the upper right of the pane.
1. Create the file by clicking **Add** and typing **project.json**.
1. Paste the following JSON contents into the edit window, and then click **Save**.

```javascript
{
  "frameworks": {
    "net46":{
      "dependencies": {
        "Castle.Core": "3.3.3",
        "Google.Protobuf": "3.0.0",
        "Microsoft.AspNet.WebApi.Client": "5.2.3",
        "Microsoft.CommonDataService": "1.0.188-preview",
        "Microsoft.IdentityModel.Clients.ActiveDirectory": "3.13.8",
        "Microsoft.IdentityModel.Logging": "1.1.3",
        "Microsoft.IdentityModel.Tokens": "5.1.3",
        "Newtonsoft.Json": "9.0.1",
        "System.IdentityModel.Tokens.Jwt": "5.1.3"
      }
    }
  }
}
```

From **View files** pane on the right, open **run.csx**, and replace the **using** and **#r** statements with the following code.

```cs
using Microsoft.CommonDataService;
using Microsoft.CommonDataService.CommonEntitySets;
using Microsoft.CommonDataService.Configuration;
using Microsoft.CommonDataService.ServiceClient.Security;
using Microsoft.CommonDataService.ServiceClient.Security.Credentials;
using System;
using System.Collections.Generic;
using System.Net;
```

Copy the following code snippet inside the body of the **run()** method of run.csx. Replace the existing code.

```cs
    log.Info($"C# HTTP trigger function processed a request. RequestUri={req.RequestUri}");

    // parse query parameter
    string name = req.GetQueryNameValuePairs()
        .FirstOrDefault(q => string.Compare(q.Key, "name", true) == 0)
        .Value;

    if(name == null)
    {
        log.Info($"Name was not passed correctly.");
        return req.CreateResponse(HttpStatusCode.BadRequest);
    }

    var connection = new ConnectionSettings
    {
        Tenant = "[[Replace with AAD tenant value]]",
        EnvironmentId = "[[Replace with PowerApps environment ID value]]",
        Credentials = new UserImpersonationCredentialsSettings
        {
            ApplicationId = "[[Replace with Function application ID value]]",
            ApplicationSecret = "[[Replace with Function application secret value]]"
        }
    };

    using (var client = await connection.CreateClient(req))
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
        await client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
            .Insert(surfaceCategory)
            .Insert(phoneCategory)
            .ExecuteAsync();

        // Query for Surface and Phone Product lines
        query = client.GetRelationalEntitySet<ProductCategory>()
            .CreateQueryBuilder()
            .Where(pc => pc.Name == name)
            .OrderByAscending(pc => new object[] { pc.CategoryId })
            .Project(pc => pc.SelectField(f => f.CategoryId).SelectField(f => f.Name).SelectField(f => f.Description));

        await client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional)
            .Query(query, out queryResult)
            .ExecuteAsync();

        // Update all selected Product Lines with description
        var updateExecutor = client.CreateRelationalBatchExecuter(RelationalBatchExecutionMode.Transactional);
        foreach (var entry in queryResult.Result)
        {
            log.Info($"Updateing '{entry.Name}'.");
            var updateProductCategory = client.CreateRelationalFieldUpdates<ProductCategory>();
            string updatedDescription = $"{DateTime.Now.ToString()} - Updated '{entry.Name}'";
            updateProductCategory.Update(pc => pc.Description, updatedDescription);

            updateExecutor.Update(entry, updateProductCategory);
        }
        await updateExecutor.ExecuteAsync();

        log.Info($"C# HTTP trigger function completed.");
        return req.CreateResponse(HttpStatusCode.OK);
    }    
```

Configure the target environment and security setting of the app by replacing the corresponding bracketed text in the code with configuration values:

+ The **AAD tenant** configuration value should replace **[[Replace with AAD tenant value]]**.
+ The **PowerApps environment ID** configuration value should replace **[[Replace with PowerApps environment ID value]]**.
+ The **AAD application** configuration value should replace **[[Replace with function application ID value]]**.
+ The **AAD application secret** configuration value should replace **[[Replace with Function application secret value]]**.

When you've finished, click **Save** at the top of the pane.

# Console client app creation and configuration

## Prerequisites

To create a new console project, you must have [Microsoft Visual Studio 2015](https://www.visualstudio.com/) or later installed on your computer.

Make sure that you have the following configuration values from previous steps:

+ **Function URL** – This value identifies location of the Azure Function.
+ **AAD tenant** – This value identifies the tenant that your database resides in.
+ **AAD client console application ID** – This value identifies the Azure AD app that you registered earlier for the client console application.
+ **AAD client console application redirect URI** – This value specifies the redirect URI that is used when you're prompted to sign in.
+ **AAD function application resource URI** – This value uniquely identifies the Azure Function application that your client application will call. You can think of this value as an alternative ID for your Azure Function's Azure AD application registration.

## Project creation and configuration

1. Start Visual Studio.
1. On the **File** menu, click **New project**.
1. In the **New Project** dialog box, click **Installed** > **Templates** > **Visual C#**, and then follow these steps:
    1. Select **Console Application**.
    1. Make sure that the Microsoft .NET Framework 4.5.2 is selected as the target framework.
    1. Specify a name for your project, and create the new Visual Studio solution.
1. Find your project in Solution Explorer, right-click it, click **Manage NuGet packages**, and then follow these steps: 
    1. Search for **Microsoft.AspNet.WebApi.Client**.
    1. Select the **Microsoft.AspNet.WebApi.Client** NuGet package, and then click **Install** to get the latest package.
    1. Proceed through the **License acceptance** dialog box. Note that by clicking **Accept**, you're agreeing to all package license terms.
    1. Repeat the last three steps for **Microsoft.IdentityModel.Clients.ActiveDirectory** and **Newtonsoft.Json**.

From Solution Explorer, open the **Program.cs** file, and replace the **using** statements at the top with the following code.

```cs
using Microsoft.IdentityModel.Clients.ActiveDirectory;
using System;
using System.Net.Http;
using System.Net.Http.Headers;
using System.Threading.Tasks;
```

In Program.cs, copy the following code and paste it inside the **Program** class. Replace the existing contents.

```cs
public const string TenantNameOrId = "[[Replace with AAD tenant value]]";
public const string ClientAppId = "[[Replace with AAD client application ID value]]";
public const string RedirectUri = "[[Replace with AAD client redirect URI value]]";
public const string AzureHostedResetUriString = "[[Replace with Function URL value]]"; // Azure hosted Function URI
public const string FunctionResourceId = "[[Replace with AAD function resource ID value]]";

public static string Authority { get { return string.Format(AuthorityTemplate, TenantNameOrId); } }
private const string AuthorityTemplate = "https://login.windows.net/{0}";
public const string LocalHostedUpdateUriString = "http://localhost:7071/api/UpdateProductCategory"; // Locally hosted Function URI
public const string AuthorizationHeaderScheme = "Bearer";

static void Main(string[] args)
{
    // Run operation as async function
    UpdateEntityAsync().Wait();
    Console.WriteLine("Press any key to continue ...");
    Console.ReadLine();
}

private static async Task UpdateEntityAsync()
{
    // Get HTTP client and send request
    var client = await GetHttpClientAsync();
    bool isAzureHosted = true;
    var updateUriString = isAzureHosted ? $"{AzureHostedResetUriString}&name=Surface" : $"{LocalHostedUpdateUriString}?name=Surface";
    var response = await client.PostAsJsonAsync<object>(updateUriString, null);
    Console.WriteLine($"Status: '{response.StatusCode}'");
    Console.WriteLine($"Contents: {await response.Content.ReadAsStringAsync()}");
}

private static async Task<HttpClient> GetHttpClientAsync()
{
    // Prompt for login and create security token
    var authenticationContext = new AuthenticationContext(Authority);
    AuthenticationResult authenticationResult = await authenticationContext.AcquireTokenAsync(FunctionResourceId
        , ClientAppId
        , new Uri(RedirectUri)
        , new PlatformParameters(PromptBehavior.Auto));
    var securityTokenString = authenticationResult.CreateAuthorizationHeader();

    // Create and configure the HTTP client
    var client = new HttpClient();
    var authorizationHeaderParameter = securityTokenString.Replace(AuthorizationHeaderScheme + " ", string.Empty);
    client.DefaultRequestHeaders.Authorization = new AuthenticationHeaderValue(AuthorizationHeaderScheme, authorizationHeaderParameter);
    return client;
}
```

Configure the target environment and security setting of the app by replacing the corresponding bracketed text in the code with configuration values:

+ The **AAD tenant** configuration value should replace **[[Replace with AAD tenant value]]**.
+ The **AAD client application ID** configuration value should replace **[[Replace with AAD client application ID value]]**.
+ The **AAD client application redirect URI** configuration value should replace **[[Replace with AAD client redirect URI value]]**.
+ The **Function URL** configuration value should replace **[[Replace with Function URL value]]**.
+ The **AAD function resource ID** configuration value should replace **[[Replace with AAD function resource ID value]]**.

The client application can call either the hosted version of the Azure Function in Azure or the locally hosted version from a Visual Studio Function Application. If you're testing against Azure, set the **isAzureHosted** variable to **true** to use the correct URI value.

```cs
public const string AzureHostedResetUriString = "https://[unique_id].azurewebsites.net/api/UpdateProductCategory?code=[unique_code]"; // Azure hosted Function URI
public const string LocalHostedUpdateUriString = "http://localhost:7071/api/UpdateProductCategory"; // Locally hosted Function URI
bool isAzureHosted = true; // false
var updateUriString = isAzureHosted ? $"{AzureHostedResetUriString}&name=Surface" : $"{LocalHostedUpdateUriString}?name=Surface";
```

### Compile and run the project

1. Make sure that the project is compiled by right-clicking the project and then clicking **Build**.
1. Run the client code by clicking **Start** or pressing F5.
1. When the Azure AD prompt appears, sign in by using your credentials. The first time that you run the application, you're prompted to allow the Azure AD application that you registered earlier to access the services that the Common Data Service uses.
1. Verify that the program runs and calls the Azure Function.
1. Verify that the Azure Function updates product categories as you expect.

**Note:** If you see log errors that are related to assembly loading, see "Assembly load issue after you publish to Azure" in the "Troubleshooting" section, later in this topic. 

# Advanced: PowerApps Custom API creation and configuration
In order for the Azure Function to be called from an app, it must first be wrapped by a Custom API that defines its API structure and authentication settings.

Prepare the [swagger](http://swagger.io/) file that defines your Azure Function by copying the following content to a .json file and modifying the **host** and **default code** values. To get these values, open the Azure Function edit page, and click **Copy function URL** in the upper right.

```javascript
{
  "swagger": "2.0",
  "info": {
    "version": "v1",
    "title": "ProductCategory",
    "description": "Product Category test operations."
  },
  "host": "[[Replace with Azure Function app name value]].azurewebsites.net",
  "schemes": [
    "https"
  ],
  "paths": {
    "/api/UpdateProductCategory": {
      "get": {
        "tags": [
          "UpdateProductCategory"
        ],
        "operationId": "UpdateProductCategory",
        "consumes": [],
        "produces": [
          "application/json",
          "text/json",
          "application/xml",
          "text/xml"
        ],
        "parameters": [
          {
            "name": "name",
            "in": "query",
            "required": true,
            "type": "string"
          },
          {
            "name": "code",
            "in": "query",
            "description": "code",
            "default": "[[Replace with the Azure Function code value]]",
            "type": "string"
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "type": "string"
            }
          }
        },
        "summary": "Updates the description of a Product Category given a name.",
        "description": "Update Product Category"
      }
    }
  },
  "definitions": {},
  "securityDefinitions": {
    "oauth2": {
      "type": "oauth2",
      "flow": "implicit",
      "authorizationUrl": "https://login.windows.net/common/oauth2/authorize",
      "scopes": {}
    }
  }
}
```

You can now create a Custom API to match the Azure Function from previous steps.

1. In the [PowerApps portal](https://powerapps.microsoft.com), click the **Connections** tab.
1. Click **New connection**, and then, on the **Custom** tab at the top, click **New custom API**.
1. Select **Swagger API definition**, click **Upload**, and then select the .json file that you just created.
1. Set the name to **ProductCategory**, and then click **Next**. 
1. Under **Authentication type**, select **Azure Active Directory**.
1. Set the **Client id** field to the **AAD custom API application ID** configuration value.
1. Set the **Client secret** field to the **AAD custom API application secret** configuration value.
1. Set the **Resource URL** field to the **AAD function resource ID** configuration value.

    **Note:** This resource ID value comes from the Azure Function application, not the Custom API application. It will resemble the following example: **https://[your_domain_name]/4598e084-55a7-4d57-88ae-59902d8e3a52**

1. Click **Create**, and verify that the new Custom API is added to the list.

Create a connection for the Custom API by following these steps.

1. On the newly created Custom API, click the plus sign (**+**) button.
1. Click **Create**, and then sign in by using your credentials.
1. You should see an authorization page that asks you to accept the terms of the app to access the Common Data Service on your behalf. Accept the terms.

# Advanced: PowerApps app building and testing 
The Custom API that you created can be used to call the Azure Function from an app. In PowerApps Studio, you can create the app and configure a button control to connect with the Custom API. You can then also test calls to the Azure Function from PowerApps Player. 

1. Create an app:
    1. In the [PowerApps portal](https://powerapps.microsoft.com), click **New app** in the lower left.
    1. Select **PowerApps Studio for web**, and then, under **Common Data Service**, click **Phone layout** to create an app from Common Data Service entities.
    1. In the entity list, select **Product category**, and then click **OK**.
1. Add the Custom API as a data source:
    1. On **Content** tab, click **Data sources**.
    1. Click **Add data source**, and select the **ProductCategory** connector.
1. Configure the button to call the Custom API:
    1. On the **BrowseScreen**, select the **BrowseGallery**, add a button control, and name it **Update**.
    1. Select the button, and change the **OnSelect** value to **ProductCategory.UpdateProductCategory(ThisItem.Name); Refresh('Product category')**.
1. Modify one of the fields so that it shows the **Description** field value:
    1. Select one of the fields under **BrowseGallery**.
    1. Change the **Text** property value to **ThisItem.Description**.
1. Test the changes by running the app:
    1. Press F5 to preview the app.
    1. Click **Update**, and note that the **Description** field of that record is updated. 

# Troubleshooting

This section provides information about the issues that are most commonly encountered and reported by consumers of this topic.

## Required permissions service isn't found

In some Azure AD configurations, such as configurations that have nested tenants, you might not be able to find **PowerApps Runtime Service** and **Windows Azure Service Management API** when you set up the required permissions in the previous step. In this case, you must directly modify the application's JSON manifest by clicking **Manifest** at the top of the registered app pane. Add the following entries under the JSON array that is named **requiredResourceAccess**, but be sure to maintain the validity of the manifest. When you've finished, click **Save**.

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

## Assembly load issue after you publish to Azure

If you started from a Visual Studio Function Application project and published it to the Azure Functions portal, you might encounter an issue where the assembly loads when the Azure Function is called. The error message might resemble the following example.

```
Function completed (Failure, Id=00000000-0000-0000-0000-000000000007)
Exception while executing function: Functions.UpdateProductCategory. Microsoft.CommonDataService.ServiceClient.Security: Could not load file or assembly 'Microsoft.CommonDataService.Common, Version=1.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35' or one of its dependencies. The system cannot find the file specified.
```

To resolve this issue, delete the project.lock.json file by following these steps.

1. Click the **View files** tab in the upper right of the pane.
1. Select the file that is named **project.lock.json**.
1. Click **Delete** at the top of the pane.
1. Reissue the request from the client.
