---
title: WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Cross-docking opportunity policy demand source selection criteria in WMS(WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cross-docking opportunity policy demand source selection criteria</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DemandSourceTypeCriterion](#DemandSourceTypeCriterion)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[PrioritySequenceNumber](#PrioritySequenceNumber)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[CrossDockingOpportunityPolicyRecId](#CrossDockingOpportunityPolicyRecId)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[MustAppointmentSchedulingHaveAssignedLocationCriterion](#MustAppointmentSchedulingHaveAssignedLocationCriterion)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[CrossDockingPrioritizationStrategy](#CrossDockingPrioritizationStrategy)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[CrossDockingOpportunityPolicyName](#CrossDockingOpportunityPolicyName)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[Relationship_CrossDockingOpportunityPolicyRelationshipId](#Relationship_CrossDockingOpportunityPolicyRelationshipId)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId](#BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity.md" target="_blank">WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity</a>|

### <a href=#DemandSourceTypeCriterion name="DemandSourceTypeCriterion">DemandSourceTypeCriterion</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSourceTypeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrioritySequenceNumber name="PrioritySequenceNumber">PrioritySequenceNumber</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrioritySequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossDockingOpportunityPolicyRecId name="CrossDockingOpportunityPolicyRecId">CrossDockingOpportunityPolicyRecId</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockingOpportunityPolicyRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MustAppointmentSchedulingHaveAssignedLocationCriterion name="MustAppointmentSchedulingHaveAssignedLocationCriterion">MustAppointmentSchedulingHaveAssignedLocationCriterion</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MustAppointmentSchedulingHaveAssignedLocationCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossDockingPrioritizationStrategy name="CrossDockingPrioritizationStrategy">CrossDockingPrioritizationStrategy</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockingPrioritizationStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossDockingOpportunityPolicyName name="CrossDockingOpportunityPolicyName">CrossDockingOpportunityPolicyName</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockingOpportunityPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CrossDockingOpportunityPolicyRelationshipId name="Relationship_CrossDockingOpportunityPolicyRelationshipId">Relationship_CrossDockingOpportunityPolicyRelationshipId</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CrossDockingOpportunityPolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId name="BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId">BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSCrossDockDemandSourceSelectionCriteriaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria.cdm.json/WHSCrossDockDemandSourceSelectionCriteria</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSCrossDockingOpportunityPolicyDemandSourceSelectionCriteriaEntity (this entity)  

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
