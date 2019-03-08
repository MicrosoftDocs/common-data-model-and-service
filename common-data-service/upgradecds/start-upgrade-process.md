---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "ryjones"
ms.date: "03/03/2019"
ms.topic: "article"
ms.custom: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "IT Pro"
ms.reviewer: jdaly
ms.author: jdaly
---

# Step 1: Start upgrade process for your existing database to CDS for Apps

To use the new features in CDS for Apps, the Environment Administrator must
update their existing database that was created with the previous version of
CDS. 

## FAQs: Before upgrading your database 

These are some frequently asked questions (FAQs) before upgrading your database.

- [Which databases do I need to upgrade?](#which-databases-do-i-need-to-upgrade)
- [How do I know whether any apps or flows use this database?](#how-do-i-know-whether-any-apps-or-flows-use-this-database)
- [How long will this take?](#how-long-will-this-take)
- [Can I cancel the upgrade process once it’s initiated?](#can-i-cancel-the-upgrade-process-once-its-initiated)
- [Will there be any downtime of the database or apps in production during the upgrade?](#will-there-be-any-downtime-of-the-database-or-apps-in-production-during-the-upgrade)
- [Are there any steps I should take before I start the upgrade?](#are-there-any-steps-i-should-take-before-i-start-the-upgrade)

### Which databases do I need to upgrade? 

- Databases on the previous version of CDS used by apps and flows.
- Databases containing vital data for your organization.

You do not need to upgrade test environments and databases created while trying
out the product. Any databases that you choose not to upgrade will eventually be
deleted.

We recommend first upgrading a test or trial database (on the previous version
of CDS) to familiarize yourself with the process before upgrading your
production database.

### How do I know whether any apps or flows use this database?

When you complete Step 1 you can view a list. More information see [View Apps and flows using the database](#view-apps-and-flows-using-the-database)

If you want to know before you start Step 1 you need to use a different procedure.

#### For Apps

Use the procedure described in [Download a list of apps created in your environments](/power-platform/admin/admin-view-apps). The list you will download includes a **Connection References** column. An app that depends on the previous version of CDS will have this value included: `Common Data Service`.

If you prefer to use PowerShell, you can use the following script to return a list of apps that use the previous version CDS connector.

```powershell
<#  
    Outputs a .csv file of records that represent a premium feature found in PowerApps throughout the tenant it is run in. Result feature records will include:
        - Connections to the previous version Common Data Service Connector used in PowerApps
#>

param(
    [string]$EnvironmentName,
    [string]$Path = './powerAppsWithCommonDataService1.csv'
)

if (-not [string]::isNullOrEmpty($EnvironmentName))
{
    $apps = Get-AdminPowerApp -EnvironmentName $EnvironmentName
}
else 
{
    $apps = Get-AdminPowerApp 
}

$premiumFeatures = @()

# loop through each app
foreach ($app in $apps)
{
    # loop through each connection reference
    foreach($conRef in $app.Internal.properties.connectionReferences)
    {
        foreach($connection in $conRef)
        {
            foreach ($connId in ($connection | Get-Member -MemberType NoteProperty).Name) 
            {
                $connDetails = $($connection.$connId)

                # save connection details if the connector is premium
                if ($connDetails.id -eq '/providers/Microsoft.PowerApps/scopes/admin/apis/shared_runtimeservice')
                {
                    $row = @{
                        ResourceType = 'PowerApp'
                        DisplayName = $app.displayName
                        Name = $app.appName
                        EnvironmentName = $app.environmentName
                        ConnectorDisplayName = $connDetails.displayName
                        ConnectionId = $connDetails.id
                        ConnectionName = $connDetails.connectionName
                        CreatedByObjectId = $app.owner.id
                        CreatedByEmail = $app.owner.email
                        IsPremiumConnector = $connDetails.apiTier -eq 'Premium'
                    }
                    $premiumFeatures += $(new-object psobject -Property $row)
                }
            }
        }        
    }
}

# output to file
$premiumFeatures | Export-Csv -Path $Path
```
> [!NOTE]
> For more PowerApps Powershell installation instructions and documentation, see [PowerShell support for PowerApps (preview)](/power-platform/admin/powerapps-powershell)

#### For Flows

You can [contact support](https://powerapps.microsoft.com/support/) and provide the URL you use to view the environment. They can run a report on your behalf to return any flows using the previous version CDS database for the environment.

If you prefer PowerShell, you can use the following script to return a list of flows that use the previous version CDS connector.

```powershell
<#  
    Outputs a .csv file of records that represent a premium feature found in Flow 
    throughout the tenant it is run in. Result feature records will include:
        - Flows using previous version Common Data Service
#>

param(
    [string]$EnvironmentName,
    [string]$Path = './flowsWithCds1.csv'
)

if (-not [string]::isNullOrEmpty($EnvironmentName))
{
    $flows = Get-AdminFlow -EnvironmentName $EnvironmentName
}
else 
{
    $flows = Get-AdminFlow
}

$premiumFeatures = @()

# loop through flows
foreach ($flow in $flows)
{
    $flowDetails = $flow | Get-AdminFlow

    # loop through each connection reference
    foreach($conRef in $flowDetails.Internal.properties.connectionReferences)
    {
        foreach($connection in $conRef)
        {
            foreach ($connId in ($connection | Get-Member -MemberType NoteProperty).Name) 
            {
                $connDetails = $($connection.$connId)
                if ($connDetails.id -eq '/providers/Microsoft.PowerApps/apis/shared_runtimeservice' )
                {
                    $row = @{
                        AffectedResourceType = 'Flow'
                        DisplayName = $flowDetails.displayName
                        Name = $flowDetails.flowName
                        EnvironmentName = $flowDetails.environmentName
                        ConnectorDisplayName = $connDetails.displayName
                        ConnectionId = $connDetails.id
                        ConnectionName = $connDetails.connectionName
                        CreatedByObjectId = $flowDetails.internal.properties.creator.objectId
                    }
                    $premiumFeatures += $(new-object psobject -Property $row)
                }
            }
        }        
    }
}

$premiumFeatures | Export-Csv -Path $Path
```
> [!NOTE]
> For more PowerApps Powershell installation instructions and documentation, see [PowerShell support for PowerApps (preview)](/power-platform/admin/powerapps-powershell)

### How long will this take?

The whole upgrade is a 3 step process. Step 2 depends on the apps and flows that must be updated and tested. Time will vary and is up to you.

> [!NOTE]
> Steps 1 & 3 are automated and will require *at least* 4 hours each. The more data you have, the longer it will take.

The first step creates a test database and should provide some indication of how long the final upgrade in the 3rd step will require. There is no visual indicator of the progress during either step. You should note the duration of step 1 as an indicator of the amount of downtime in step 3.

### Can I cancel the upgrade process once it’s initiated? 

No, you cannot cancel the upgrade process for a database once you initiate it.
It’s important that you read through this entire document and understand the
process before initiating the upgrade.

> [!IMPORTANT]
> Once you start the upgrade process you must not delete the database. This will leave your environment in an inconsistent state. If you choose to abandon the upgrade process after you have started, [contact support](https://powerapps.microsoft.com/support/) for assistance.

### Will there be any downtime of the database or apps in production during the upgrade? 

The upgrade process consists of three steps as described later. Only the third
step involves downtime for the database as well as the apps and flows connecting
to it. We encourage admins to communicate to users when step 3 is planned to be executed.

> [!TIP]
> You can get an approximate duration of the downtime in step 3 by capturing the amount of time for step 1.
> 
> Note the time when you start step 1. When step 1 completes it will provide the time it completed. Compare the difference. This represents a minimum amount of downtime you can expect in step 3. Step 3 may be slightly longer under some circumstances.

### Are there any steps I should take before I start the upgrade?

- You should check to see if the previous version CDS database security settings refer to any people who are no longer with your company and remove them. This can help avoid the `Can't find XRM ID for user with oid <value> when assigning to role <value> (source role <value>) in environment <value>` error mentioned in [Errors and resolutions](errors-resolutions.md).
- If you have any entities that you aren't using, or data that you don't care about, deleting that data will reduce the risk of errors. After you start the upgrade, you can't edit entities but you can delete data.

## Start the database upgrade process

To start upgrading your database to the latest CDS for Apps: 

1.  If you’re an environment Administrator, go to the [PowerApps admin
    center](https://admin.powerapps.com/), and in the left navigation pane,
    select **Environments**.

    > [!IMPORTANT]
    > See [No environments visible](errors-resolutions.md#no-environments-visible) if you don't see a list of environments.

    Environments that have a database on the previous version of CDS have **Upgrade now** listed next to them. 

    ![Environments](media/environments.png)

2.  On the **Upgrade** page, select the language and currency of the database,
    and then select **Create test database**.  

    ![Create test database](media/create-test-database.png)

    > [!NOTE]
    > It may take several hours to create the test database. There is no progress bar. The spinning icon for the first step indicates is is running.
    >
    > You might want to start this in the afternoon and check it the next day to see how it went.
    > 
    > When you start step 1, note the time. When step 1 is completed you will be able to see the time it completed. This duration will give you an estimate for how long step 3 will require.

    A test database with the latest version of CDS for Apps is created. You can view the schema of the new database during the creation process, as shown in the following example. 

    ![Database schema](media/db-schema.png)

After the test database is created, the environment looks like the following:  

![After database upgrade](media/after-db-upgrade.png)

## Next step

Verify that the apps and flows are working as expected with the test database on
the latest version of CDS for Apps. 

### View Apps and flows using the database

When you complete step 1 you should see a list of any apps or flows that use the previous version CDS database.

> [!TIP]
> If no apps or flows are using this database, perhaps you don't need to upgrade it?
> 
> If you choose not to upgrade at this point, please contact support and ask them to delete your database.

### View Errors 

You can view all changes that occurred during creation of the test database, including any errors that occurred while copying data from the original database to the test database.  

![Errors during database upgrade](media/error-db-upgrade.png)

> [!NOTE]
> Errors shown at the end of Step 1 may or may not appear during Step 3. Generally, you can proceed to Step 2. The errors shown in Step 1 can be considered warnings and you might observe data inconsistencies related to them during Step 2. But the same errors may not occur during Step 3.

If you encounter any errors, see [Errors and resolutions](errors-resolutions.md) for information to help troubleshooting.

> [!div class="nextstepaction"]
> [Step 2: Upgrade and verify your apps and flows](upgrade-verify-apps-flows.md)
