---
title: LedgerJournalTrans_ProjectTaxExtensionIN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerJournalTrans_ProjectTaxExtensionIN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_ProjectTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[LedgerJournalTrans_Project](#LedgerJournalTrans_Project)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[AssessableValue](#AssessableValue)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[CompanyLocation](#CompanyLocation)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[CustomerLocation_IN](#CustomerLocation_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[CustomerTaxInformation_IN](#CustomerTaxInformation_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[CustomsTariffCodeTable](#CustomsTariffCodeTable)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[DirectSettlement](#DirectSettlement)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ExciseRecordType](#ExciseRecordType)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ExciseTariffCodes](#ExciseTariffCodes)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ExciseType](#ExciseType)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[Exempt](#Exempt)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[HSNCodeTable_IN](#HSNCodeTable_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ITCCategory_IN](#ITCCategory_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[SalesTaxFormTypes](#SalesTaxFormTypes)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ServiceAccountingCodeTable_IN](#ServiceAccountingCodeTable_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[ServiceCodeTable](#ServiceCodeTable)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[TaxInformation](#TaxInformation)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[VendorLocation_IN](#VendorLocation_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[VendorTaxInformation_IN](#VendorTaxInformation_IN)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[TaxInventVATCommodityCodeId](#TaxInventVATCommodityCodeId)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[Relationship_LedgerJournalTrans_ProjectRelationshipId](#Relationship_LedgerJournalTrans_ProjectRelationshipId)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalTrans_ProjectTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_ProjectTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LedgerJournalTrans_Project name="LedgerJournalTrans_Project">LedgerJournalTrans_Project</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans_Project attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssessableValue name="AssessableValue">AssessableValue</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CompanyLocation name="CompanyLocation">CompanyLocation</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerLocation_IN name="CustomerLocation_IN">CustomerLocation_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomerTaxInformation_IN name="CustomerTaxInformation_IN">CustomerTaxInformation_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsTariffCodeTable name="CustomsTariffCodeTable">CustomsTariffCodeTable</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DirectSettlement name="DirectSettlement">DirectSettlement</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExciseRecordType name="ExciseRecordType">ExciseRecordType</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExciseTariffCodes name="ExciseTariffCodes">ExciseTariffCodes</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseType name="ExciseType">ExciseType</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HSNCodeTable_IN name="HSNCodeTable_IN">HSNCodeTable_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ITCCategory_IN name="ITCCategory_IN">ITCCategory_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesTaxFormTypes name="SalesTaxFormTypes">SalesTaxFormTypes</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTable_IN name="ServiceAccountingCodeTable_IN">ServiceAccountingCodeTable_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCodeTable name="ServiceCodeTable">ServiceCodeTable</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxInformation name="TaxInformation">TaxInformation</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorLocation_IN name="VendorLocation_IN">VendorLocation_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorTaxInformation_IN name="VendorTaxInformation_IN">VendorTaxInformation_IN</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxInventVATCommodityCodeId name="TaxInventVATCommodityCodeId">TaxInventVATCommodityCodeId</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATCommodityCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

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

### <a href=#Relationship_LedgerJournalTrans_ProjectRelationshipId name="Relationship_LedgerJournalTrans_ProjectRelationshipId">Relationship_LedgerJournalTrans_ProjectRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTrans_ProjectRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/LedgerJournalTrans_Project.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/LedgerJournalTrans_Project.cdm.json/LedgerJournalTrans_Project</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/LedgerJournalTrans_Project.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTrans_ProjectTaxExtensionIN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
