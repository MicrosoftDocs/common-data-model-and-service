---
title: OnlineInvoicingParameters_HU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Online invoicing system parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EInvoice/Miscellaneous/OnlineInvoicingParameters_HU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OnlineInvoicingParameters_HU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Online invoicing system parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[TechUserNameKeyVaultRef](#TechUserNameKeyVaultRef)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[TechUserPasswordKeyVaultRef](#TechUserPasswordKeyVaultRef)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[SignatureKeyKeyVaultRef](#SignatureKeyKeyVaultRef)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[ReplacementKeyKeyVaultRef](#ReplacementKeyKeyVaultRef)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Key](#Key)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[TechUserName](#TechUserName)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[TechUserPassword](#TechUserPassword)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[SignatureKey](#SignatureKey)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[ReplacementKey](#ReplacementKey)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[DataAreaId](#DataAreaId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Relationship_TechUserNameKeyVaultRefRelationshipId](#Relationship_TechUserNameKeyVaultRefRelationshipId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Relationship_TechUserPasswordKeyVaultRefRelationshipId](#Relationship_TechUserPasswordKeyVaultRefRelationshipId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Relationship_SignatureKeyKeyVaultRefRelationshipId](#Relationship_SignatureKeyKeyVaultRefRelationshipId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Relationship_ReplacementKeyKeyVaultRefRelationshipId](#Relationship_ReplacementKeyKeyVaultRefRelationshipId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="OnlineInvoicingParameters_HU.md" target="_blank">Miscellaneous/OnlineInvoicingParameters_HU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OnlineInvoicingParameters_HU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TechUserNameKeyVaultRef name="TechUserNameKeyVaultRef">TechUserNameKeyVaultRef</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technical user name secret</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechUserNameKeyVaultRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Technical user name secret</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TechUserPasswordKeyVaultRef name="TechUserPasswordKeyVaultRef">TechUserPasswordKeyVaultRef</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technical user password secret</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechUserPasswordKeyVaultRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Technical user password secret</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SignatureKeyKeyVaultRef name="SignatureKeyKeyVaultRef">SignatureKeyKeyVaultRef</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Signature key secret</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureKeyKeyVaultRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Signature key secret</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReplacementKeyKeyVaultRef name="ReplacementKeyKeyVaultRef">ReplacementKeyKeyVaultRef</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Replacement key secret</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementKeyKeyVaultRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replacement key secret</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TechUserName name="TechUserName">TechUserName</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technical user name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechUserName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Technical user name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechUserPassword name="TechUserPassword">TechUserPassword</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technical user password</td></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechUserPassword attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Technical user password</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureKey name="SignatureKey">SignatureKey</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Signature key</td></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureKey attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Signature key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ReplacementKey name="ReplacementKey">ReplacementKey</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Replacement key</td></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplacementKey attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replacement key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

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

### <a href=#Relationship_TechUserNameKeyVaultRefRelationshipId name="Relationship_TechUserNameKeyVaultRefRelationshipId">Relationship_TechUserNameKeyVaultRefRelationshipId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TechUserNameKeyVaultRefRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TechUserPasswordKeyVaultRefRelationshipId name="Relationship_TechUserPasswordKeyVaultRefRelationshipId">Relationship_TechUserPasswordKeyVaultRefRelationshipId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TechUserPasswordKeyVaultRefRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SignatureKeyKeyVaultRefRelationshipId name="Relationship_SignatureKeyKeyVaultRefRelationshipId">Relationship_SignatureKeyKeyVaultRefRelationshipId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SignatureKeyKeyVaultRefRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReplacementKeyKeyVaultRefRelationshipId name="Relationship_ReplacementKeyKeyVaultRefRelationshipId">Relationship_ReplacementKeyKeyVaultRefRelationshipId</a>

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplacementKeyKeyVaultRefRelationshipId attribute are listed below.</summary>

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

First included in: Miscellaneous/OnlineInvoicingParameters_HU (this entity)  

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
