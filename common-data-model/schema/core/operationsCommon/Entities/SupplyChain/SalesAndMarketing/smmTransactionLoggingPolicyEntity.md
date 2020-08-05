---
title: smmTransactionLoggingPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Transaction logging policies in SalesAndMarketing(smmTransactionLoggingPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmTransactionLoggingPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction logging policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreCustomerChangesLogged](#AreCustomerChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreCustomerTransactionChangesLogged](#AreCustomerTransactionChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreVendorChangesLogged](#AreVendorChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreVendorTransactionChangesLogged](#AreVendorTransactionChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreContactPersonChangesLogged](#AreContactPersonChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreSalesActivityChangesLogged](#AreSalesActivityChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreDocumentReferenceChangesLogged](#AreDocumentReferenceChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreSalesOrderChangesLogged](#AreSalesOrderChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreQuotationChangesLogged](#AreQuotationChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreMailingChangesLogged](#AreMailingChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreProspectChangesLogged](#AreProspectChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreTelemarketingCallListChangesLogged](#AreTelemarketingCallListChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreCampaignChangesLogged](#AreCampaignChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreOpportunityChangesLogged](#AreOpportunityChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreLeadChangesLogged](#AreLeadChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreCaseChangesLogged](#AreCaseChangesLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[LogAvailabilityDays](#LogAvailabilityDays)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreCreatedTransactionsLogged](#AreCreatedTransactionsLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[AreDeletedTransactionsLogged](#AreDeletedTransactionsLogged)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[UpdatedTransactionsLoggingRule](#UpdatedTransactionsLoggingRule)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[BackingTable_smmParametersTableRelationshipId](#BackingTable_smmParametersTableRelationshipId)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmTransactionLoggingPolicyEntity.md" target="_blank">SalesAndMarketing/smmTransactionLoggingPolicyEntity</a>|

### <a href=#AreCustomerChangesLogged name="AreCustomerChangesLogged">AreCustomerChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCustomerChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCustomerTransactionChangesLogged name="AreCustomerTransactionChangesLogged">AreCustomerTransactionChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCustomerTransactionChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreVendorChangesLogged name="AreVendorChangesLogged">AreVendorChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreVendorChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreVendorTransactionChangesLogged name="AreVendorTransactionChangesLogged">AreVendorTransactionChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreVendorTransactionChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreContactPersonChangesLogged name="AreContactPersonChangesLogged">AreContactPersonChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreContactPersonChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesActivityChangesLogged name="AreSalesActivityChangesLogged">AreSalesActivityChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesActivityChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDocumentReferenceChangesLogged name="AreDocumentReferenceChangesLogged">AreDocumentReferenceChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDocumentReferenceChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderChangesLogged name="AreSalesOrderChangesLogged">AreSalesOrderChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreQuotationChangesLogged name="AreQuotationChangesLogged">AreQuotationChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreQuotationChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreMailingChangesLogged name="AreMailingChangesLogged">AreMailingChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreMailingChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreProspectChangesLogged name="AreProspectChangesLogged">AreProspectChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreProspectChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTelemarketingCallListChangesLogged name="AreTelemarketingCallListChangesLogged">AreTelemarketingCallListChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTelemarketingCallListChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCampaignChangesLogged name="AreCampaignChangesLogged">AreCampaignChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCampaignChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOpportunityChangesLogged name="AreOpportunityChangesLogged">AreOpportunityChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOpportunityChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreLeadChangesLogged name="AreLeadChangesLogged">AreLeadChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreLeadChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCaseChangesLogged name="AreCaseChangesLogged">AreCaseChangesLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCaseChangesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogAvailabilityDays name="LogAvailabilityDays">LogAvailabilityDays</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogAvailabilityDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCreatedTransactionsLogged name="AreCreatedTransactionsLogged">AreCreatedTransactionsLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCreatedTransactionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDeletedTransactionsLogged name="AreDeletedTransactionsLogged">AreDeletedTransactionsLogged</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDeletedTransactionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpdatedTransactionsLoggingRule name="UpdatedTransactionsLoggingRule">UpdatedTransactionsLoggingRule</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdatedTransactionsLoggingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmParametersTableRelationshipId name="BackingTable_smmParametersTableRelationshipId">BackingTable_smmParametersTableRelationshipId</a>

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

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

First included in: SalesAndMarketing/smmTransactionLoggingPolicyEntity (this entity)  

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
