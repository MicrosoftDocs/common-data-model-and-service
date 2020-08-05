---
title: BusinessEventsAzureEndpoint in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Business Events Azure endpoint in Miscellaneous(BusinessEventsAzureEndpoint)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsAzureEndpoint.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsAzureEndpoint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Business events endpoint</td></tr><tr><td>en</td><td>Business Events Azure endpoint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[Name](#Name)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[Type](#Type)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[ProducerConsumerType](#ProducerConsumerType)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[KeyVaultDnsName](#KeyVaultDnsName)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[KeyVaultSecretName](#KeyVaultSecretName)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[AzureAppId](#AzureAppId)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|
|[AzureAppSecret](#AzureAppSecret)||<a href="BusinessEventsAzureEndpoint.md" target="_blank">Miscellaneous/BusinessEventsAzureEndpoint</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsAzureEndpoint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

</details>

### <a href=#Type name="Type">Type</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProducerConsumerType name="ProducerConsumerType">ProducerConsumerType</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProducerConsumerType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#KeyVaultDnsName name="KeyVaultDnsName">KeyVaultDnsName</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultDnsName attribute are listed below.</summary>

</details>

### <a href=#KeyVaultSecretName name="KeyVaultSecretName">KeyVaultSecretName</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyVaultSecretName attribute are listed below.</summary>

</details>

### <a href=#AzureAppId name="AzureAppId">AzureAppId</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureAppId attribute are listed below.</summary>

</details>

### <a href=#AzureAppSecret name="AzureAppSecret">AzureAppSecret</a>

First included in: Miscellaneous/BusinessEventsAzureEndpoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureAppSecret attribute are listed below.</summary>

</details>
