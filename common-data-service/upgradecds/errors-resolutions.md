---
title: "Errors and resolutions when upgrading previous version of Common Data Service. | Microsoft Docs"
description: "Provides known errors and resolutions when upgrading from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "annbe"
ms.date: "01/24/2019"
ms.topic: "article"
ms.custom: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "IT Pro"
ms.reviewer: kvivek
ms.author: jdaly
---
# Errors and resolutions

This section provides information about possible errors you might see during upgrade steps and how to resolve them.

|Error  |Description and resolution  |
|--|--|
|Errors to migrate From CDM `PositionWorkerAssignment` to CDS2 `cdm_positionworkerassignmentmaps`, exported record count 17 but imported record count 0, error count 17|The overall data upgrade has completed but we encountered an error while upgrading this entity due to which either one or more records failed to upgrade. These records will not be available to you in CDS for Apps. Please create a support ticket if you need the missing data extracted from previous version of CDS.|
|`CdsUpgradeInternalFailure` . The CDS upgrade process has encountered an error. The tracking id for this request was \<value> |We encountered an error due to which Upgrade has failed. You may retry the step.| 
|Can't find XRM ID for user with oid \<value> when assigning to role \<value> (source role \<value>) in environment \<value>|The user with AAD Object Id {0} wasn’t synced to the upgraded CDS instance yet, so the role assignment to role {1} can’t be migrated for that user. Unless the user is deleted or disabled in the AAD tenant, you can assign the necessary role manually once the user is synced (which can take up to a couple of days).<br/><br/>To find the user with AAD Object Id {0}, you can go to the following URL:<br/>`<`[Base CDS Url](#base-cds-url)`>/api/data/v9.0/systemusers()?$select=fullname&$filter=azureactivedirectoryobjectid%20eq%20{0}`<br/>and look at the value of the fullname property.<br/><br/>To find which role has the ID {1}, you can go to the following URL:<br/>`<`[Base CDS Url](#base-cds-url)`>/api/data/v9.0/roles({1})?$select=name`<br/>and look at the value of the name property.<br/><br/>You can then use the security tab in the Admin portal to assign the user to the role.|

## Deleting test databases

Any test databases created during step 1 will automatically be deleted 2 days after the upgrade succeeds. You don't need to delete them.

If one or more upgrade attempts fail, the test databases will remain until the upgrade finally succeeds.

## Base CDS Url

Some troubleshooting step includes instructions to query the CDS for apps Web API, a RESTful Odata endpoint.

You can get data in JSON format by executing `HTTP GET` requests using the address bar of your browser, or by using other tools such as [Postman](https://www.getpostman.com/).

To do this, you will need to know the base url for your environment. This base URL will typically look something like this `https://org97209.crm.dynamics.com` where `org97209` is the name of the CDS for Apps environment. The value `crm` is for North America. Other regions will have different values. More information: [Web API URL](/powerapps/developer/common-data-service/webapi/compose-http-requests-handle-errors#web-api-url-and-versions)

> [!TIP]
> If you type the URL in your browser, the JSON data can be difficult to read because it isn't formatted. There are many online JSON formatting tools you can use. Simply copy the results from your browser to a site like [JSON Formatter](https://jsonformatter.curiousconcept.com/) and it will add formatting to make the JSON easier to read.

More information: [Use Postman with Web API](/dynamics365/customer-engagement/developer/webapi/use-postman-web-api)

## No environments visible

If you go to the [PowerApps admin center](https://admin.powerapps.com/) as described in [Start the database upgrade process](start-upgrade-process.md#start-the-database-upgrade-process) and you cannot see any environments, it may be that you don't have the required PowerApps Plan 2 license.

Go to [https://powerapps.microsoft.com/pricing/](https://powerapps.microsoft.com/pricing/) and request a PowerApps Plan 2 license. A free trial should be enough to provide the privileges you will need to complete the upgrade steps. 
