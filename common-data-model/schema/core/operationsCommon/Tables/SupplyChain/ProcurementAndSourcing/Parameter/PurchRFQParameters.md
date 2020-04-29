---
title: PurchRFQParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Request for quotation parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchRFQParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DaysOffset](#DaysOffset)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DefaultSolicitationType](#DefaultSolicitationType)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DlvMode](#DlvMode)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DlvTerm](#DlvTerm)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ExpDateCalendarDays](#ExpDateCalendarDays)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Key](#Key)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Payment](#Payment)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[PriceDiscJournalName](#PriceDiscJournalName)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[PurchRFQType](#PurchRFQType)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderCurrencyCode](#ReplyHeaderCurrencyCode)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderDeliveryDate](#ReplyHeaderDeliveryDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderDlvTerm](#ReplyHeaderDlvTerm)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderDocumentation](#ReplyHeaderDocumentation)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderEndDiscPct](#ReplyHeaderEndDiscPct)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderMarkup](#ReplyHeaderMarkup)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderPayment](#ReplyHeaderPayment)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderValidFromDate](#ReplyHeaderValidFromDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderValidToDate](#ReplyHeaderValidToDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyHeaderVendRef](#ReplyHeaderVendRef)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineDeliveryDate](#ReplyLineDeliveryDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineDocumentation](#ReplyLineDocumentation)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineExternalItemFreeTxt](#ReplyLineExternalItemFreeTxt)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineExternalItemId](#ReplyLineExternalItemId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineLeadTime](#ReplyLineLeadTime)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineLineDisc](#ReplyLineLineDisc)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineMarkup](#ReplyLineMarkup)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineMultiLnDisc](#ReplyLineMultiLnDisc)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineMultiLnPercent](#ReplyLineMultiLnPercent)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLinePercent](#ReplyLinePercent)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLinePriceUnit](#ReplyLinePriceUnit)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineQuantity](#ReplyLineQuantity)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineUnit](#ReplyLineUnit)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineValidFromDate](#ReplyLineValidFromDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineValidToDate](#ReplyLineValidToDate)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ReplyLineWorkingdays](#ReplyLineWorkingdays)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLineLineDiscEP](#ShowRFQReplyLineLineDiscEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLineMarkupEP](#ShowRFQReplyLineMarkupEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLineMultiLnDiscEP](#ShowRFQReplyLineMultiLnDiscEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLineMultiLnPercentEP](#ShowRFQReplyLineMultiLnPercentEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLinePercentEP](#ShowRFQReplyLinePercentEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[ShowRFQReplyLinePriceUnitEP](#ShowRFQReplyLinePriceUnitEP)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[TimeOffset](#TimeOffset)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DefaultRFQCloseVisibilityType](#DefaultRFQCloseVisibilityType)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[LockRFQOnSend](#LockRFQOnSend)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[SysEmailTable](#SysEmailTable)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[CancelSysEmailTable](#CancelSysEmailTable)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[IsBidEditByProcurementAgentEnabled](#IsBidEditByProcurementAgentEnabled)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DefaultBidType](#DefaultBidType)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[SealedBidEncryptionKeyExpirationDayOffset](#SealedBidEncryptionKeyExpirationDayOffset)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[IsVendorQuestionEnabled](#IsVendorQuestionEnabled)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[IsDefaultedToDirectVendorResponse](#IsDefaultedToDirectVendorResponse)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[PSNPurchRFQShowDescription](#PSNPurchRFQShowDescription)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[PSNIsEnforcedAlternateItemNameDifferent](#PSNIsEnforcedAlternateItemNameDifferent)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[PSNPurchRFQLockEdit](#PSNPurchRFQLockEdit)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_DlvModeRelationshipId](#Relationship_DlvModeRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_DlvTermRelationshipId](#Relationship_DlvTermRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_PriceDiscAdmNameRelationshipId](#Relationship_PriceDiscAdmNameRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_PurchRFQSolicitationTypeRelationshipId](#Relationship_PurchRFQSolicitationTypeRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_PurchRFQCloseVisibilityTypeRelationshipId](#Relationship_PurchRFQCloseVisibilityTypeRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_SysEmailTableRelationshipId](#Relationship_SysEmailTableRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_CancelSysEmailTableRelationshipId](#Relationship_CancelSysEmailTableRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQParameters.md" target="_blank">Parameter/PurchRFQParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DaysOffset name="DaysOffset">DaysOffset</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days offset</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DefaultSolicitationType name="DefaultSolicitationType">DefaultSolicitationType</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSolicitationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DlvMode name="DlvMode">DlvMode</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvTerm name="DlvTerm">DlvTerm</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpDateCalendarDays name="ExpDateCalendarDays">ExpDateCalendarDays</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpDateCalendarDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceDiscJournalName name="PriceDiscJournalName">PriceDiscJournalName</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchRFQType name="PurchRFQType">PurchRFQType</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderCurrencyCode name="ReplyHeaderCurrencyCode">ReplyHeaderCurrencyCode</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderCurrencyCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderDeliveryDate name="ReplyHeaderDeliveryDate">ReplyHeaderDeliveryDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderDeliveryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderDlvTerm name="ReplyHeaderDlvTerm">ReplyHeaderDlvTerm</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderDlvTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderDocumentation name="ReplyHeaderDocumentation">ReplyHeaderDocumentation</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderDocumentation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderEndDiscPct name="ReplyHeaderEndDiscPct">ReplyHeaderEndDiscPct</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderEndDiscPct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderMarkup name="ReplyHeaderMarkup">ReplyHeaderMarkup</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderPayment name="ReplyHeaderPayment">ReplyHeaderPayment</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderValidFromDate name="ReplyHeaderValidFromDate">ReplyHeaderValidFromDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderValidFromDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderValidToDate name="ReplyHeaderValidToDate">ReplyHeaderValidToDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderValidToDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyHeaderVendRef name="ReplyHeaderVendRef">ReplyHeaderVendRef</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyHeaderVendRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineDeliveryDate name="ReplyLineDeliveryDate">ReplyLineDeliveryDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineDeliveryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineDocumentation name="ReplyLineDocumentation">ReplyLineDocumentation</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineDocumentation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineExternalItemFreeTxt name="ReplyLineExternalItemFreeTxt">ReplyLineExternalItemFreeTxt</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineExternalItemFreeTxt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineExternalItemId name="ReplyLineExternalItemId">ReplyLineExternalItemId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineExternalItemId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineLeadTime name="ReplyLineLeadTime">ReplyLineLeadTime</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineLeadTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineLineDisc name="ReplyLineLineDisc">ReplyLineLineDisc</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineLineDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineMarkup name="ReplyLineMarkup">ReplyLineMarkup</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineMultiLnDisc name="ReplyLineMultiLnDisc">ReplyLineMultiLnDisc</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineMultiLnDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineMultiLnPercent name="ReplyLineMultiLnPercent">ReplyLineMultiLnPercent</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineMultiLnPercent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLinePercent name="ReplyLinePercent">ReplyLinePercent</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLinePercent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLinePriceUnit name="ReplyLinePriceUnit">ReplyLinePriceUnit</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLinePriceUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineQuantity name="ReplyLineQuantity">ReplyLineQuantity</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineUnit name="ReplyLineUnit">ReplyLineUnit</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineValidFromDate name="ReplyLineValidFromDate">ReplyLineValidFromDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineValidFromDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineValidToDate name="ReplyLineValidToDate">ReplyLineValidToDate</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineValidToDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplyLineWorkingdays name="ReplyLineWorkingdays">ReplyLineWorkingdays</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineWorkingdays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineLineDiscEP name="ShowRFQReplyLineLineDiscEP">ShowRFQReplyLineLineDiscEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineLineDiscEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMarkupEP name="ShowRFQReplyLineMarkupEP">ShowRFQReplyLineMarkupEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMarkupEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMultiLnDiscEP name="ShowRFQReplyLineMultiLnDiscEP">ShowRFQReplyLineMultiLnDiscEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMultiLnDiscEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMultiLnPercentEP name="ShowRFQReplyLineMultiLnPercentEP">ShowRFQReplyLineMultiLnPercentEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMultiLnPercentEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLinePercentEP name="ShowRFQReplyLinePercentEP">ShowRFQReplyLinePercentEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLinePercentEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLinePriceUnitEP name="ShowRFQReplyLinePriceUnitEP">ShowRFQReplyLinePriceUnitEP</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLinePriceUnitEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TimeOffset name="TimeOffset">TimeOffset</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiration Time</td></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeOffset attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expiration Time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#DefaultRFQCloseVisibilityType name="DefaultRFQCloseVisibilityType">DefaultRFQCloseVisibilityType</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQCloseVisibilityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LockRFQOnSend name="LockRFQOnSend">LockRFQOnSend</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LockRFQOnSend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SysEmailTable name="SysEmailTable">SysEmailTable</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email template for notification of amendments</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SysEmailTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email template for notification of amendments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancelSysEmailTable name="CancelSysEmailTable">CancelSysEmailTable</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email template for notification of canceled RFQ</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelSysEmailTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email template for notification of canceled RFQ</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBidEditByProcurementAgentEnabled name="IsBidEditByProcurementAgentEnabled">IsBidEditByProcurementAgentEnabled</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBidEditByProcurementAgentEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultBidType name="DefaultBidType">DefaultBidType</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBidType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SealedBidEncryptionKeyExpirationDayOffset name="SealedBidEncryptionKeyExpirationDayOffset">SealedBidEncryptionKeyExpirationDayOffset</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encryption key expiration day offset</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SealedBidEncryptionKeyExpirationDayOffset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Encryption key expiration day offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsVendorQuestionEnabled name="IsVendorQuestionEnabled">IsVendorQuestionEnabled</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorQuestionEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDefaultedToDirectVendorResponse name="IsDefaultedToDirectVendorResponse">IsDefaultedToDirectVendorResponse</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultedToDirectVendorResponse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNPurchRFQShowDescription name="PSNPurchRFQShowDescription">PSNPurchRFQShowDescription</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPurchRFQShowDescription attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNIsEnforcedAlternateItemNameDifferent name="PSNIsEnforcedAlternateItemNameDifferent">PSNIsEnforcedAlternateItemNameDifferent</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNIsEnforcedAlternateItemNameDifferent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNPurchRFQLockEdit name="PSNPurchRFQLockEdit">PSNPurchRFQLockEdit</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNPurchRFQLockEdit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

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

### <a href=#Relationship_DlvModeRelationshipId name="Relationship_DlvModeRelationshipId">Relationship_DlvModeRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvMode.cdm.json/DlvMode</a></td><td><a href="../../SalesAndMarketing/Group/DlvMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvTermRelationshipId name="Relationship_DlvTermRelationshipId">Relationship_DlvTermRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvTerm.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvTerm.cdm.json/DlvTerm</a></td><td><a href="../../SalesAndMarketing/Group/DlvTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../../Finance/Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PriceDiscAdmNameRelationshipId name="Relationship_PriceDiscAdmNameRelationshipId">Relationship_PriceDiscAdmNameRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscAdmNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/PriceDiscAdmName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscAdmName.cdm.json/PriceDiscAdmName</a></td><td><a href="../../SalesAndMarketing/Group/PriceDiscAdmName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQSolicitationTypeRelationshipId name="Relationship_PurchRFQSolicitationTypeRelationshipId">Relationship_PurchRFQSolicitationTypeRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQSolicitationTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/PurchRFQSolicitationType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchRFQSolicitationType.cdm.json/PurchRFQSolicitationType</a></td><td><a href="../Miscellaneous/PurchRFQSolicitationType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQCloseVisibilityTypeRelationshipId name="Relationship_PurchRFQCloseVisibilityTypeRelationshipId">Relationship_PurchRFQCloseVisibilityTypeRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQCloseVisibilityTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/PurchRFQCloseVisibilityType_PSN.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchRFQCloseVisibilityType_PSN.cdm.json/PurchRFQCloseVisibilityType_PSN</a></td><td><a href="../Miscellaneous/PurchRFQCloseVisibilityType_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysEmailTableRelationshipId name="Relationship_SysEmailTableRelationshipId">Relationship_SysEmailTableRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysEmailTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CancelSysEmailTableRelationshipId name="Relationship_CancelSysEmailTableRelationshipId">Relationship_CancelSysEmailTableRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CancelSysEmailTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/SysEmailTable.cdm.json/SysEmailTable</a></td><td><a href="../../../System/SystemAdministration/Main/SysEmailTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/PurchRFQParameters (this entity)  

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
