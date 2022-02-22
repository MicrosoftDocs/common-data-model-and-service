---
title: EximEPCGBankGuaranteeDetails_IN in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Bank guarantee details in Miscellaneous(EximEPCGBankGuaranteeDetails_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/ExportImportIndia/Miscellaneous/EximEPCGBankGuaranteeDetails_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EximEPCGBankGuaranteeDetails_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank guarantee details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[BankAccountId](#BankAccountId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[Comment](#Comment)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[ExpiryDateTime](#ExpiryDateTime)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[GuaranteeAmount](#GuaranteeAmount)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[GuaranteeNum](#GuaranteeNum)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[IssueDateTime](#IssueDateTime)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[PlaceActivity](#PlaceActivity)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[SchemeApprovalRecId](#SchemeApprovalRecId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[Text](#Text)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[Relationship_BankAccountTableRelationshipId](#Relationship_BankAccountTableRelationshipId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[Relationship_EximEPCGSchemeApproveRelationshipId](#Relationship_EximEPCGSchemeApproveRelationshipId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EximEPCGBankGuaranteeDetails_IN.md" target="_blank">Miscellaneous/EximEPCGBankGuaranteeDetails_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EximEPCGBankGuaranteeDetails_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpiryDateTime name="ExpiryDateTime">ExpiryDateTime</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration date/time</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expiration date/time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#GuaranteeAmount name="GuaranteeAmount">GuaranteeAmount</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GuaranteeNum name="GuaranteeNum">GuaranteeNum</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IssueDateTime name="IssueDateTime">IssueDateTime</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date/time</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date/time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#PlaceActivity name="PlaceActivity">PlaceActivity</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlaceActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchemeApprovalRecId name="SchemeApprovalRecId">SchemeApprovalRecId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchemeApprovalRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Text name="Text">Text</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

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

### <a href=#Relationship_BankAccountTableRelationshipId name="Relationship_BankAccountTableRelationshipId">Relationship_BankAccountTableRelationshipId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/BankAccountTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json/BankAccountTable</a></td><td><a href="../../Bank/Main/BankAccountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EximEPCGSchemeApproveRelationshipId name="Relationship_EximEPCGSchemeApproveRelationshipId">Relationship_EximEPCGSchemeApproveRelationshipId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EximEPCGSchemeApproveRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EximEPCGSchemeApprove_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/ExportImportIndia/Miscellaneous/EximEPCGSchemeApprove_IN.cdm.json/EximEPCGSchemeApprove_IN</a></td><td><a href="EximEPCGSchemeApprove_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/EximEPCGBankGuaranteeDetails_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
