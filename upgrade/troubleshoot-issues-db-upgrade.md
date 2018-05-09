---
title: "Considerations for upgrading to CDS for Apps | Microsoft Docs"
description: "The topic provides information about things you might want to know and consider when upgrading from previous version of Common Data Service (CDS) to CDS for Apps"
author: "KumarVivek"
manager: "robinarh"
ms.date: "05/15/2018"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "Common Data Service for Apps, CDS for Apps, Upgrade"
audience: "Administrator"
ms.assetid: "26e8323d-8d74-480b-8180-870180e7bcd8"
ms.reviewer: kvivek
ms.author: kitabriz
---


# Considerations for upgrading to CDS for Apps

Significant platform improvements in the latest release of Common Data Service (CDS) for Apps requires existing environments with applications built on the previous version of Common Data Service to be upgraded. For more information about the new capabilities available in the latest release of CDS for Apps, see this blog post: [https://powerapps.microsoft.com/en-us/blog/cds-for-apps-march/](https://powerapps.microsoft.com/en-us/blog/cds-for-apps-march/)

This topic covers what you should expect in your CDS for Apps database following an upgrade and some of the key differences between the previous and current versions.

## General structure of your application

There are extensive changes in the latest release of the [Common Data Model (CDM)](https://github.com/Microsoft/CDM). To maximize application compatibility, the upgrade process installs a *solution* in CDS for Apps that contains your schema, including standard entities in the CDM and customizations, and then copies data from your existing CDS database into these entities. For information about solutions, see [Solutions overview](https://docs.microsoft.com/dynamics365/customer-engagement/customize/solutions-overview). 

The following solutions are installed in an upgraded CDS for Apps database:

|Solution|Description|
|--|--|
|CDS Upgrade Foundation|This managed solution contains the upgraded schema of the previous release of the CDM.  See the considerations section below for information on the differences in the schema in this solution from the previous release.  You can consider this solution to be temporary.  Following upgrade, review the new standard schema in CDS for Apps and decide whether you want to manually move your data into these entities or continue to run your applications as upgraded if it suits your needs.|
|CDS Upgrade Customizations|This unmanaged solution contains customizations to the standard entities.  This includes new entities added to the database and changes to the CDM schema.|
|HCMCommon|This managed solution contains entities for the Human Capital Management (HCM) application on CDS for Apps.  This is a standard solution also installed as part of the [Dynamics 365 for Talent](https://dynamics.microsoft.com/talent/overview/) application.|
|HCMCommon Customizations|This unmanaged solution contains customizations to the HCMCommon entities.|

## Considerations when upgrading your environment

There are several differences in the latest release of CDS for Apps that you should be aware of when upgrading from the previous version of CDS.

### Some entities won't be upgraded

These entities have been deprecated and won't be upgraded.

| Logical name                | Category     |
|-----------------------------|--------------|
| Application user            | Person       |
| Application user contact    | Person       |
| Application user group      | Group        |
| Purchase order line charge  | Purchase     |
| Purchase order line receipt | Purchase     |
| Purchase order line tax     | Purchase     |
| Purchase order tax          | Purchase     |
| Quotation charge            | Sales        |
| Quotation line charge       | Sales        |
| Quotation line tax          | Sales        |
| Quotation tax               | Sales        |
| Sales invoice charge        | Sales        |
| Sales invoice line charge   | Sales        |
| Sales invoice line tax      | Sales        |
| Sales invoice tax           | Sales        |
| Sales order charge          | Sales        |
| Sales order line charge     | Sales        |
| Sales order line tax        | Sales        |
| Sales order tax             | Sales        |
| Vendor invoice charge       | Purchase     |
| Vendor invoice line charge  | Purchase     |
| Vendor invoice line tax     | Purchase     |
| Vendor invoice tax          | Purchase     |

### Field Data Types

The names of most attribute data types have changed during the upgrade process. In most cases, though, the underlying behavior of the data types themselves hasn’t changed significantly.

<table title="" border="1" cellspacing="0" cellpadding="0" summary="">
    <tbody>
        <tr>
            <td width="13    0" valign="top">
                <h2>
                    Previously
                </h2>
            </td>
            <td width="296" valign="top" colspan="3">
                <h2 align="center">
                    Common Data Service for Apps
                </h2>
            </td>
        </tr>
        <tr>
            <td width="130" valign="top">
                <p>
                    <strong> Field Type</strong>
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    <strong>Data Type</strong>
                </p>
            </td>
            <td width="69" valign="top">
                <p align="center">
                    <strong>Field Type</strong>
                </p>
            </td>
            <td width="51" valign="top">
                <p align="center">
                    <strong>Format</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Email
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Single Line of Text
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    Simple
                </p>
            </td>
            <td width="51" valign="top">
                <p>
                    Email
                </p>
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Text
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Single Line of Text
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    Simple
                </p>
            </td>
            <td width="51" valign="top">
                <p>
                    Text
                </p>
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Multiline Text
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Multiple Lines of Text
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Address
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Multiple text fields
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    AutoNumber
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Whole Number
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Boolean
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Two Options
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Currency/Currency code
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Decimal / Option Set
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Date
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Date and Time
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    DateTime
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Date and Time
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Guid
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Simple Line of text
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Image
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Image
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Integer
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Whole Number
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Large Text
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Multiple Lines of Text
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    Simple
                </p>
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Number
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Whole Number
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    PersonName
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Multiple text fields
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Phone
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Single Line of Text
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    Simple
                </p>
            </td>
            <td width="51" valign="top">
                <p>
                    Phone
                </p>
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Picklist
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Option Set
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    Quantity
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Whole Number
                </p>
            </td>
            <td width="69" valign="top">
            </td>
            <td width="51" valign="top">
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    User Or Group
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Not Upgraded
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    <s>
                    </s>
                </p>
            </td>
            <td width="51" valign="top">
                <p>
                    <s>
                    </s>
                </p>
            </td>
        </tr>
        <tr>
            <td width="101" valign="top">
                <p>
                    WebsiteUrl
                </p>
            </td>
            <td width="176" valign="top">
                <p>
                    Simple line of Text
                </p>
            </td>
            <td width="69" valign="top">
                <p>
                    Simple
                </p>
            </td>
            <td width="51" valign="top">
                <p>
                    Url
                </p>
            </td>
        </tr>
    </tbody>
</table>