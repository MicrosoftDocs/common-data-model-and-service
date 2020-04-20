---
title: RetailMachine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailMachine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMachine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMachine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[AssignedSites](#AssignedSites)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[DistinguishedName](#DistinguishedName)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[DomainWorkgroup](#DomainWorkgroup)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[FriendlyName](#FriendlyName)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[IPAddresses](#IPAddresses)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[IPSubnets](#IPSubnets)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[IPv6Addresses](#IPv6Addresses)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[IPv6Prefixes](#IPv6Prefixes)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[IsVirtualMachine](#IsVirtualMachine)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[MACAddresses](#MACAddresses)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[MachineName](#MachineName)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[OSNameAndVersion](#OSNameAndVersion)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[ResourceNames](#ResourceNames)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[UniqueIdentifier](#UniqueIdentifier)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[VirtualMachineHostName](#VirtualMachineHostName)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[LogShareId](#LogShareId)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|
|[Relationship_RetailDeploymentLogShareRelationshipId](#Relationship_RetailDeploymentLogShareRelationshipId)||<a href="RetailMachine.md" target="_blank">Miscellaneous/RetailMachine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMachine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssignedSites name="AssignedSites">AssignedSites</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignedSites attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DistinguishedName name="DistinguishedName">DistinguishedName</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistinguishedName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DomainWorkgroup name="DomainWorkgroup">DomainWorkgroup</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomainWorkgroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FriendlyName name="FriendlyName">FriendlyName</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FriendlyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IPAddresses name="IPAddresses">IPAddresses</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPAddresses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IPSubnets name="IPSubnets">IPSubnets</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPSubnets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IPv6Addresses name="IPv6Addresses">IPv6Addresses</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPv6Addresses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IPv6Prefixes name="IPv6Prefixes">IPv6Prefixes</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IPv6Prefixes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVirtualMachine name="IsVirtualMachine">IsVirtualMachine</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVirtualMachine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MACAddresses name="MACAddresses">MACAddresses</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MACAddresses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MachineName name="MachineName">MachineName</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MachineName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OSNameAndVersion name="OSNameAndVersion">OSNameAndVersion</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OSNameAndVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceNames name="ResourceNames">ResourceNames</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UniqueIdentifier name="UniqueIdentifier">UniqueIdentifier</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VirtualMachineHostName name="VirtualMachineHostName">VirtualMachineHostName</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VirtualMachineHostName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogShareId name="LogShareId">LogShareId</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogShareId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailDeploymentLogShareRelationshipId name="Relationship_RetailDeploymentLogShareRelationshipId">Relationship_RetailDeploymentLogShareRelationshipId</a>

First included in: Miscellaneous/RetailMachine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentLogShareRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentLogShares.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentLogShares.cdm.json/RetailDeploymentLogShares</a></td><td><a href="RetailDeploymentLogShares.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
