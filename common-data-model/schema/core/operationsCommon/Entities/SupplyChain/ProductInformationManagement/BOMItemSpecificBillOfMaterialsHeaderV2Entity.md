---
title: BOMItemSpecificBillOfMaterialsHeaderV2Entity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Bill of materials headers and versions V2 in ProductInformationManagement(BOMItemSpecificBillOfMaterialsHeaderV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill of materials headers and versions V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsApproved](#IsApproved)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[IsActive](#IsActive)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ApproverId](#ApproverId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ApproverPersonnelNumber](#ApproverPersonnelNumber)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[BOMId](#BOMId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[BOMName](#BOMName)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ManufacturedItemNumber](#ManufacturedItemNumber)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[VersionBOMId](#VersionBOMId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[VersionName](#VersionName)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[VersionSiteId](#VersionSiteId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[VersionIsApproved](#VersionIsApproved)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[VersionApproverId](#VersionApproverId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[Relationship_ApprovingWorkerRelationshipId](#Relationship_ApprovingWorkerRelationshipId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[Relationship_ProductionSiteRelationshipId](#Relationship_ProductionSiteRelationshipId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[BackingTable_BOMTableRelationshipId](#BackingTable_BOMTableRelationshipId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BOMItemSpecificBillOfMaterialsHeaderV2Entity.md" target="_blank">ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity</a>|

### <a href=#IsApproved name="IsApproved">IsApproved</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApproverId name="ApproverId">ApproverId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApproverPersonnelNumber name="ApproverPersonnelNumber">ApproverPersonnelNumber</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMId name="BOMId">BOMId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMName name="BOMName">BOMName</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturedItemNumber name="ManufacturedItemNumber">ManufacturedItemNumber</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturedItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionBOMId name="VersionBOMId">VersionBOMId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionName name="VersionName">VersionName</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionSiteId name="VersionSiteId">VersionSiteId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIsApproved name="VersionIsApproved">VersionIsApproved</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIsApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionApproverId name="VersionApproverId">VersionApproverId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionApproverId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ApprovingWorkerRelationshipId name="Relationship_ApprovingWorkerRelationshipId">Relationship_ApprovingWorkerRelationshipId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ApprovingWorkerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductionSiteRelationshipId name="Relationship_ProductionSiteRelationshipId">Relationship_ProductionSiteRelationshipId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BOMTableRelationshipId name="BackingTable_BOMTableRelationshipId">BackingTable_BOMTableRelationshipId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BOMTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.cdm.json/BOMTable</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/BOMItemSpecificBillOfMaterialsHeaderV2Entity (this entity)  

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
