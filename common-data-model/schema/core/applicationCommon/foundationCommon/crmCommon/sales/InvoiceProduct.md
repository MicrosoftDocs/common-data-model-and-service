---
title: InvoiceProduct
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Invoice Product

## Properties

Display Name: Invoice Product

Description: Line item in an invoice containing detailed billing information for a product.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct](InvoiceProduct.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[createdBy](#createdBy)|Shows who created the record.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[ownerId](#ownerId)|Owner Id|[sales/InvoiceProduct](InvoiceProduct.md)|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|[sales/InvoiceProduct](InvoiceProduct.md)|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[versionNumber](#versionNumber)|Version Number|[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceDetailId](#invoiceDetailId)|Unique identifier of the invoice product line item.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[actualDeliveryOn](#actualDeliveryOn)|Enter the date when the invoiced product was delivered to the customer.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[baseAmount](#baseAmount)|Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[baseAmountBase](#baseAmountBase)|Value of the Amount in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[description](#description)|Type additional information to describe the product line item of the invoice.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[extendedAmount](#extendedAmount)|Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[extendedAmountBase](#extendedAmountBase)|Value of the Extended Amount in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceId](#invoiceId)|Unique identifier of the invoice associated with the invoice product line item.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceIsPriceLocked](#invoiceIsPriceLocked)|Information about whether invoice product pricing is locked.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceStateCode](#invoiceStateCode)|Status of the invoice product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceStateCode_display](#invoiceStateCode_display)||[sales/InvoiceProduct](InvoiceProduct.md)|
|[isCopied](#isCopied)|Select whether the invoice product is copied from another item or data source.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[isPriceOverridden](#isPriceOverridden)|Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[isProductOverridden](#isProductOverridden)|Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[lineItemNumber](#lineItemNumber)|Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[manualDiscountAmount](#manualDiscountAmount)|Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[manualDiscountAmountBase](#manualDiscountAmountBase)|Value of the Manual Discount in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[parentBundleId](#parentBundleId)|Choose the parent bundle associated with this product|[sales/InvoiceProduct](InvoiceProduct.md)|
|[productAssociationId](#productAssociationId)|Unique identifier of the product line item association with bundle in the invoice|[sales/InvoiceProduct](InvoiceProduct.md)|
|[productTypeCode](#productTypeCode)|Product Type|[sales/InvoiceProduct](InvoiceProduct.md)|
|[productTypeCode_display](#productTypeCode_display)||[sales/InvoiceProduct](InvoiceProduct.md)|
|[pricePerUnit](#pricePerUnit)|Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[pricePerUnitBase](#pricePerUnitBase)|Value of the Price Per Unit in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[pricingErrorCode](#pricingErrorCode)|Pricing error for the invoice product line item.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[pricingErrorCode_display](#pricingErrorCode_display)||[sales/InvoiceProduct](InvoiceProduct.md)|
|[productDescription](#productDescription)|Type a name or description to identify the type of write-in product included in the invoice.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[productName](#productName)|Calculated field that will be populated by name and description of the product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[productId](#productId)|Choose the product to include on the invoice.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[quantity](#quantity)|Type the amount or quantity of the product included in the invoice's total amount due.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[quantityBackordered](#quantityBackordered)|Type the amount or quantity of the product that is back ordered for the invoice.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[quantityCancelled](#quantityCancelled)|Type the amount or quantity of the product that was canceled for the invoice line item.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[quantityShipped](#quantityShipped)|Type the amount or quantity of the product that was shipped.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[salesRepId](#salesRepId)|Choose the user responsible for the sale of the invoice product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shippingTrackingNumber](#shippingTrackingNumber)|Type a tracking number for shipment of the invoiced product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToCity](#shipToCity)|Type the city for the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToCountry](#shipToCountry)|Type the country or region for the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToFax](#shipToFax)|Type the fax number for the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToFreightTermsCode](#shipToFreightTermsCode)|Select the freight terms to make sure shipping orders are processed correctly.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToFreightTermsCode_display](#shipToFreightTermsCode_display)||[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToLine1](#shipToLine1)|Type the first line of the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToLine2](#shipToLine2)|Type the second line of the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToLine3](#shipToLine3)|Type the third line of the shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToName](#shipToName)|Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToPostalCode](#shipToPostalCode)|Type the ZIP Code or postal code for the shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToStateOrProvince](#shipToStateOrProvince)|Type the state or province for the shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[shipToTelephone](#shipToTelephone)|Type the phone number for the customer's shipping address.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[tax](#tax)|Type the tax amount for the invoice product.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[taxBase](#taxBase)|Value of the Tax in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[uoMId](#uoMId)|Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[volumeDiscountAmount](#volumeDiscountAmount)|Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[volumeDiscountAmountBase](#volumeDiscountAmountBase)|Value of the Volume Discount in base currency.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[willCall](#willCall)|Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[sequenceNumber](#sequenceNumber)|Shows the ID of the data that maintains the sequence.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[propertyConfigurationStatus](#propertyConfigurationStatus)|Status of the property configuration.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[propertyConfigurationStatus_display](#propertyConfigurationStatus_display)||[sales/InvoiceProduct](InvoiceProduct.md)|
|[invoiceDetailName](#invoiceDetailName)|Invoice Detail Name. Added for 1:n Referential relationship|[sales/InvoiceProduct](InvoiceProduct.md)|
|[salesOrderDetailId](#salesOrderDetailId)|Unique identifier for Order Line associated with Invoice Line.|[sales/InvoiceProduct](InvoiceProduct.md)|
|[parentBundleIdRef](#parentBundleIdRef)|Choose the parent bundle associated with this product|[sales/InvoiceProduct](InvoiceProduct.md)|

## Attribute - Details

### <a name="createdOn">createdOn</a>

Date and time when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created On</td></tr>
<tr><td>description</td><td>Date and time when the record was created.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="createdBy">createdBy</a>

Shows who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By</td></tr>
<tr><td>description</td><td>Shows who created the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who created the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Shows who created the record.",
  "isNullable": true,
  "sourceName": "createdby"
}
```

</details>

### <a name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified On</td></tr>
<tr><td>description</td><td>Date and time when the record was modified.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.modify

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was modified.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="modifiedBy">modifiedBy</a>

Shows who last updated the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By</td></tr>
<tr><td>description</td><td>Shows who last updated the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who last updated the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Shows who last updated the record.",
  "isNullable": true,
  "sourceName": "modifiedby"
}
```

</details>

### <a name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdonbehalfby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Shows who created the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "createdonbehalfby"
}
```

</details>

### <a name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Shows who last updated the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby"
}
```

</details>

### <a name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Record Created On</td></tr>
<tr><td>description</td><td>Date and time that the record was migrated.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>overriddencreatedon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Record Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time that the record was migrated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>overriddencreatedon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Import Sequence Number</td></tr>
<tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-2147483648</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>importsequencenumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Import Sequence Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>importsequencenumber</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner Type</td></tr>
<tr><td>description</td><td>The type of owner, either User or Team.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
<tr><td>sourceName</td><td>owneridtype</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.entityName

##### is.readOnly

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The type of owner, either User or Team.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owneridtype</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="ownerId">ownerId</a>

Owner Id

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner</td></tr>
<tr><td>description</td><td>Owner Id</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>ownerid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ownerid</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Business Unit</td></tr>
<tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningbusinessunit</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning Business Unit</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningbusinessunit</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningBusinessUnit",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Business Unit"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the business unit that owns the record"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Business Unit",
  "description": "Unique identifier for the business unit that owns the record",
  "isNullable": true,
  "sourceName": "owningbusinessunit"
}
```

</details>

### <a name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning User</td></tr>
<tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owninguser</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning User</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owninguser</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "owningUser",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning User"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the user that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning User",
  "description": "Unique identifier for the user that owns the record.",
  "isNullable": true,
  "sourceName": "owninguser"
}
```

</details>

### <a name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Team</td></tr>
<tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningteam</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning Team</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningteam</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningTeam",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Team"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the team that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Team",
  "description": "Unique identifier for the team that owns the record.",
  "isNullable": true,
  "sourceName": "owningteam"
}
```

</details>

### <a name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time Zone Rule Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr>
<tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="versionNumber">versionNumber</a>

Version Number

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Version Number</td></tr>
<tr><td>description</td><td>Version Number</td></tr>
<tr><td>dataFormat</td><td>Int64</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>versionnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.dataFormat.big

##### means.measurement.version

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="invoiceDetailId">invoiceDetailId</a>

Unique identifier of the invoice product line item.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Invoice Product</td></tr>
<tr><td>description</td><td>Unique identifier of the invoice product line item.</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>invoicedetailid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"InvoiceProduct_/hasAttributes/invoiceDetailId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"InvoiceProduct_/hasAttributes/invoiceDetailId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Invoice Product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the invoice product line item.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>invoicedetailid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10000</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="actualDeliveryOn">actualDeliveryOn</a>

Enter the date when the invoiced product was delivered to the customer.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Delivered On</td></tr>
<tr><td>description</td><td>Enter the date when the invoiced product was delivered to the customer.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>actualdeliveryon</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Delivered On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Enter the date when the invoiced product was delivered to the customer.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>actualdeliveryon</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10028</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="baseAmount">baseAmount</a>

Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Amount</td></tr>
<tr><td>description</td><td>Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>baseamount</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Amount</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>baseamount</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10029</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Currency</td></tr>
<tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>transactioncurrencyid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Currency</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>transactioncurrencyid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10030</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "transactionCurrencyId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Currency"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the local currency for the record to make sure budgets are reported in the correct currency."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Currency",
  "description": "Choose the local currency for the record to make sure budgets are reported in the correct currency.",
  "isNullable": true,
  "sourceName": "transactioncurrencyid",
  "sourceOrdering": 10030
}
```

</details>

### <a name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Exchange Rate</td></tr>
<tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>100000000000</td></tr>
<tr><td>minimumValue</td><td>1E-10</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>exchangerate</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Exchange Rate</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>exchangerate</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10032</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>1E-10</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="baseAmountBase">baseAmountBase</a>

Value of the Amount in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Amount (Base)</td></tr>
<tr><td>description</td><td>Value of the Amount in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>baseamount_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>baseAmount</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Amount (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Amount in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>baseamount_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10033</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="description">description</a>

Type additional information to describe the product line item of the invoice.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Description</td></tr>
<tr><td>description</td><td>Type additional information to describe the product line item of the invoice.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>2000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>description</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Description</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type additional information to describe the product line item of the invoice.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>description</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10034</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>2000</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="extendedAmount">extendedAmount</a>

Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Extended Amount</td></tr>
<tr><td>description</td><td>Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>extendedamount</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Extended Amount</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>extendedamount</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10035</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="extendedAmountBase">extendedAmountBase</a>

Value of the Extended Amount in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Extended Amount (Base)</td></tr>
<tr><td>description</td><td>Value of the Extended Amount in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>extendedamount_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>extendedAmount</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Extended Amount (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Extended Amount in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>extendedamount_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10036</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="invoiceId">invoiceId</a>

Unique identifier of the invoice associated with the invoice product line item.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Invoice ID</td></tr>
<tr><td>description</td><td>Unique identifier of the invoice associated with the invoice product line item.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>invoiceid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Invoice ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the invoice associated with the invoice product line item.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>invoiceid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10037</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "invoiceId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "systemrequired"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Invoice ID"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the invoice associated with the invoice product line item."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Invoice ID",
  "description": "Unique identifier of the invoice associated with the invoice product line item.",
  "sourceName": "invoiceid",
  "sourceOrdering": 10037
}
```

</details>

### <a name="invoiceIsPriceLocked">invoiceIsPriceLocked</a>

Information about whether invoice product pricing is locked.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Invoice Is Price Locked</td></tr>
<tr><td>description</td><td>Information about whether invoice product pricing is locked.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>invoiceispricelocked</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Invoice Is Price Locked</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Information about whether invoice product pricing is locked.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>invoiceispricelocked</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10038</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="invoiceStateCode">invoiceStateCode</a>

Status of the invoice product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Invoice Status</td></tr>
<tr><td>description</td><td>Status of the invoice product.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>sourceName</td><td>invoicestatecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Invoice Status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status of the invoice product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>invoicestatecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10040</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="invoiceStateCode_display">invoiceStateCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>invoiceStateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="isCopied">isCopied</a>

Select whether the invoice product is copied from another item or data source.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Copied</td></tr>
<tr><td>description</td><td>Select whether the invoice product is copied from another item or data source.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>iscopied</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Copied</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select whether the invoice product is copied from another item or data source.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>iscopied</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10042</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="isPriceOverridden">isPriceOverridden</a>

Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Pricing</td></tr>
<tr><td>description</td><td>Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>ispriceoverridden</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Pricing</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ispriceoverridden</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10044</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="isProductOverridden">isProductOverridden</a>

Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Select Product</td></tr>
<tr><td>description</td><td>Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>isproductoverridden</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select Product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>isproductoverridden</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10046</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="lineItemNumber">lineItemNumber</a>

Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Line Item Number</td></tr>
<tr><td>description</td><td>Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>lineitemnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Line Item Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>lineitemnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10048</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="manualDiscountAmount">manualDiscountAmount</a>

Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Manual Discount</td></tr>
<tr><td>description</td><td>Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>1000000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>manualdiscountamount</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Manual Discount</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>manualdiscountamount</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10049</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="manualDiscountAmountBase">manualDiscountAmountBase</a>

Value of the Manual Discount in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Manual Discount (Base)</td></tr>
<tr><td>description</td><td>Value of the Manual Discount in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>manualdiscountamount_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>manualDiscountAmount</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Manual Discount (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Manual Discount in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>manualdiscountamount_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10050</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="parentBundleId">parentBundleId</a>

Choose the parent bundle associated with this product

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Parent Bundle</td></tr>
<tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>parentbundleid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Parent Bundle</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the parent bundle associated with this product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>parentbundleid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10051</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "guid",
...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "guid",
  "name": "parentBundleId",
  "appliedTraits": [
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Parent Bundle"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the parent bundle associated with this product"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Parent Bundle",
  "description": "Choose the parent bundle associated with this product",
  "isNullable": true,
  "sourceName": "parentbundleid",
  "sourceOrdering": 10051
}
```

</details>

### <a name="productAssociationId">productAssociationId</a>

Unique identifier of the product line item association with bundle in the invoice

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Bundle Item Association</td></tr>
<tr><td>description</td><td>Unique identifier of the product line item association with bundle in the invoice</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productassociationid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Bundle Item Association</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the product line item association with bundle in the invoice</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productassociationid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10052</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "guid",
...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "guid",
  "name": "productAssociationId",
  "appliedTraits": [
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Bundle Item Association"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the product line item association with bundle in the invoice"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Bundle Item Association",
  "description": "Unique identifier of the product line item association with bundle in the invoice",
  "isNullable": true,
  "sourceName": "productassociationid",
  "sourceOrdering": 10052
}
```

</details>

### <a name="productTypeCode">productTypeCode</a>

Product Type

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Product type</td></tr>
<tr><td>description</td><td>Product Type</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>sourceName</td><td>producttypecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Product",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Bundle",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Required Bundle Product",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Optional Bundle Product",
    "attributeValue": "4",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "Project-based Service",
    "attributeValue": "5",
    "displayOrder": "4"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Product</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Bundle</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Required Bundle Product</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>Optional Bundle Product</td><td>4</td><td>3</td></tr>
<tr><td>en</td><td>Project-based Service</td><td>5</td><td>4</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Product type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Product Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>producttypecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10053</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="productTypeCode_display">productTypeCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>productTypeCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="pricePerUnit">pricePerUnit</a>

Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Price Per Unit</td></tr>
<tr><td>description</td><td>Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>priceperunit</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Price Per Unit</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>priceperunit</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10055</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="pricePerUnitBase">pricePerUnitBase</a>

Value of the Price Per Unit in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Price Per Unit (Base)</td></tr>
<tr><td>description</td><td>Value of the Price Per Unit in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>priceperunit_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>pricePerUnit</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Price Per Unit (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Price Per Unit in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>priceperunit_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10056</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="pricingErrorCode">pricingErrorCode</a>

Pricing error for the invoice product line item.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Pricing Error </td></tr>
<tr><td>description</td><td>Pricing error for the invoice product line item.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>pricingerrorcode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "None",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Detail Error",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Price Level",
    "attributeValue": "2",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Inactive Price Level",
    "attributeValue": "3",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Quantity",
    "attributeValue": "4",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Unit Price",
    "attributeValue": "5",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Product",
    "attributeValue": "6",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Product",
    "attributeValue": "7",
    "displayOrder": "7"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Pricing Code",
    "attributeValue": "8",
    "displayOrder": "8"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Pricing Code",
    "attributeValue": "9",
    "displayOrder": "9"
  },
  {
    "languageTag": "en",
    "displayText": "Missing UOM",
    "attributeValue": "10",
    "displayOrder": "10"
  },
  {
    "languageTag": "en",
    "displayText": "Product Not In Price Level",
    "attributeValue": "11",
    "displayOrder": "11"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Price Level Amount",
    "attributeValue": "12",
    "displayOrder": "12"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Price Level Percentage",
    "attributeValue": "13",
    "displayOrder": "13"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Price",
    "attributeValue": "14",
    "displayOrder": "14"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Current Cost",
    "attributeValue": "15",
    "displayOrder": "15"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Standard Cost",
    "attributeValue": "16",
    "displayOrder": "16"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Price Level Amount",
    "attributeValue": "17",
    "displayOrder": "17"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Price Level Percentage",
    "attributeValue": "18",
    "displayOrder": "18"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Price",
    "attributeValue": "19",
    "displayOrder": "19"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Current Cost",
    "attributeValue": "20",
    "displayOrder": "20"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Standard Cost",
    "attributeValue": "21",
    "displayOrder": "21"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Rounding Policy",
    "attributeValue": "22",
    "displayOrder": "22"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Rounding Option",
    "attributeValue": "23",
    "displayOrder": "23"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Rounding Amount",
    "attributeValue": "24",
    "displayOrder": "24"
  },
  {
    "languageTag": "en",
    "displayText": "Price Calculation Error",
    "attributeValue": "25",
    "displayOrder": "25"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Discount Type",
    "attributeValue": "26",
    "displayOrder": "26"
  },
  {
    "languageTag": "en",
    "displayText": "Discount Type Invalid State",
    "attributeValue": "27",
    "displayOrder": "27"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Discount",
    "attributeValue": "28",
    "displayOrder": "28"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Quantity",
    "attributeValue": "29",
    "displayOrder": "29"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Pricing Precision",
    "attributeValue": "30",
    "displayOrder": "30"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Product Default UOM",
    "attributeValue": "31",
    "displayOrder": "31"
  },
  {
    "languageTag": "en",
    "displayText": "Missing Product UOM Schedule ",
    "attributeValue": "32",
    "displayOrder": "32"
  },
  {
    "languageTag": "en",
    "displayText": "Inactive Discount Type",
    "attributeValue": "33",
    "displayOrder": "33"
  },
  {
    "languageTag": "en",
    "displayText": "Invalid Price Level Currency",
    "attributeValue": "34",
    "displayOrder": "34"
  },
  {
    "languageTag": "en",
    "displayText": "Price Attribute Out Of Range",
    "attributeValue": "35",
    "displayOrder": "35"
  },
  {
    "languageTag": "en",
    "displayText": "Base Currency Attribute Overflow",
    "attributeValue": "36",
    "displayOrder": "36"
  },
  {
    "languageTag": "en",
    "displayText": "Base Currency Attribute Underflow",
    "attributeValue": "37",
    "displayOrder": "37"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>None</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Detail Error</td><td>1</td><td>1</td></tr>
<tr><td>en</td><td>Missing Price Level</td><td>2</td><td>2</td></tr>
<tr><td>en</td><td>Inactive Price Level</td><td>3</td><td>3</td></tr>
<tr><td>en</td><td>Missing Quantity</td><td>4</td><td>4</td></tr>
<tr><td>en</td><td>Missing Unit Price</td><td>5</td><td>5</td></tr>
<tr><td>en</td><td>Missing Product</td><td>6</td><td>6</td></tr>
<tr><td>en</td><td>Invalid Product</td><td>7</td><td>7</td></tr>
<tr><td>en</td><td>Missing Pricing Code</td><td>8</td><td>8</td></tr>
<tr><td>en</td><td>Invalid Pricing Code</td><td>9</td><td>9</td></tr>
<tr><td>en</td><td>Missing UOM</td><td>10</td><td>10</td></tr>
<tr><td>en</td><td>Product Not In Price Level</td><td>11</td><td>11</td></tr>
<tr><td>en</td><td>Missing Price Level Amount</td><td>12</td><td>12</td></tr>
<tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td><td>13</td></tr>
<tr><td>en</td><td>Missing Price</td><td>14</td><td>14</td></tr>
<tr><td>en</td><td>Missing Current Cost</td><td>15</td><td>15</td></tr>
<tr><td>en</td><td>Missing Standard Cost</td><td>16</td><td>16</td></tr>
<tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td><td>17</td></tr>
<tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td><td>18</td></tr>
<tr><td>en</td><td>Invalid Price</td><td>19</td><td>19</td></tr>
<tr><td>en</td><td>Invalid Current Cost</td><td>20</td><td>20</td></tr>
<tr><td>en</td><td>Invalid Standard Cost</td><td>21</td><td>21</td></tr>
<tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td><td>22</td></tr>
<tr><td>en</td><td>Invalid Rounding Option</td><td>23</td><td>23</td></tr>
<tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td><td>24</td></tr>
<tr><td>en</td><td>Price Calculation Error</td><td>25</td><td>25</td></tr>
<tr><td>en</td><td>Invalid Discount Type</td><td>26</td><td>26</td></tr>
<tr><td>en</td><td>Discount Type Invalid State</td><td>27</td><td>27</td></tr>
<tr><td>en</td><td>Invalid Discount</td><td>28</td><td>28</td></tr>
<tr><td>en</td><td>Invalid Quantity</td><td>29</td><td>29</td></tr>
<tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td><td>30</td></tr>
<tr><td>en</td><td>Missing Product Default UOM</td><td>31</td><td>31</td></tr>
<tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td><td>32</td></tr>
<tr><td>en</td><td>Inactive Discount Type</td><td>33</td><td>33</td></tr>
<tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td><td>34</td></tr>
<tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td><td>35</td></tr>
<tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td><td>36</td></tr>
<tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td><td>37</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Pricing Error </td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Pricing error for the invoice product line item.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>pricingerrorcode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10057</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>pricingErrorCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="productDescription">productDescription</a>

Type a name or description to identify the type of write-in product included in the invoice.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Write-In Product</td></tr>
<tr><td>description</td><td>Type a name or description to identify the type of write-in product included in the invoice.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>500</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productdescription</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Write-In Product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type a name or description to identify the type of write-in product included in the invoice.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productdescription</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10059</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>500</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="productName">productName</a>

Calculated field that will be populated by name and description of the product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Product Name</td></tr>
<tr><td>description</td><td>Calculated field that will be populated by name and description of the product.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>500</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productname</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Product Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Calculated field that will be populated by name and description of the product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productname</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10060</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>500</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="productId">productId</a>

Choose the product to include on the invoice.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Existing Product</td></tr>
<tr><td>description</td><td>Choose the product to include on the invoice.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Existing Product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the product to include on the invoice.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10061</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "productId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Existing Product"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the product to include on the invoice."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Existing Product",
  "description": "Choose the product to include on the invoice.",
  "isNullable": true,
  "sourceName": "productid",
  "sourceOrdering": 10061
}
```

</details>

### <a name="quantity">quantity</a>

Type the amount or quantity of the product included in the invoice's total amount due.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quantity</td></tr>
<tr><td>description</td><td>Type the amount or quantity of the product included in the invoice's total amount due.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>100000000000</td></tr>
<tr><td>minimumValue</td><td>-100000000000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>quantity</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quantity</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the amount or quantity of the product included in the invoice's total amount due.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>quantity</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10062</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="quantityBackordered">quantityBackordered</a>

Type the amount or quantity of the product that is back ordered for the invoice.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quantity Back Ordered</td></tr>
<tr><td>description</td><td>Type the amount or quantity of the product that is back ordered for the invoice.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>quantitybackordered</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quantity Back Ordered</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the amount or quantity of the product that is back ordered for the invoice.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>quantitybackordered</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10063</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="quantityCancelled">quantityCancelled</a>

Type the amount or quantity of the product that was canceled for the invoice line item.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quantity Canceled</td></tr>
<tr><td>description</td><td>Type the amount or quantity of the product that was canceled for the invoice line item.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>quantitycancelled</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quantity Canceled</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the amount or quantity of the product that was canceled for the invoice line item.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>quantitycancelled</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10064</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="quantityShipped">quantityShipped</a>

Type the amount or quantity of the product that was shipped.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quantity Shipped</td></tr>
<tr><td>description</td><td>Type the amount or quantity of the product that was shipped.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>-1000000000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>quantityshipped</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quantity Shipped</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the amount or quantity of the product that was shipped.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>quantityshipped</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10065</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1000000000</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="salesRepId">salesRepId</a>

Choose the user responsible for the sale of the invoice product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Salesperson</td></tr>
<tr><td>description</td><td>Choose the user responsible for the sale of the invoice product.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>salesrepid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Salesperson</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the user responsible for the sale of the invoice product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>salesrepid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10066</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "salesRepId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Salesperson"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the user responsible for the sale of the invoice product."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Salesperson",
  "description": "Choose the user responsible for the sale of the invoice product.",
  "isNullable": true,
  "sourceName": "salesrepid",
  "sourceOrdering": 10066
}
```

</details>

### <a name="shippingTrackingNumber">shippingTrackingNumber</a>

Type a tracking number for shipment of the invoiced product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Shipment Tracking Number</td></tr>
<tr><td>description</td><td>Type a tracking number for shipment of the invoiced product.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shippingtrackingnumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shipment Tracking Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type a tracking number for shipment of the invoiced product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shippingtrackingnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10067</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToCity">shipToCity</a>

Type the city for the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To City</td></tr>
<tr><td>description</td><td>Type the city for the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>80</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_city</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.city

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To City</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the city for the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_city</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10068</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>80</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToCountry">shipToCountry</a>

Type the country or region for the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Country/Region</td></tr>
<tr><td>description</td><td>Type the country or region for the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>80</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_country</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.country

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Country/Region</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the country or region for the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_country</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10069</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>80</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToFax">shipToFax</a>

Type the fax number for the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Fax</td></tr>
<tr><td>description</td><td>Type the fax number for the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>50</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_fax</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Fax</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the fax number for the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_fax</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10070</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>50</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToFreightTermsCode">shipToFreightTermsCode</a>

Select the freight terms to make sure shipping orders are processed correctly.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Freight Terms</td></tr>
<tr><td>description</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_freighttermscode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "FOB",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "No Charge",
    "attributeValue": "2",
    "displayOrder": "1"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>FOB</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>No Charge</td><td>2</td><td>1</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Freight Terms</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_freighttermscode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10071</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToFreightTermsCode_display">shipToFreightTermsCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>shipToFreightTermsCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="shipToLine1">shipToLine1</a>

Type the first line of the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Street 1</td></tr>
<tr><td>description</td><td>Type the first line of the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>250</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_line1</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.address

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Street 1</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the first line of the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_line1</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10073</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>250</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToLine2">shipToLine2</a>

Type the second line of the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Street 2</td></tr>
<tr><td>description</td><td>Type the second line of the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>250</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_line2</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.address

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Street 2</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the second line of the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_line2</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10074</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>250</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToLine3">shipToLine3</a>

Type the third line of the shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Street 3</td></tr>
<tr><td>description</td><td>Type the third line of the shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>250</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_line3</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.address

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Street 3</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the third line of the shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_line3</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10075</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>250</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToName">shipToName</a>

Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Name</td></tr>
<tr><td>description</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>200</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_name</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_name</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10076</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>200</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToPostalCode">shipToPostalCode</a>

Type the ZIP Code or postal code for the shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr>
<tr><td>description</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>20</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_postalcode</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.postalCode

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To ZIP/Postal Code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_postalcode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10077</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>20</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToStateOrProvince">shipToStateOrProvince</a>

Type the state or province for the shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To State/Province</td></tr>
<tr><td>description</td><td>Type the state or province for the shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>50</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_stateorprovince</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.location.stateOrProvince

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To State/Province</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the state or province for the shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_stateorprovince</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10078</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>50</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="shipToTelephone">shipToTelephone</a>

Type the phone number for the customer's shipping address.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To Phone</td></tr>
<tr><td>description</td><td>Type the phone number for the customer's shipping address.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>50</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>shipto_telephone</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.service.phone

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To Phone</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the phone number for the customer's shipping address.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>shipto_telephone</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10079</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>50</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="tax">tax</a>

Type the tax amount for the invoice product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Tax</td></tr>
<tr><td>description</td><td>Type the tax amount for the invoice product.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>1000000000000</td></tr>
<tr><td>minimumValue</td><td>-1000000000000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>tax</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Tax</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the tax amount for the invoice product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>tax</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10080</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1000000000000</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="taxBase">taxBase</a>

Value of the Tax in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Tax (Base)</td></tr>
<tr><td>description</td><td>Value of the Tax in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>tax_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>tax</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Tax (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Tax in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>tax_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10081</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="uoMId">uoMId</a>

Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Unit</td></tr>
<tr><td>description</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>uomid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unit</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>uomid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10082</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "uoMId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unit"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Unit",
  "description": "Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.",
  "isNullable": true,
  "sourceName": "uomid",
  "sourceOrdering": 10082
}
```

</details>

### <a name="volumeDiscountAmount">volumeDiscountAmount</a>

Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Volume Discount</td></tr>
<tr><td>description</td><td>Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>volumediscountamount</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Volume Discount</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>volumediscountamount</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10083</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="volumeDiscountAmountBase">volumeDiscountAmountBase</a>

Value of the Volume Discount in base currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Volume Discount (Base)</td></tr>
<tr><td>description</td><td>Value of the Volume Discount in base currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>922337203685477</td></tr>
<tr><td>minimumValue</td><td>-922337203685477</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>volumediscountamount_base</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### means.measurement.currency

##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>volumeDiscountAmount</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Volume Discount (Base)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value of the Volume Discount in base currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>volumediscountamount_base</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10084</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="willCall">willCall</a>

Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Ship To</td></tr>
<tr><td>description</td><td>Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>willcall</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Ship To</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>willcall</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10085</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="sequenceNumber">sequenceNumber</a>

Shows the ID of the data that maintains the sequence.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Sequence Number</td></tr>
<tr><td>description</td><td>Shows the ID of the data that maintains the sequence.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-2147483648</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>sequencenumber</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sequence Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the ID of the data that maintains the sequence.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>sequencenumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10087</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="propertyConfigurationStatus">propertyConfigurationStatus</a>

Status of the property configuration.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Property Configuration</td></tr>
<tr><td>description</td><td>Status of the property configuration.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>sourceName</td><td>propertyconfigurationstatus</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Edit",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Rectify",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Not Configured",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Edit</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Rectify</td><td>1</td><td>1</td></tr>
<tr><td>en</td><td>Not Configured</td><td>2</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Property Configuration</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status of the property configuration.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>propertyconfigurationstatus</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10088</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="propertyConfigurationStatus_display">propertyConfigurationStatus_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>propertyConfigurationStatus</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="invoiceDetailName">invoiceDetailName</a>

Invoice Detail Name. Added for 1:n Referential relationship

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Name</td></tr>
<tr><td>description</td><td>Invoice Detail Name. Added for 1:n Referential relationship</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>invoicedetailname</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Invoice Detail Name. Added for 1:n Referential relationship</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>invoicedetailname</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10095</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="salesOrderDetailId">salesOrderDetailId</a>

Unique identifier for Order Line associated with Invoice Line.

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Order Product Id</td></tr>
<tr><td>description</td><td>Unique identifier for Order Line associated with Invoice Line.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>salesorderdetailid</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Order Product Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for Order Line associated with Invoice Line.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>salesorderdetailid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10096</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "salesOrderDetailId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Order Product Id"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for Order Line associated with Invoice Line."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Order Product Id",
  "description": "Unique identifier for Order Line associated with Invoice Line.",
  "isNullable": true,
  "sourceName": "salesorderdetailid",
  "sourceOrdering": 10096
}
```

</details>

### <a name="parentBundleIdRef">parentBundleIdRef</a>

Choose the parent bundle associated with this product

First included in: /core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json/InvoiceProduct

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Parent bundle product</td></tr>
<tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>parentbundleidref</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Parent bundle product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the parent bundle associated with this product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>parentbundleidref</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10097</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "parentBundleIdRef",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Parent bundle product"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the parent bundle associated with this product"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Parent bundle product",
  "description": "Choose the parent bundle associated with this product",
  "isNullable": true,
  "sourceName": "parentbundleidref",
  "sourceOrdering": 10097
}
```

</details>

