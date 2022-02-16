---
title: WorkflowParticipantExpenTokenLine in Reference - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Workflow participant expenditure token legal entity in Reference(WorkflowParticipantExpenTokenLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Reference/WorkflowParticipantExpenTokenLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowParticipantExpenTokenLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow participant expenditure token legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[IsProjectControllerAuthority](#IsProjectControllerAuthority)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[IsProjectManagerAuthority](#IsProjectManagerAuthority)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[IsProjectSalesManagerAuthority](#IsProjectSalesManagerAuthority)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[LegalEntity](#LegalEntity)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[OrganizationDimensionAttributeSet](#OrganizationDimensionAttributeSet)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[ProjectDimensionAttributeSet](#ProjectDimensionAttributeSet)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[Token](#Token)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[Relationship_OrganizationDimensionAttributeSetRelationshipId](#Relationship_OrganizationDimensionAttributeSetRelationshipId)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[Relationship_ProjectDimensionAttributeSetRelationshipId](#Relationship_ProjectDimensionAttributeSetRelationshipId)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|
|[Relationship_WorkflowParticipantExpenTokenRelationshipId](#Relationship_WorkflowParticipantExpenTokenRelationshipId)||<a href="WorkflowParticipantExpenTokenLine.md" target="_blank">Reference/WorkflowParticipantExpenTokenLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowParticipantExpenTokenLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsProjectControllerAuthority name="IsProjectControllerAuthority">IsProjectControllerAuthority</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project controller</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectControllerAuthority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project controller</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsProjectManagerAuthority name="IsProjectManagerAuthority">IsProjectManagerAuthority</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project manager</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectManagerAuthority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project manager</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsProjectSalesManagerAuthority name="IsProjectSalesManagerAuthority">IsProjectSalesManagerAuthority</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project sales manager</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectSalesManagerAuthority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project sales manager</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OrganizationDimensionAttributeSet name="OrganizationDimensionAttributeSet">OrganizationDimensionAttributeSet</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationDimensionAttributeSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjectDimensionAttributeSet name="ProjectDimensionAttributeSet">ProjectDimensionAttributeSet</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDimensionAttributeSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Token name="Token">Token</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Token attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OrganizationDimensionAttributeSetRelationshipId name="Relationship_OrganizationDimensionAttributeSetRelationshipId">Relationship_OrganizationDimensionAttributeSetRelationshipId</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrganizationDimensionAttributeSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Reference/DimensionAttributeSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttributeSet.cdm.json/DimensionAttributeSet</a></td><td><a href="../../../Finance/FinancialDimensions/Reference/DimensionAttributeSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectDimensionAttributeSetRelationshipId name="Relationship_ProjectDimensionAttributeSetRelationshipId">Relationship_ProjectDimensionAttributeSetRelationshipId</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectDimensionAttributeSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Reference/DimensionAttributeSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttributeSet.cdm.json/DimensionAttributeSet</a></td><td><a href="../../../Finance/FinancialDimensions/Reference/DimensionAttributeSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowParticipantExpenTokenRelationshipId name="Relationship_WorkflowParticipantExpenTokenRelationshipId">Relationship_WorkflowParticipantExpenTokenRelationshipId</a>

First included in: Reference/WorkflowParticipantExpenTokenLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowParticipantExpenTokenRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowParticipantExpenToken.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Reference/WorkflowParticipantExpenToken.cdm.json/WorkflowParticipantExpenToken</a></td><td><a href="WorkflowParticipantExpenToken.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
