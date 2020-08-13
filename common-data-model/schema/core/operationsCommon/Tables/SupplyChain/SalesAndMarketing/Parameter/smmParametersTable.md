---
title: smmParametersTable in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales and marketing parameters in Parameter(smmParametersTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[smmParametersTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales and marketing parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DocuTypeIdForInEMail](#DocuTypeIdForInEMail)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetActivityPhase](#CampaignTargetActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetActivityType](#CampaignTargetActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementAccountKey_RU](#AgreementAccountKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementClassificationKey_RU](#AgreementClassificationKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementCurrencyKey_RU](#AgreementCurrencyKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementDocumentTitleKey_RU](#AgreementDocumentTitleKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementExtRefKey_RU](#AgreementExtRefKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AgreementYearKey_RU](#AgreementYearKey_RU)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AutoCreateBusinessRelation](#AutoCreateBusinessRelation)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AutoCreateCustomer](#AutoCreateCustomer)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[AutoCreateOpportunity](#AutoCreateOpportunity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[BusRelOpenCustForm](#BusRelOpenCustForm)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[BusRelStatus](#BusRelStatus)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[BusRelTypeId](#BusRelTypeId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CallBackCreateActivity](#CallBackCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignActivityCategory](#CampaignActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignActivityPhaseId](#CampaignActivityPhaseId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignActivityPurpose](#CampaignActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignActivityTypeId](#CampaignActivityTypeId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignCreateActivity](#CampaignCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignGroupId](#CampaignGroupId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignNumOfDaysExpiryDate](#CampaignNumOfDaysExpiryDate)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignStatus](#CampaignStatus)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetActivityCategory](#CampaignTargetActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetActivityPurpose](#CampaignTargetActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetId](#CampaignTargetId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTargetsCreateActivity](#CampaignTargetsCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CampaignTypeId](#CampaignTypeId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CreateOpportunityForProjectQuotation](#CreateOpportunityForProjectQuotation)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CreateOpportunityForSalesQuotation](#CreateOpportunityForSalesQuotation)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[CustGroup](#CustGroup)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DefaultUserId](#DefaultUserId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DocuAgeLimitForDisplay](#DocuAgeLimitForDisplay)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DocuTypeIdForFiles](#DocuTypeIdForFiles)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DocuTypeIdForOutEMail](#DocuTypeIdForOutEMail)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[EmailMemberCopyType](#EmailMemberCopyType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[FollowupCreateActivity](#FollowupCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[key](#key)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LanguageId](#LanguageId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogActivities](#LogActivities)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogBusRel](#LogBusRel)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogCampaignTable](#LogCampaignTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogCaseDetail](#LogCaseDetail)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogContactPerson](#LogContactPerson)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogCustTable](#LogCustTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogCustTrans](#LogCustTrans)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogDelete](#LogDelete)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogDocuRef](#LogDocuRef)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogInsert](#LogInsert)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogLeadTable](#LogLeadTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogMailings](#LogMailings)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogOpportunity](#LogOpportunity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogQuotationTable](#LogQuotationTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogSalesTable](#LogSalesTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogTMCallListTable](#LogTMCallListTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogUpdate](#LogUpdate)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogVendTable](#LogVendTable)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[LogVendTrans](#LogVendTrans)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MailingfileDirectory](#MailingfileDirectory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogReqActivityCategory](#MCRCatalogReqActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogReqActivityCreate](#MCRCatalogReqActivityCreate)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogReqActivityPhase](#MCRCatalogReqActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogReqActivityPurpose](#MCRCatalogReqActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogReqActivityType](#MCRCatalogReqActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogSentActivityCategory](#MCRCatalogSentActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogSentActivityCreate](#MCRCatalogSentActivityCreate)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogSentActivityPhase](#MCRCatalogSentActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogSentActivityPurpose](#MCRCatalogSentActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[MCRCatalogSentActivityType](#MCRCatalogSentActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[NumOfCampaignDaysFollowUpDate](#NumOfCampaignDaysFollowUpDate)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[OpenFromTime](#OpenFromTime)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[OpenToTime](#OpenToTime)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PeriodFrom](#PeriodFrom)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PeriodId](#PeriodId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PeriodTo](#PeriodTo)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PhoneInboundActivityType](#PhoneInboundActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PhoneOutboundActivityType](#PhoneOutboundActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[PhoneOutboundStandardPrefix](#PhoneOutboundStandardPrefix)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[ProjGroupId](#ProjGroupId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[QuotationActivityCategory](#QuotationActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[QuotationActivityPhaseId](#QuotationActivityPhaseId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[QuotationActivityPurpose](#QuotationActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[QuotationActivityTypeId](#QuotationActivityTypeId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[QuotationCreateActivity](#QuotationCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[RunBaseBatchCreateActivity](#RunBaseBatchCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TelemarkeringTargetActivityPhase](#TelemarkeringTargetActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TelemarketingActivityPurpose](#TelemarketingActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TelemarketingTargetActivityCategory](#TelemarketingTargetActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TelemarketingTargetActivityType](#TelemarketingTargetActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TelemarketingTargetsCreateActivity](#TelemarketingTargetsCreateActivity)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMCallBackActivityCategory](#TMCallBackActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMCallBackActivityPhase](#TMCallBackActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMCallBackActivityPurpose](#TMCallBackActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMCallbackActivityType](#TMCallbackActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMFollowUpActivityCategory](#TMFollowUpActivityCategory)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMFollowUpActivityPhase](#TMFollowUpActivityPhase)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMFollowUpActivityPurpose](#TMFollowUpActivityPurpose)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TMFollowUpActivityType](#TMFollowUpActivityType)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[TransLogInterval](#TransLogInterval)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[UpdateOpportunityForProjectQuotation](#UpdateOpportunityForProjectQuotation)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[UpdateOpportunityForSalesQuotation](#UpdateOpportunityForSalesQuotation)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[VendGroupId](#VendGroupId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[WebSiteURL](#WebSiteURL)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[DataAreaId](#DataAreaId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_CustGroupRelationshipId](#Relationship_CustGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_DocuType_FilesRelationshipId](#Relationship_DocuType_FilesRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_DocuType_InEMailRelationshipId](#Relationship_DocuType_InEMailRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_DocuType_OutEMailRelationshipId](#Relationship_DocuType_OutEMailRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_ProjGroupRelationshipId](#Relationship_ProjGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_ProjPeriodTableRelationshipId](#Relationship_ProjPeriodTableRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_smmBusRelStatusGroupRelationshipId](#Relationship_smmBusRelStatusGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_smmBusRelTypeGroupRelationshipId](#Relationship_smmBusRelTypeGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_smmCampaignGroupRelationshipId](#Relationship_smmCampaignGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_smmCampaignTargetTableRelationshipId](#Relationship_smmCampaignTargetTableRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_smmCampaignTypeGroupRelationshipId](#Relationship_smmCampaignTypeGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_VendGroupRelationshipId](#Relationship_VendGroupRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="smmParametersTable.md" target="_blank">Parameter/smmParametersTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[smmParametersTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocuTypeIdForInEMail name="DocuTypeIdForInEMail">DocuTypeIdForInEMail</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document type for incoming email</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeIdForInEMail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document type for incoming email</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignTargetActivityPhase name="CampaignTargetActivityPhase">CampaignTargetActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignTargetActivityType name="CampaignTargetActivityType">CampaignTargetActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementAccountKey_RU name="AgreementAccountKey_RU">AgreementAccountKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer account</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementAccountKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AgreementClassificationKey_RU name="AgreementClassificationKey_RU">AgreementClassificationKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Agreement classification</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementClassificationKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Agreement classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AgreementCurrencyKey_RU name="AgreementCurrencyKey_RU">AgreementCurrencyKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementCurrencyKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AgreementDocumentTitleKey_RU name="AgreementDocumentTitleKey_RU">AgreementDocumentTitleKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document title</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDocumentTitleKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document title</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AgreementExtRefKey_RU name="AgreementExtRefKey_RU">AgreementExtRefKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External reference</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementExtRefKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AgreementYearKey_RU name="AgreementYearKey_RU">AgreementYearKey_RU</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementYearKey_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AutoCreateBusinessRelation name="AutoCreateBusinessRelation">AutoCreateBusinessRelation</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create a prospect</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCreateBusinessRelation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create a prospect</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AutoCreateCustomer name="AutoCreateCustomer">AutoCreateCustomer</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create customer when qualified</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCreateCustomer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create customer when qualified</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AutoCreateOpportunity name="AutoCreateOpportunity">AutoCreateOpportunity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create opportunity when qualified</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCreateOpportunity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create opportunity when qualified</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BusRelOpenCustForm name="BusRelOpenCustForm">BusRelOpenCustForm</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open customer or vendor form on converting a prospect</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusRelOpenCustForm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open customer or vendor form on converting a prospect</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BusRelStatus name="BusRelStatus">BusRelStatus</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusRelStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusRelTypeId name="BusRelTypeId">BusRelTypeId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusRelTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CallBackCreateActivity name="CallBackCreateActivity">CallBackCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CallBackCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignActivityCategory name="CampaignActivityCategory">CampaignActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignActivityPhaseId name="CampaignActivityPhaseId">CampaignActivityPhaseId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignActivityPurpose name="CampaignActivityPurpose">CampaignActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignActivityTypeId name="CampaignActivityTypeId">CampaignActivityTypeId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignCreateActivity name="CampaignCreateActivity">CampaignCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignGroupId name="CampaignGroupId">CampaignGroupId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignNumOfDaysExpiryDate name="CampaignNumOfDaysExpiryDate">CampaignNumOfDaysExpiryDate</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days campaign expires</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignNumOfDaysExpiryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days campaign expires</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CampaignStatus name="CampaignStatus">CampaignStatus</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignTargetActivityCategory name="CampaignTargetActivityCategory">CampaignTargetActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignTargetActivityPurpose name="CampaignTargetActivityPurpose">CampaignTargetActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignTargetId name="CampaignTargetId">CampaignTargetId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignTargetsCreateActivity name="CampaignTargetsCreateActivity">CampaignTargetsCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTargetsCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CampaignTypeId name="CampaignTypeId">CampaignTypeId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateOpportunityForProjectQuotation name="CreateOpportunityForProjectQuotation">CreateOpportunityForProjectQuotation</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create opportunity for project quotations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateOpportunityForProjectQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create opportunity for project quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CreateOpportunityForSalesQuotation name="CreateOpportunityForSalesQuotation">CreateOpportunityForSalesQuotation</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create opportunity for sales quotation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateOpportunityForSalesQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create opportunity for sales quotation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustGroup name="CustGroup">CustGroup</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultUserId name="DefaultUserId">DefaultUserId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuAgeLimitForDisplay name="DocuAgeLimitForDisplay">DocuAgeLimitForDisplay</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuAgeLimitForDisplay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DocuTypeIdForFiles name="DocuTypeIdForFiles">DocuTypeIdForFiles</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document type for other documents</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeIdForFiles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document type for other documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeIdForOutEMail name="DocuTypeIdForOutEMail">DocuTypeIdForOutEMail</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document type for outgoing email</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeIdForOutEMail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document type for outgoing email</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailMemberCopyType name="EmailMemberCopyType">EmailMemberCopyType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailMemberCopyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FollowupCreateActivity name="FollowupCreateActivity">FollowupCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FollowupCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#key name="key">key</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogActivities name="LogActivities">LogActivities</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogActivities attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogBusRel name="LogBusRel">LogBusRel</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogBusRel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogCampaignTable name="LogCampaignTable">LogCampaignTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogCampaignTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogCaseDetail name="LogCaseDetail">LogCaseDetail</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogCaseDetail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogContactPerson name="LogContactPerson">LogContactPerson</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogContactPerson attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogCustTable name="LogCustTable">LogCustTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogCustTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogCustTrans name="LogCustTrans">LogCustTrans</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogCustTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogDelete name="LogDelete">LogDelete</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogDelete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogDocuRef name="LogDocuRef">LogDocuRef</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogDocuRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogInsert name="LogInsert">LogInsert</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogInsert attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogLeadTable name="LogLeadTable">LogLeadTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogLeadTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogMailings name="LogMailings">LogMailings</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogMailings attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogOpportunity name="LogOpportunity">LogOpportunity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogOpportunity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogQuotationTable name="LogQuotationTable">LogQuotationTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogQuotationTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogSalesTable name="LogSalesTable">LogSalesTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogSalesTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogTMCallListTable name="LogTMCallListTable">LogTMCallListTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogTMCallListTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogUpdate name="LogUpdate">LogUpdate</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogVendTable name="LogVendTable">LogVendTable</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogVendTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LogVendTrans name="LogVendTrans">LogVendTrans</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogVendTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MailingfileDirectory name="MailingfileDirectory">MailingfileDirectory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mailing file directory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MailingfileDirectory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mailing file directory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogReqActivityCategory name="MCRCatalogReqActivityCategory">MCRCatalogReqActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog requested category</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogReqActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog requested category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRCatalogReqActivityCreate name="MCRCatalogReqActivityCreate">MCRCatalogReqActivityCreate</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create activity for catalog is requested</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogReqActivityCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create activity for catalog is requested</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRCatalogReqActivityPhase name="MCRCatalogReqActivityPhase">MCRCatalogReqActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog request activity phase</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogReqActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog request activity phase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogReqActivityPurpose name="MCRCatalogReqActivityPurpose">MCRCatalogReqActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog request activity purpose</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogReqActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog request activity purpose</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogReqActivityType name="MCRCatalogReqActivityType">MCRCatalogReqActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog request activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogReqActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog request activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogSentActivityCategory name="MCRCatalogSentActivityCategory">MCRCatalogSentActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog sent category</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogSentActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog sent category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRCatalogSentActivityCreate name="MCRCatalogSentActivityCreate">MCRCatalogSentActivityCreate</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create activity for catalog is sent</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogSentActivityCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create activity for catalog is sent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRCatalogSentActivityPhase name="MCRCatalogSentActivityPhase">MCRCatalogSentActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog sent activity phase</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogSentActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog sent activity phase</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogSentActivityPurpose name="MCRCatalogSentActivityPurpose">MCRCatalogSentActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog sent activity purpose</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogSentActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog sent activity purpose</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCatalogSentActivityType name="MCRCatalogSentActivityType">MCRCatalogSentActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catalog sent activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCatalogSentActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog sent activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumOfCampaignDaysFollowUpDate name="NumOfCampaignDaysFollowUpDate">NumOfCampaignDaysFollowUpDate</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days before follow-up</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfCampaignDaysFollowUpDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days before follow-up</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#OpenFromTime name="OpenFromTime">OpenFromTime</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenFromTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#OpenToTime name="OpenToTime">OpenToTime</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenToTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#PeriodFrom name="PeriodFrom">PeriodFrom</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PeriodId name="PeriodId">PeriodId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodTo name="PeriodTo">PeriodTo</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PhoneInboundActivityType name="PhoneInboundActivityType">PhoneInboundActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity type for inbound calls</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneInboundActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity type for inbound calls</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneOutboundActivityType name="PhoneOutboundActivityType">PhoneOutboundActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity type for outbound calls</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneOutboundActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity type for outbound calls</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneOutboundStandardPrefix name="PhoneOutboundStandardPrefix">PhoneOutboundStandardPrefix</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneOutboundStandardPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjGroupId name="ProjGroupId">ProjGroupId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationActivityCategory name="QuotationActivityCategory">QuotationActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#QuotationActivityPhaseId name="QuotationActivityPhaseId">QuotationActivityPhaseId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationActivityPhaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationActivityPurpose name="QuotationActivityPurpose">QuotationActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationActivityTypeId name="QuotationActivityTypeId">QuotationActivityTypeId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationCreateActivity name="QuotationCreateActivity">QuotationCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RunBaseBatchCreateActivity name="RunBaseBatchCreateActivity">RunBaseBatchCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunBaseBatchCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TelemarkeringTargetActivityPhase name="TelemarkeringTargetActivityPhase">TelemarkeringTargetActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarkeringTargetActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarketingActivityPurpose name="TelemarketingActivityPurpose">TelemarketingActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarketingTargetActivityCategory name="TelemarketingTargetActivityCategory">TelemarketingTargetActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingTargetActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TelemarketingTargetActivityType name="TelemarketingTargetActivityType">TelemarketingTargetActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingTargetActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelemarketingTargetsCreateActivity name="TelemarketingTargetsCreateActivity">TelemarketingTargetsCreateActivity</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelemarketingTargetsCreateActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TMCallBackActivityCategory name="TMCallBackActivityCategory">TMCallBackActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMCallBackActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TMCallBackActivityPhase name="TMCallBackActivityPhase">TMCallBackActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMCallBackActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMCallBackActivityPurpose name="TMCallBackActivityPurpose">TMCallBackActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMCallBackActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMCallbackActivityType name="TMCallbackActivityType">TMCallbackActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMCallbackActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMFollowUpActivityCategory name="TMFollowUpActivityCategory">TMFollowUpActivityCategory</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMFollowUpActivityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TMFollowUpActivityPhase name="TMFollowUpActivityPhase">TMFollowUpActivityPhase</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMFollowUpActivityPhase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMFollowUpActivityPurpose name="TMFollowUpActivityPurpose">TMFollowUpActivityPurpose</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMFollowUpActivityPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMFollowUpActivityType name="TMFollowUpActivityType">TMFollowUpActivityType</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMFollowUpActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransLogInterval name="TransLogInterval">TransLogInterval</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransLogInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UpdateOpportunityForProjectQuotation name="UpdateOpportunityForProjectQuotation">UpdateOpportunityForProjectQuotation</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update opportunity when project quotation status changes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateOpportunityForProjectQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update opportunity when project quotation status changes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UpdateOpportunityForSalesQuotation name="UpdateOpportunityForSalesQuotation">UpdateOpportunityForSalesQuotation</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update opportunity when sales quotation status changes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateOpportunityForSalesQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update opportunity when sales quotation status changes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VendGroupId name="VendGroupId">VendGroupId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WebSiteURL name="WebSiteURL">WebSiteURL</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WebSiteURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/smmParametersTable (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

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

### <a href=#Relationship_CustGroupRelationshipId name="Relationship_CustGroupRelationshipId">Relationship_CustGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustGroup.cdm.json/CustGroup</a></td><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuType_FilesRelationshipId name="Relationship_DocuType_FilesRelationshipId">Relationship_DocuType_FilesRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuType_FilesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuType_InEMailRelationshipId name="Relationship_DocuType_InEMailRelationshipId">Relationship_DocuType_InEMailRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuType_InEMailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuType_OutEMailRelationshipId name="Relationship_DocuType_OutEMailRelationshipId">Relationship_DocuType_OutEMailRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuType_OutEMailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

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

### <a href=#Relationship_ProjGroupRelationshipId name="Relationship_ProjGroupRelationshipId">Relationship_ProjGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjGroup.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjGroup.cdm.json/ProjGroup</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjPeriodTableRelationshipId name="Relationship_ProjPeriodTableRelationshipId">Relationship_ProjPeriodTableRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjPeriodTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.cdm.json/ProjPeriodTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjPeriodTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmBusRelStatusGroupRelationshipId name="Relationship_smmBusRelStatusGroupRelationshipId">Relationship_smmBusRelStatusGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmBusRelStatusGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmBusRelStatusGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmBusRelStatusGroup.cdm.json/smmBusRelStatusGroup</a></td><td><a href="../Group/smmBusRelStatusGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmBusRelTypeGroupRelationshipId name="Relationship_smmBusRelTypeGroupRelationshipId">Relationship_smmBusRelTypeGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmBusRelTypeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmBusRelTypeGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmBusRelTypeGroup.cdm.json/smmBusRelTypeGroup</a></td><td><a href="../Group/smmBusRelTypeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmCampaignGroupRelationshipId name="Relationship_smmCampaignGroupRelationshipId">Relationship_smmCampaignGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmCampaignGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmCampaignGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmCampaignGroup.cdm.json/smmCampaignGroup</a></td><td><a href="../Group/smmCampaignGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmCampaignTargetTableRelationshipId name="Relationship_smmCampaignTargetTableRelationshipId">Relationship_smmCampaignTargetTableRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmCampaignTargetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmCampaignTargetTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmCampaignTargetTable.cdm.json/smmCampaignTargetTable</a></td><td><a href="../Group/smmCampaignTargetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmCampaignTypeGroupRelationshipId name="Relationship_smmCampaignTypeGroupRelationshipId">Relationship_smmCampaignTypeGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmCampaignTypeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmCampaignTypeGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmCampaignTypeGroup.cdm.json/smmCampaignTypeGroup</a></td><td><a href="../Group/smmCampaignTypeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendGroupRelationshipId name="Relationship_VendGroupRelationshipId">Relationship_VendGroupRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Group/VendGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Group/VendGroup.cdm.json/VendGroup</a></td><td><a href="../../Vendor/Group/VendGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/smmParametersTable (this entity)  

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
