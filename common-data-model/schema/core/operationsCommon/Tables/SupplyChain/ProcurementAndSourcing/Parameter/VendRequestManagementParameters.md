---
title: VendRequestManagementParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Vendor request management parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/VendRequestManagementParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendRequestManagementParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor request management parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[Key](#Key)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ProspectiveVendorAddressBook](#ProspectiveVendorAddressBook)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ProspectiveVendorEffectivePeriod](#ProspectiveVendorEffectivePeriod)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[DefaultCompany](#DefaultCompany)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ExistingVendorAddressVisible](#ExistingVendorAddressVisible)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ExistingVendorDBAVisible](#ExistingVendorDBAVisible)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ExistingVendorEmailVisible](#ExistingVendorEmailVisible)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[ExistingVendorPhoneVisible](#ExistingVendorPhoneVisible)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[IsVendorPortalAdminEnabled](#IsVendorPortalAdminEnabled)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[VendorCategorySelectionLevel](#VendorCategorySelectionLevel)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[VendorCategorySelectionLevelEnabled](#VendorCategorySelectionLevelEnabled)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[IsAutoSubmitProspectiveVendorRegistrationToWorkflow](#IsAutoSubmitProspectiveVendorRegistrationToWorkflow)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[IsAutoConfirmBatchable](#IsAutoConfirmBatchable)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[Relationship_DirAddressBookRelationshipId](#Relationship_DirAddressBookRelationshipId)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendRequestManagementParameters.md" target="_blank">Parameter/VendRequestManagementParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendRequestManagementParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ProspectiveVendorAddressBook name="ProspectiveVendorAddressBook">ProspectiveVendorAddressBook</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default address book for prospective vendors</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProspectiveVendorAddressBook attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default address book for prospective vendors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProspectiveVendorEffectivePeriod name="ProspectiveVendorEffectivePeriod">ProspectiveVendorEffectivePeriod</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProspectiveVendorEffectivePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultCompany name="DefaultCompany">DefaultCompany</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default company</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExistingVendorAddressVisible name="ExistingVendorAddressVisible">ExistingVendorAddressVisible</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingVendorAddressVisible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ExistingVendorDBAVisible name="ExistingVendorDBAVisible">ExistingVendorDBAVisible</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>DBA name</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingVendorDBAVisible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DBA name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ExistingVendorEmailVisible name="ExistingVendorEmailVisible">ExistingVendorEmailVisible</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email address</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingVendorEmailVisible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ExistingVendorPhoneVisible name="ExistingVendorPhoneVisible">ExistingVendorPhoneVisible</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExistingVendorPhoneVisible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Telephone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsVendorPortalAdminEnabled name="IsVendorPortalAdminEnabled">IsVendorPortalAdminEnabled</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorPortalAdminEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorCategorySelectionLevel name="VendorCategorySelectionLevel">VendorCategorySelectionLevel</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCategorySelectionLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorCategorySelectionLevelEnabled name="VendorCategorySelectionLevelEnabled">VendorCategorySelectionLevelEnabled</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCategorySelectionLevelEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsAutoSubmitProspectiveVendorRegistrationToWorkflow name="IsAutoSubmitProspectiveVendorRegistrationToWorkflow">IsAutoSubmitProspectiveVendorRegistrationToWorkflow</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutoSubmitProspectiveVendorRegistrationToWorkflow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsAutoConfirmBatchable name="IsAutoConfirmBatchable">IsAutoConfirmBatchable</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatically confirm in batch run</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutoConfirmBatchable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatically confirm in batch run</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DirAddressBookRelationshipId name="Relationship_DirAddressBookRelationshipId">Relationship_DirAddressBookRelationshipId</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirAddressBookRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/DirAddressBook.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/DirAddressBook.cdm.json/DirAddressBook</a></td><td><a href="../../../Common/GAB/Group/DirAddressBook.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/VendRequestManagementParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
