---
title: PSAParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PSAParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Parameter/PSAParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ApprActiveInvoiceProposal](#ApprActiveInvoiceProposal)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[BudgetMethod](#BudgetMethod)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ContractLineFeeJournalNameId](#ContractLineFeeJournalNameId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[Key](#Key)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ProjProposalSalesUpdate](#ProjProposalSalesUpdate)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[PSAActivityDisplayDefault](#PSAActivityDisplayDefault)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[PSAActivityLookupSubproject](#PSAActivityLookupSubproject)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[PSAActivityLookupTask](#PSAActivityLookupTask)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqControl](#ReqControl)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqControlProjectOverride](#ReqControlProjectOverride)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqHourProjectOverride](#ReqHourProjectOverride)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqHourValidate](#ReqHourValidate)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqItemProjectOverride](#ReqItemProjectOverride)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[ReqItemValidate](#ReqItemValidate)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[SchedDefaultCalendar](#SchedDefaultCalendar)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[EnableHourScheduling](#EnableHourScheduling)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[EnableSchedulingWorkflow](#EnableSchedulingWorkflow)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[Relationship_ProjJournalNameRelationshipId](#Relationship_ProjJournalNameRelationshipId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[Relationship_WorkCalendarTableRelationshipId](#Relationship_WorkCalendarTableRelationshipId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PSAParameters.md" target="_blank">Parameter/PSAParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PSAParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApprActiveInvoiceProposal name="ApprActiveInvoiceProposal">ApprActiveInvoiceProposal</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprActiveInvoiceProposal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetMethod name="BudgetMethod">BudgetMethod</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ContractLineFeeJournalNameId name="ContractLineFeeJournalNameId">ContractLineFeeJournalNameId</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractLineFeeJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ProjProposalSalesUpdate name="ProjProposalSalesUpdate">ProjProposalSalesUpdate</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjProposalSalesUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSAActivityDisplayDefault name="PSAActivityDisplayDefault">PSAActivityDisplayDefault</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAActivityDisplayDefault attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSAActivityLookupSubproject name="PSAActivityLookupSubproject">PSAActivityLookupSubproject</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAActivityLookupSubproject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSAActivityLookupTask name="PSAActivityLookupTask">PSAActivityLookupTask</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAActivityLookupTask attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqControl name="ReqControl">ReqControl</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqControl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqControlProjectOverride name="ReqControlProjectOverride">ReqControlProjectOverride</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqControlProjectOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqHourProjectOverride name="ReqHourProjectOverride">ReqHourProjectOverride</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqHourProjectOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqHourValidate name="ReqHourValidate">ReqHourValidate</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqHourValidate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqItemProjectOverride name="ReqItemProjectOverride">ReqItemProjectOverride</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqItemProjectOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqItemValidate name="ReqItemValidate">ReqItemValidate</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqItemValidate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SchedDefaultCalendar name="SchedDefaultCalendar">SchedDefaultCalendar</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDefaultCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableHourScheduling name="EnableHourScheduling">EnableHourScheduling</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableHourScheduling attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableSchedulingWorkflow name="EnableSchedulingWorkflow">EnableSchedulingWorkflow</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSchedulingWorkflow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/PSAParameters (this entity)  

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

### <a href=#Relationship_ProjJournalNameRelationshipId name="Relationship_ProjJournalNameRelationshipId">Relationship_ProjJournalNameRelationshipId</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjJournalName.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalName.cdm.json/ProjJournalName</a></td><td><a href="../Group/ProjJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkCalendarTableRelationshipId name="Relationship_WorkCalendarTableRelationshipId">Relationship_WorkCalendarTableRelationshipId</a>

First included in: Parameter/PSAParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductionControl/Group/WorkCalendarTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/WorkCalendarTable.cdm.json/WorkCalendarTable</a></td><td><a href="../../../SupplyChain/ProductionControl/Group/WorkCalendarTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/PSAParameters (this entity)  

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
