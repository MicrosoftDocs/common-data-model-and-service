---
title: ProjInvoiceProposalEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Project invoice proposal in ProjectManagementAndAccounting

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjInvoiceProposalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project invoice proposal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesCurrency](#SalesCurrency)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FundingSource](#FundingSource)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[Invoice](#Invoice)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[ProjectContractId](#ProjectContractId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[InvoiceProposalId](#InvoiceProposalId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[InvoiceHeaderText](#InvoiceHeaderText)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FundingSource_ContractId](#FundingSource_ContractId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FundingSourceId](#FundingSourceId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[ContractName](#ContractName)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[InvoiceFormat](#InvoiceFormat)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[DeliveryTransportBrand](#DeliveryTransportBrand)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FiscalDocumentTypeRecId](#FiscalDocumentTypeRecId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FiscalEstablishmentRecId](#FiscalEstablishmentRecId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[BillOfLadingFreightChargeTerms](#BillOfLadingFreightChargeTerms)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[ServiceFiscalInformationCode](#ServiceFiscalInformationCode)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[DeliveryVehicleLicensePlateNumber](#DeliveryVehicleLicensePlateNumber)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[DeliveryVehicleLicensePlateState](#DeliveryVehicleLicensePlateState)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[VolumeQuantity](#VolumeQuantity)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[VolumeType](#VolumeType)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FiscalDocumentTypeId](#FiscalDocumentTypeId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[BackingTable_ProjProposalJourRelationshipId](#BackingTable_ProjProposalJourRelationshipId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjInvoiceProposalEntity.md" target="_blank">ProjectManagementAndAccounting/ProjInvoiceProposalEntity</a>|

### <a href=#SalesCurrency name="SalesCurrency">SalesCurrency</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSource name="FundingSource">FundingSource</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractId name="ProjectContractId">ProjectContractId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceProposalId name="InvoiceProposalId">InvoiceProposalId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Proposal ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceProposalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice Proposal ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceHeaderText name="InvoiceHeaderText">InvoiceHeaderText</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceHeaderText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSource_ContractId name="FundingSource_ContractId">FundingSource_ContractId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSource_ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceId name="FundingSourceId">FundingSourceId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractName name="ContractName">ContractName</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceFormat name="InvoiceFormat">InvoiceFormat</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTransportBrand name="DeliveryTransportBrand">DeliveryTransportBrand</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTransportBrand attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeRecId name="FiscalDocumentTypeRecId">FiscalDocumentTypeRecId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentRecId name="FiscalEstablishmentRecId">FiscalEstablishmentRecId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfLadingFreightChargeTerms name="BillOfLadingFreightChargeTerms">BillOfLadingFreightChargeTerms</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingFreightChargeTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceFiscalInformationCode name="ServiceFiscalInformationCode">ServiceFiscalInformationCode</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceFiscalInformationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryVehicleLicensePlateNumber name="DeliveryVehicleLicensePlateNumber">DeliveryVehicleLicensePlateNumber</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryVehicleLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryVehicleLicensePlateState name="DeliveryVehicleLicensePlateState">DeliveryVehicleLicensePlateState</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryVehicleLicensePlateState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeQuantity name="VolumeQuantity">VolumeQuantity</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeType name="VolumeType">VolumeType</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeId name="FiscalDocumentTypeId">FiscalDocumentTypeId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjProposalJourRelationshipId name="BackingTable_ProjProposalJourRelationshipId">BackingTable_ProjProposalJourRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjProposalJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.cdm.json/ProjProposalJour</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjInvoiceProposalEntity (this entity)  

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
