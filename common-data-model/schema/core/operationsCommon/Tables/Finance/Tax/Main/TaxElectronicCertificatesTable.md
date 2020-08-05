---
title: TaxElectronicCertificatesTable in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Electronic tax certificates in Main(TaxElectronicCertificatesTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Main/TaxElectronicCertificatesTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxElectronicCertificatesTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic tax certificates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[CertificateReference](#CertificateReference)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[CertificateType](#CertificateType)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[UserId](#UserId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[SignerKeyVaultCertificateRef](#SignerKeyVaultCertificateRef)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[EncryptKeyVaultCertificateRef](#EncryptKeyVaultCertificateRef)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[ElsterKeyVaultCertificateRef](#ElsterKeyVaultCertificateRef)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[AuthKeyVaultCertificateRef](#AuthKeyVaultCertificateRef)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[Relationship_SignerKeyVaultCertificateTableRelationshipId](#Relationship_SignerKeyVaultCertificateTableRelationshipId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[Relationship_EncryptKeyVaultCertificateTableRelationshipId](#Relationship_EncryptKeyVaultCertificateTableRelationshipId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[Relationship_ElsterKeyVaultCertificateTableRelationshipId](#Relationship_ElsterKeyVaultCertificateTableRelationshipId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[Relationship_AuthKeyVaultCertificateTableRelationshipId](#Relationship_AuthKeyVaultCertificateTableRelationshipId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxElectronicCertificatesTable.md" target="_blank">Main/TaxElectronicCertificatesTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxElectronicCertificatesTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CertificateReference name="CertificateReference">CertificateReference</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateType name="CertificateType">CertificateType</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignerKeyVaultCertificateRef name="SignerKeyVaultCertificateRef">SignerKeyVaultCertificateRef</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Signer certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignerKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Signer certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EncryptKeyVaultCertificateRef name="EncryptKeyVaultCertificateRef">EncryptKeyVaultCertificateRef</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encrypt certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EncryptKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Encrypt certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ElsterKeyVaultCertificateRef name="ElsterKeyVaultCertificateRef">ElsterKeyVaultCertificateRef</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Elster certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElsterKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Elster certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AuthKeyVaultCertificateRef name="AuthKeyVaultCertificateRef">AuthKeyVaultCertificateRef</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auth. certificate</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthKeyVaultCertificateRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Auth. certificate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

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

### <a href=#Relationship_SignerKeyVaultCertificateTableRelationshipId name="Relationship_SignerKeyVaultCertificateTableRelationshipId">Relationship_SignerKeyVaultCertificateTableRelationshipId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SignerKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EncryptKeyVaultCertificateTableRelationshipId name="Relationship_EncryptKeyVaultCertificateTableRelationshipId">Relationship_EncryptKeyVaultCertificateTableRelationshipId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EncryptKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ElsterKeyVaultCertificateTableRelationshipId name="Relationship_ElsterKeyVaultCertificateTableRelationshipId">Relationship_ElsterKeyVaultCertificateTableRelationshipId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ElsterKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AuthKeyVaultCertificateTableRelationshipId name="Relationship_AuthKeyVaultCertificateTableRelationshipId">Relationship_AuthKeyVaultCertificateTableRelationshipId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AuthKeyVaultCertificateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.cdm.json/KeyVaultCertificateTable</a></td><td><a href="../../../System/SystemAdministration/Miscellaneous/KeyVaultCertificateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/TaxElectronicCertificatesTable (this entity)  

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
