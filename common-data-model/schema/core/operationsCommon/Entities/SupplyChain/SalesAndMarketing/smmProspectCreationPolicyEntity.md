---
title: smmProspectCreationPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Prospect creation policies in SalesAndMarketing(smmProspectCreationPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmProspectCreationPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prospect creation policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultProspectRelationTypeId](#DefaultProspectRelationTypeId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultLanguageId](#DefaultLanguageId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultVendorGroupId](#DefaultVendorGroupId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultCustomerGroupId](#DefaultCustomerGroupId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultCurrencyCode](#DefaultCurrencyCode)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultBusinessOpeningTime](#DefaultBusinessOpeningTime)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultBusinessClosingTime](#DefaultBusinessClosingTime)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[DefaultProspectStatusId](#DefaultProspectStatusId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[WillProspectConversionOpenRelationTypeForm](#WillProspectConversionOpenRelationTypeForm)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[BackingTable_smmParametersTableRelationshipId](#BackingTable_smmParametersTableRelationshipId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmProspectCreationPolicyEntity.md" target="_blank">SalesAndMarketing/smmProspectCreationPolicyEntity</a>|

### <a href=#DefaultProspectRelationTypeId name="DefaultProspectRelationTypeId">DefaultProspectRelationTypeId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProspectRelationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLanguageId name="DefaultLanguageId">DefaultLanguageId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorGroupId name="DefaultVendorGroupId">DefaultVendorGroupId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerGroupId name="DefaultCustomerGroupId">DefaultCustomerGroupId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCurrencyCode name="DefaultCurrencyCode">DefaultCurrencyCode</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBusinessOpeningTime name="DefaultBusinessOpeningTime">DefaultBusinessOpeningTime</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBusinessOpeningTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBusinessClosingTime name="DefaultBusinessClosingTime">DefaultBusinessClosingTime</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBusinessClosingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProspectStatusId name="DefaultProspectStatusId">DefaultProspectStatusId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProspectStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProspectConversionOpenRelationTypeForm name="WillProspectConversionOpenRelationTypeForm">WillProspectConversionOpenRelationTypeForm</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProspectConversionOpenRelationTypeForm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmParametersTableRelationshipId name="BackingTable_smmParametersTableRelationshipId">BackingTable_smmParametersTableRelationshipId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_smmParametersTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.cdm.json/smmParametersTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmProspectCreationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
