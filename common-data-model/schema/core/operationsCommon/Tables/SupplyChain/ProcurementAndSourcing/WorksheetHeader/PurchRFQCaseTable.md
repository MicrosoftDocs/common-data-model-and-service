---
title: PurchRFQCaseTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Request for quotation cases

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQCaseTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQCaseTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation cases</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AddressRefRecId](#AddressRefRecId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AddressRefTableId](#AddressRefTableId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AllowAlternates](#AllowAlternates)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AllowBidByInvitationOnly](#AllowBidByInvitationOnly)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[BidType](#BidType)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DeliveryDate](#DeliveryDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DlvMode](#DlvMode)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DlvTerm](#DlvTerm)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ExpiryDateTime](#ExpiryDateTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[InclTax](#InclTax)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[InventLocationId](#InventLocationId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[InventSiteId](#InventSiteId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[isAmended](#isAmended)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[IsSealed](#IsSealed)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ItemBuyerGroup](#ItemBuyerGroup)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[LanguageId](#LanguageId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Name](#Name)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Payment](#Payment)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[PaymMode](#PaymMode)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ProjId](#ProjId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Requester](#Requester)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RequestingDepartment](#RequestingDepartment)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ResponsibleWorkerId](#ResponsibleWorkerId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQCaseId](#RFQCaseId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQCloseVisibilityType](#RFQCloseVisibilityType)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderCurrencyCode](#RFQReplyHeaderCurrencyCode)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderDeliveryDate](#RFQReplyHeaderDeliveryDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderDlvTerm](#RFQReplyHeaderDlvTerm)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderDocumentation](#RFQReplyHeaderDocumentation)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderEndDiscPct](#RFQReplyHeaderEndDiscPct)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderMarkup](#RFQReplyHeaderMarkup)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderPayment](#RFQReplyHeaderPayment)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderValidFromDate](#RFQReplyHeaderValidFromDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderValidToDate](#RFQReplyHeaderValidToDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyHeaderVendRef](#RFQReplyHeaderVendRef)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineDeliveryDate](#RFQReplyLineDeliveryDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineDocumentation](#RFQReplyLineDocumentation)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineExternalItemFreeTxt](#RFQReplyLineExternalItemFreeTxt)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineExternalItemId](#RFQReplyLineExternalItemId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineLeadTime](#RFQReplyLineLeadTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineLineDisc](#RFQReplyLineLineDisc)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineMarkup](#RFQReplyLineMarkup)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineMultiLnDisc](#RFQReplyLineMultiLnDisc)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineMultiLnPercent](#RFQReplyLineMultiLnPercent)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLinePercent](#RFQReplyLinePercent)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLinePriceUnit](#RFQReplyLinePriceUnit)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineQuantity](#RFQReplyLineQuantity)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineUnit](#RFQReplyLineUnit)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineValidFromDate](#RFQReplyLineValidFromDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineValidToDate](#RFQReplyLineValidToDate)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQReplyLineWorkingdays](#RFQReplyLineWorkingdays)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQType](#RFQType)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[RFQVendNum](#RFQVendNum)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLineLineDiscEP](#ShowRFQReplyLineLineDiscEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLineMarkupEP](#ShowRFQReplyLineMarkupEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLineMultiLnDiscEP](#ShowRFQReplyLineMultiLnDiscEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLineMultiLnPercentEP](#ShowRFQReplyLineMultiLnPercentEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLinePercentEP](#ShowRFQReplyLinePercentEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ShowRFQReplyLinePriceUnitEP](#ShowRFQReplyLinePriceUnitEP)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[SitesEmailId](#SitesEmailId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[SitesSvcPage](#SitesSvcPage)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[SolicitationType](#SolicitationType)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[StatusHigh](#StatusHigh)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[StatusLow](#StatusLow)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[UnsealedDateTime](#UnsealedDateTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ValidityDateEnd](#ValidityDateEnd)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[ValidityDateStart](#ValidityDateStart)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CancellationReason](#CancellationReason)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CanceledDateTime](#CanceledDateTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CanceledPurchReqId](#CanceledPurchReqId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[AgreementClassification](#AgreementClassification)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CancelledDateTime](#CancelledDateTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[CancelledPurchReqId](#CancelledPurchReqId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[IsVendorQuestionEnabled](#IsVendorQuestionEnabled)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[VendorQuestionCutoffDateTime](#VendorQuestionCutoffDateTime)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[PSNRFQDescription](#PSNRFQDescription)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_AccountingDistributionTemplateRelationshipId](#Relationship_AccountingDistributionTemplateRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_DeliveryPostalAddressRelationshipId](#Relationship_DeliveryPostalAddressRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_DlvModeRelationshipId](#Relationship_DlvModeRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_DlvTermRelationshipId](#Relationship_DlvTermRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_InventBuyerGroupRelationshipId](#Relationship_InventBuyerGroupRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_NumberSequenceGroupRelationshipId](#Relationship_NumberSequenceGroupRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_PurchRFQCloseVisibilityTypeRelationshipId](#Relationship_PurchRFQCloseVisibilityTypeRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_PurchRFQSolicitationTypeRelationshipId](#Relationship_PurchRFQSolicitationTypeRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_SysEmailTableRelationshipId](#Relationship_SysEmailTableRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_VendPaymModeTableRelationshipId](#Relationship_VendPaymModeTableRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_PurchReqTableRelationshipId](#Relationship_PurchReqTableRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_PurchRFQAgreementClassificationRelationshipId](#Relationship_PurchRFQAgreementClassificationRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQCaseTable.md" target="_blank">WorksheetHeader/PurchRFQCaseTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQCaseTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressRefRecId name="AddressRefRecId">AddressRefRecId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressRefTableId name="AddressRefTableId">AddressRefTableId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowAlternates name="AllowAlternates">AllowAlternates</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAlternates attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowBidByInvitationOnly name="AllowBidByInvitationOnly">AllowBidByInvitationOnly</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBidByInvitationOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BidType name="BidType">BidType</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BidType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DlvMode name="DlvMode">DlvMode</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#ExpiryDateTime name="ExpiryDateTime">ExpiryDateTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#isAmended name="isAmended">isAmended</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isAmended attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSealed name="IsSealed">IsSealed</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSealed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemBuyerGroup name="ItemBuyerGroup">ItemBuyerGroup</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBuyerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Requester name="Requester">Requester</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Requester attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RequestingDepartment name="RequestingDepartment">RequestingDepartment</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingDepartment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsibleWorkerId name="ResponsibleWorkerId">ResponsibleWorkerId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibleWorkerId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RFQCaseId name="RFQCaseId">RFQCaseId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCloseVisibilityType name="RFQCloseVisibilityType">RFQCloseVisibilityType</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCloseVisibilityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RFQReplyHeaderCurrencyCode name="RFQReplyHeaderCurrencyCode">RFQReplyHeaderCurrencyCode</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderCurrencyCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderDeliveryDate name="RFQReplyHeaderDeliveryDate">RFQReplyHeaderDeliveryDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderDeliveryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderDlvTerm name="RFQReplyHeaderDlvTerm">RFQReplyHeaderDlvTerm</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderDlvTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderDocumentation name="RFQReplyHeaderDocumentation">RFQReplyHeaderDocumentation</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderDocumentation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderEndDiscPct name="RFQReplyHeaderEndDiscPct">RFQReplyHeaderEndDiscPct</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderEndDiscPct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderMarkup name="RFQReplyHeaderMarkup">RFQReplyHeaderMarkup</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderPayment name="RFQReplyHeaderPayment">RFQReplyHeaderPayment</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderValidFromDate name="RFQReplyHeaderValidFromDate">RFQReplyHeaderValidFromDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderValidFromDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderValidToDate name="RFQReplyHeaderValidToDate">RFQReplyHeaderValidToDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderValidToDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyHeaderVendRef name="RFQReplyHeaderVendRef">RFQReplyHeaderVendRef</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyHeaderVendRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineDeliveryDate name="RFQReplyLineDeliveryDate">RFQReplyLineDeliveryDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineDeliveryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineDocumentation name="RFQReplyLineDocumentation">RFQReplyLineDocumentation</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineDocumentation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineExternalItemFreeTxt name="RFQReplyLineExternalItemFreeTxt">RFQReplyLineExternalItemFreeTxt</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineExternalItemFreeTxt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineExternalItemId name="RFQReplyLineExternalItemId">RFQReplyLineExternalItemId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineExternalItemId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineLeadTime name="RFQReplyLineLeadTime">RFQReplyLineLeadTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineLeadTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineLineDisc name="RFQReplyLineLineDisc">RFQReplyLineLineDisc</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineLineDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineMarkup name="RFQReplyLineMarkup">RFQReplyLineMarkup</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineMultiLnDisc name="RFQReplyLineMultiLnDisc">RFQReplyLineMultiLnDisc</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineMultiLnDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineMultiLnPercent name="RFQReplyLineMultiLnPercent">RFQReplyLineMultiLnPercent</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineMultiLnPercent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLinePercent name="RFQReplyLinePercent">RFQReplyLinePercent</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLinePercent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLinePriceUnit name="RFQReplyLinePriceUnit">RFQReplyLinePriceUnit</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLinePriceUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineQuantity name="RFQReplyLineQuantity">RFQReplyLineQuantity</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineUnit name="RFQReplyLineUnit">RFQReplyLineUnit</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineValidFromDate name="RFQReplyLineValidFromDate">RFQReplyLineValidFromDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineValidFromDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineValidToDate name="RFQReplyLineValidToDate">RFQReplyLineValidToDate</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineValidToDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQReplyLineWorkingdays name="RFQReplyLineWorkingdays">RFQReplyLineWorkingdays</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyLineWorkingdays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQType name="RFQType">RFQType</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQVendNum name="RFQVendNum">RFQVendNum</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQVendNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineLineDiscEP name="ShowRFQReplyLineLineDiscEP">ShowRFQReplyLineLineDiscEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineLineDiscEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMarkupEP name="ShowRFQReplyLineMarkupEP">ShowRFQReplyLineMarkupEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMarkupEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMultiLnDiscEP name="ShowRFQReplyLineMultiLnDiscEP">ShowRFQReplyLineMultiLnDiscEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMultiLnDiscEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLineMultiLnPercentEP name="ShowRFQReplyLineMultiLnPercentEP">ShowRFQReplyLineMultiLnPercentEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLineMultiLnPercentEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLinePercentEP name="ShowRFQReplyLinePercentEP">ShowRFQReplyLinePercentEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLinePercentEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowRFQReplyLinePriceUnitEP name="ShowRFQReplyLinePriceUnitEP">ShowRFQReplyLinePriceUnitEP</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowRFQReplyLinePriceUnitEP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SitesEmailId name="SitesEmailId">SitesEmailId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SitesEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SitesSvcPage name="SitesSvcPage">SitesSvcPage</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SitesSvcPage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SolicitationType name="SolicitationType">SolicitationType</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SolicitationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StatusHigh name="StatusHigh">StatusHigh</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Highest status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusHigh attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Highest status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StatusLow name="StatusLow">StatusLow</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lowest status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusLow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lowest status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UnsealedDateTime name="UnsealedDateTime">UnsealedDateTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnsealedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ValidityDateEnd name="ValidityDateEnd">ValidityDateEnd</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidityDateEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidityDateStart name="ValidityDateStart">ValidityDateStart</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidityDateStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CancellationReason name="CancellationReason">CancellationReason</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The reason for canceling the RFQ</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancellationReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The reason for canceling the RFQ</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanceledDateTime name="CanceledDateTime">CanceledDateTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cancelation date and time</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanceledDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cancelation date and time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CanceledPurchReqId name="CanceledPurchReqId">CanceledPurchReqId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanceledPurchReqId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementClassification name="AgreementClassification">AgreementClassification</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase agreement classification</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CancelledDateTime name="CancelledDateTime">CancelledDateTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelledDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CancelledPurchReqId name="CancelledPurchReqId">CancelledPurchReqId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelledPurchReqId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorQuestionEnabled name="IsVendorQuestionEnabled">IsVendorQuestionEnabled</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorQuestionEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorQuestionCutoffDateTime name="VendorQuestionCutoffDateTime">VendorQuestionCutoffDateTime</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorQuestionCutoffDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PSNRFQDescription name="PSNRFQDescription">PSNRFQDescription</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNRFQDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_AccountingDistributionTemplateRelationshipId name="Relationship_AccountingDistributionTemplateRelationshipId">Relationship_AccountingDistributionTemplateRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingDistributionTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/AccountingDistributionTemplate.cdm.json/AccountingDistributionTemplate</a></td><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryPostalAddressRelationshipId name="Relationship_DeliveryPostalAddressRelationshipId">Relationship_DeliveryPostalAddressRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryPostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvModeRelationshipId name="Relationship_DlvModeRelationshipId">Relationship_DlvModeRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_InventBuyerGroupRelationshipId name="Relationship_InventBuyerGroupRelationshipId">Relationship_InventBuyerGroupRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventBuyerGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventBuyerGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventBuyerGroup.cdm.json/InventBuyerGroup</a></td><td><a href="../../Inventory/Group/InventBuyerGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../../Inventory/Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceGroupRelationshipId name="Relationship_NumberSequenceGroupRelationshipId">Relationship_NumberSequenceGroupRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceGroup.cdm.json/NumberSequenceGroup</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQCloseVisibilityTypeRelationshipId name="Relationship_PurchRFQCloseVisibilityTypeRelationshipId">Relationship_PurchRFQCloseVisibilityTypeRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_PurchRFQSolicitationTypeRelationshipId name="Relationship_PurchRFQSolicitationTypeRelationshipId">Relationship_PurchRFQSolicitationTypeRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_SysEmailTableRelationshipId name="Relationship_SysEmailTableRelationshipId">Relationship_SysEmailTableRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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

### <a href=#Relationship_VendPaymModeTableRelationshipId name="Relationship_VendPaymModeTableRelationshipId">Relationship_VendPaymModeTableRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeTable.cdm.json/VendPaymModeTable</a></td><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReqTableRelationshipId name="Relationship_PurchReqTableRelationshipId">Relationship_PurchReqTableRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchReqTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchReqTable.cdm.json/PurchReqTable</a></td><td><a href="PurchReqTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQAgreementClassificationRelationshipId name="Relationship_PurchRFQAgreementClassificationRelationshipId">Relationship_PurchRFQAgreementClassificationRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQAgreementClassificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AgreementClassification.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/AgreementClassification.cdm.json/AgreementClassification</a></td><td><a href="../Group/AgreementClassification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/PurchRFQCaseTable (this entity)  

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
