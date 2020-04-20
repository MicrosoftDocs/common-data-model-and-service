---
title: UserRequestParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# UserRequestParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Parameter/UserRequestParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UserRequestParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[UserAliasEmailTemplate](#UserAliasEmailTemplate)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[AzureACSNetworkDomain](#AzureACSNetworkDomain)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[CustomerAuthenticationMode](#CustomerAuthenticationMode)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[CustomerNewUserEmailTemplate](#CustomerNewUserEmailTemplate)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[CustomerProviderName](#CustomerProviderName)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[CustomerSelfServiceSiteId](#CustomerSelfServiceSiteId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Key](#Key)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[TemporaryPasswordEmailTemplate](#TemporaryPasswordEmailTemplate)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[UnSolicitedVendorAuthenticationMode](#UnSolicitedVendorAuthenticationMode)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[UseEmailAsUserAlias](#UseEmailAsUserAlias)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[VendorAuthenticationMode](#VendorAuthenticationMode)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[VendorNewUserEmailTemplate](#VendorNewUserEmailTemplate)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[VendorProviderName](#VendorProviderName)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[VendorSelfServiceSiteId](#VendorSelfServiceSiteId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[PublicPortalSiteId](#PublicPortalSiteId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[UserACSAuthenticationEmailTemplate](#UserACSAuthenticationEmailTemplate)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[UserACSAuthenticationURLExpiryDays](#UserACSAuthenticationURLExpiryDays)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_CustomerNewUserTemplateRelationshipId](#Relationship_CustomerNewUserTemplateRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_CustomerSelfServiceWebsiteRelationshipId](#Relationship_CustomerSelfServiceWebsiteRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_TemporaryPasswordTemplateRelationshipId](#Relationship_TemporaryPasswordTemplateRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_UserAliasTemplateRelationshipId](#Relationship_UserAliasTemplateRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_VendorNewUserTemplateRelationshipId](#Relationship_VendorNewUserTemplateRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_VendorSelfServiceWebsiteRelationshipId](#Relationship_VendorSelfServiceWebsiteRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_PublicPortalWebsiteRelationshipId](#Relationship_PublicPortalWebsiteRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|
|[Relationship_UserRequestACSAuthenticationTemplateRelationshipId](#Relationship_UserRequestACSAuthenticationTemplateRelationshipId)||<a href="UserRequestParameters.md" target="_blank">Parameter/UserRequestParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UserRequestParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UserAliasEmailTemplate name="UserAliasEmailTemplate">UserAliasEmailTemplate</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserAliasEmailTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureACSNetworkDomain name="AzureACSNetworkDomain">AzureACSNetworkDomain</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureACSNetworkDomain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAuthenticationMode name="CustomerAuthenticationMode">CustomerAuthenticationMode</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAuthenticationMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomerNewUserEmailTemplate name="CustomerNewUserEmailTemplate">CustomerNewUserEmailTemplate</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerNewUserEmailTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerProviderName name="CustomerProviderName">CustomerProviderName</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerSelfServiceSiteId name="CustomerSelfServiceSiteId">CustomerSelfServiceSiteId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerSelfServiceSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TemporaryPasswordEmailTemplate name="TemporaryPasswordEmailTemplate">TemporaryPasswordEmailTemplate</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemporaryPasswordEmailTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnSolicitedVendorAuthenticationMode name="UnSolicitedVendorAuthenticationMode">UnSolicitedVendorAuthenticationMode</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnSolicitedVendorAuthenticationMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseEmailAsUserAlias name="UseEmailAsUserAlias">UseEmailAsUserAlias</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseEmailAsUserAlias attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorAuthenticationMode name="VendorAuthenticationMode">VendorAuthenticationMode</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAuthenticationMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorNewUserEmailTemplate name="VendorNewUserEmailTemplate">VendorNewUserEmailTemplate</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorNewUserEmailTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorProviderName name="VendorProviderName">VendorProviderName</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorSelfServiceSiteId name="VendorSelfServiceSiteId">VendorSelfServiceSiteId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorSelfServiceSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PublicPortalSiteId name="PublicPortalSiteId">PublicPortalSiteId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PublicPortalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserACSAuthenticationEmailTemplate name="UserACSAuthenticationEmailTemplate">UserACSAuthenticationEmailTemplate</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserACSAuthenticationEmailTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserACSAuthenticationURLExpiryDays name="UserACSAuthenticationURLExpiryDays">UserACSAuthenticationURLExpiryDays</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserACSAuthenticationURLExpiryDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CustomerNewUserTemplateRelationshipId name="Relationship_CustomerNewUserTemplateRelationshipId">Relationship_CustomerNewUserTemplateRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerNewUserTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailSystemTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailSystemTable.cdm.json/SysEmailSystemTable</a></td><td><a href="../Main/SysEmailSystemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomerSelfServiceWebsiteRelationshipId name="Relationship_CustomerSelfServiceWebsiteRelationshipId">Relationship_CustomerSelfServiceWebsiteRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerSelfServiceWebsiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EPWebSiteParameters.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/EPWebSiteParameters.cdm.json/EPWebSiteParameters</a></td><td><a href="../Group/EPWebSiteParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TemporaryPasswordTemplateRelationshipId name="Relationship_TemporaryPasswordTemplateRelationshipId">Relationship_TemporaryPasswordTemplateRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TemporaryPasswordTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailSystemTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailSystemTable.cdm.json/SysEmailSystemTable</a></td><td><a href="../Main/SysEmailSystemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UserAliasTemplateRelationshipId name="Relationship_UserAliasTemplateRelationshipId">Relationship_UserAliasTemplateRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UserAliasTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailSystemTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailSystemTable.cdm.json/SysEmailSystemTable</a></td><td><a href="../Main/SysEmailSystemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorNewUserTemplateRelationshipId name="Relationship_VendorNewUserTemplateRelationshipId">Relationship_VendorNewUserTemplateRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorNewUserTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailSystemTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailSystemTable.cdm.json/SysEmailSystemTable</a></td><td><a href="../Main/SysEmailSystemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorSelfServiceWebsiteRelationshipId name="Relationship_VendorSelfServiceWebsiteRelationshipId">Relationship_VendorSelfServiceWebsiteRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorSelfServiceWebsiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EPWebSiteParameters.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/EPWebSiteParameters.cdm.json/EPWebSiteParameters</a></td><td><a href="../Group/EPWebSiteParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PublicPortalWebsiteRelationshipId name="Relationship_PublicPortalWebsiteRelationshipId">Relationship_PublicPortalWebsiteRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PublicPortalWebsiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EPWebSiteParameters.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/EPWebSiteParameters.cdm.json/EPWebSiteParameters</a></td><td><a href="../Group/EPWebSiteParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UserRequestACSAuthenticationTemplateRelationshipId name="Relationship_UserRequestACSAuthenticationTemplateRelationshipId">Relationship_UserRequestACSAuthenticationTemplateRelationshipId</a>

First included in: Parameter/UserRequestParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UserRequestACSAuthenticationTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/SysEmailSystemTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailSystemTable.cdm.json/SysEmailSystemTable</a></td><td><a href="../Main/SysEmailSystemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
