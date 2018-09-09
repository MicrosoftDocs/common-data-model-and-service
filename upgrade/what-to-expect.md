---
title: "What to expect on upgrading to CDS for Apps | Microsoft Docs"
description: "The topic provides information about things to expect and consider when upgrading from previous version of Common Data Service to CDS for Apps."
author: "kitabriz"
manager: "annbe"
ms.date: "09/10/2018"
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

# What to expect on upgrading to CDS for Apps

Significant platform improvements in the latest release of CDS for Apps requires
existing environments with applications built on the previous version of Common
Data Service to be upgraded.

This section covers what you should expect in your CDS for Apps database
following an upgrade and some of the key differences between the previous and
current versions.

## General structure of your application

There are extensive changes in the latest release of the [Common Data Model
(CDM)](https://github.com/Microsoft/CDM). To maximize application compatibility,
the upgrade process installs a *solution* in CDS for Apps that contains your
schema, including standard entities in the CDM and customizations, and then
copies data from your existing CDS database into these entities. For information
about solutions, see [Solutions
overview](https://docs.microsoft.com/dynamics365/customer-engagement/customize/solutions-overview).

The following solutions are installed in an upgraded CDS for Apps database:

| Solution                   | Description   |
|----------------------------|---------------|
| CDS Upgrade Foundation     | This managed solution contains the upgraded schema of the previous release of the CDM. See the considerations section below for information on the differences in the schema in this solution from the previous release. You can consider this solution to be temporary. Following upgrade, review the new standard schema in CDS for Apps and decide whether you want to manually move your data into these entities or continue to run your applications as upgraded if it suits your needs. |
| CDS Upgrade Customizations | This unmanaged solution contains customizations to the standard entities. This includes new entities added to the database and changes to the CDM schema. |
| HCM Common                 | This managed solution contains entities for the Human Capital Management (HCM) application on CDS for Apps. This is a standard solution also installed as part of the [Dynamics 365 for Talent](https://dynamics.microsoft.com/talent/overview/) application.                                                                                                                                                                                                                                  |
| HCM Common Temp            | This unmanaged solution contains customizations to the HCMCommon|

Considerations when upgrading your environment
----------------------------------------------

There are several differences between the previous version of CDS and CDS for Apps that you
should be aware of when upgrading to CDS for Apps.

-   [Some entities won't be
    upgraded](#some-entities-wont-be-upgraded)

-   [Field data
    types](#field-data-types)

-   [Entity and field
    naming](#entity-and-field-naming)

-   [Users and
    security](#users-and-security)

-   [System
    fields](#system-fields)

-   [DateTime](#datetime)

-   [Currency](#currency)

-   [Unit of Measure
    (UoM)](#unit-of-measure-uom)

-   [Organization
    Striping](#organization-striping)

-   [Image](#image)

-   [Complex data
    types](#complex-data-types)

### Some entities won't be upgraded

These entities have been deprecated and won't be upgraded.

| **Logical name**            | **Category** |
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

### Field data types

The names of most attribute data types have changed during the upgrade process.
In most cases, though, the underlying behavior of the data types themselves
hasn’t changed significantly.

| **Previously**         | **Common Data Service for Apps** |                |            |
|------------------------|----------------------------------|----------------|------------|
| **Field Type**         | **Data Type**                    | **Field Type** | **Format** |
| Email                  | Single Line of Text              | Simple         | Email      |
| Text                   | Single Line of Text              | Simple         | Text       |
| Multiline Text         | Multiple Lines of Text           |                |            |
| Address                | Multiple text fields             |                |            |
| AutoNumber             | Whole Number                     |                |            |
| Boolean                | Two Options                      |                |            |
| Currency/Currency code | Decimal / Option Set             |                |            |
| Date                   | Date and Time                    |                |            |
| DateTime               | Date and Time                    |                |            |
| Guid                   | Simple Line of text              |                |            |
| Image                  | Image                            |                |            |
| Integer                | Whole Number                     |                |            |
| Large Text             | Multiple Lines of Text           | Simple         |            |
| Number                 | Whole Number                     |                |            |
| PersonName             | Multiple text fields             |                |            |
| Phone                  | Single Line of Text              | Simple         | Phone      |
| Picklist               | Option Set                       |                |            |
| Quantity               | Whole Number                     |                |            |
| User or Group          | Not Upgraded                     |                |            |
| WebsiteUrl             | Simple line of Text              | Simple         | Url        |

### Entity and field naming

Entity and field names longer than 50 characters are truncated and ensured to be
unique. Logical, that is, unique names, will now contain a publisher prefix.
Canvas applications that reference these names will also be updated to use the
new name after you go through the upgrade process.

CDS for Apps has a primary name field, which is used in applications to easily
identify a row. For custom entities, the business key is used if it is a string.
Otherwise, a new, empty primary name field is created, and you can decide to
move data into this field to use as required.

CDS for Apps supports localized entity and field names like the previous
release. Only strings for the base language chosen during the upgrade will be
installed in the upgraded database.

### Users and security

Security principals (users) represented in CDM will not be directly copied
during the upgrade process. Current users with licenses will be synchronized to
the CDS for Apps database and granted the privileges they had previously. There
are some cases where a user’s privileges cannot be mapped precisely. An
administrator should review the security configuration following the upgrade
process to ensure their users have the right permissions.

These are some examples of differences following the upgrade process:

-   Previously, there were two privileges indicating whether you could create or
    update a record. Now there is a third privilege, Append, which allows you to
    set the value of a Lookup in a record regardless of your Create or Update
    permissions. As a result, users with Create, but not Update will not be able
    to set a Lookup value while creating a record. An administrator can address
    this by explicitly grant these users the Append privilege for the entity in
    question.

-   Business Units and Teams are used to manage security at organizational
    levels in CDS for Apps. Administrators can decide to extend their
    applications with organizational security concepts, but these won't be
    enabled out-of-the-box following an upgrade.

-   Previously, the **Open** or **Restricted** setting for the database
    controlled whether entity-level security is enforced. If the database had
    previously selected Open mode, on upgrade a security role is created with
    permissions to all upgraded entities and given it to every user.

For more information on security concepts in CDS for Apps, see [Security
concepts](https://docs.microsoft.com/dynamics365/customer-engagement/admin/security-concepts).

### System fields
Currency code
is set at the row level. The monetary value and exchange rate to the base
currency are also stored for each currency field.
Some system fields will be different after the upgrade.

| **Previously**   | **Common Data Service for Apps** |  |
|------------------|----------------------------------|--|
| **Field Name**   | **Field Name**                   | **Mapping Notes**                                                                                                                                                                                                                                             |
| CreatedDateTime  | OverriddenCreatedOn              | Set to the value from the previous release of CDS. **CreatedOn** value will reflect when the upgrade process was run.                                                                                                                                         |
| CreatedBy        | CreatedOnBehalfBy                | **CreatedOnBehalfBy** is set to the value from the previous release of CDS. **CreatedBy** will reflect the system account used to run the upgrade process. If the user from previous version of CDS cannot be synced, it will be replaced by the internal service account used to run the upgrade. |
| ModifiedDateTime | ModifiedOn                       | Not upgraded. Will display the date and time when the upgrade process was run.                                                                                                                                                                                |
| ModifiedBy       | ModifiedBy                       | Not upgraded. Will display the system account that was used to run the upgrade process.                                                                                                                                                                       |

For more information on the behavior of these system fields on import, see
[Import auditing
data](https://docs.microsoft.com/dynamics365/customer-engagement/developer/run-data-import#import-auditing-data)
.

### DateTime

In the previous release of CDS, the earliest date value allowed was 1/1/0001.
CDS for Apps does not support dates earlier than 1/1/1753. If there is a date
value earlier than 1/1/1753, it will be set to 1/1/1753 during the upgrade, and
a warning will be logged.

### Currency

Previously, every currency field was represented by two fields: currency code
and monetary value. These codes and values are upgraded as is. Support for
currency in CDS for Apps going forward is significantly different. In CDS for Apps, each currency field contains the migrated currency code, monetary value, but also contains a base currency and exchange rate. For more information about
currency support in CDS for Apps, see [Using currency
fields](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/types-of-fields#BKMK_UsingCurrencyFields).

### Unit of Measure (UoM)

Unit of Measure (UoM) values will continue to be represented as Option Sets. CDS
for Apps includes a definition of UoM in the Product entity when Dynamics 365
for Sales is installed.

### Organization Striping

If organization striping is present on an entity, it is considered a
customization and will be migrated accordingly. Keys are created in the upgraded
solutions to enforce uniqueness by organization.

### Image

Images from the previous release are copied into an image field in the entity.
There are some significant behavior differences from images in the previous
release of CDS. The image field represents a small, cropped image that appears
in the top left corner of the model-based forms to represent a row, commonly
referred to an entity image. For more information about image fields in CDS for
Apps, see [Image
fields](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/types-of-fields#BKMK_ImageFields).

If you have more than one image field on an entity and to preserve the original
image quality, the image files are also stored in related Note record(s).

### Complex data types

Address and PersonName fields are both upgraded to multiple text fields on an
entity instead of using a complex data type with references to a central entity
that defines the address schema. The provided Address and Full Name schema
available in CDS for Apps is currently limited to entities like Account,
Contact, and User.

## Next step

[Step 1: Start upgrade process for your existing database to CDS for Apps](start-upgrade-process.md)
