---
title: SalesParmTable in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales order - update table in Transaction(SalesParmTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order - update table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[AttorneyDate_RU](#AttorneyDate_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[AttorneyId_RU](#AttorneyId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[AttorneyIssuedName_RU](#AttorneyIssuedName_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BankLCExportLine](#BankLCExportLine)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BatchAdministration](#BatchAdministration)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BatchType](#BatchType)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLCarrierCode_RU](#BOLCarrierCode_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLCarrierType_RU](#BOLCarrierType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLDeliveryDate_RU](#BOLDeliveryDate_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLDriverName_RU](#BOLDriverName_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLDrivingLicenseNum_RU](#BOLDrivingLicenseNum_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLLicenseCardNum_RU](#BOLLicenseCardNum_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLLicenseCardRegNum_RU](#BOLLicenseCardRegNum_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLLicenseCardSeries_RU](#BOLLicenseCardSeries_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLLicenseCardType_RU](#BOLLicenseCardType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLTransportationType_RU](#BOLTransportationType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLVehicleModel_RU](#BOLVehicleModel_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLVehiclePlateNum_RU](#BOLVehiclePlateNum_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[BOLWaybillNum_RU](#BOLWaybillNum_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CargoDescription_RU](#CargoDescription_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CargoPacking_RU](#CargoPacking_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CarrierCode_RU](#CarrierCode_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CarrierType_RU](#CarrierType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CashDiscBaseDate](#CashDiscBaseDate)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CashDiscBaseDays](#CashDiscBaseDays)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Correct_RU](#Correct_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectedFactureDate_RU](#CorrectedFactureDate_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectedFactureExternalId_RU](#CorrectedFactureExternalId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectedInvoiceDate_RU](#CorrectedInvoiceDate_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectedInvoiceId_RU](#CorrectedInvoiceId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectedPeriod_RU](#CorrectedPeriod_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CorrectionType_RU](#CorrectionType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CustAccount](#CustAccount)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CustBankAccountId](#CustBankAccountId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CustomsExportInvoiceId_IN](#CustomsExportInvoiceId_IN)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CustomsShippingBillNumberTable_IN](#CustomsShippingBillNumberTable_IN)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CustPackingSlipJour](#CustPackingSlipJour)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DeliveryName](#DeliveryName)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DlvMode](#DlvMode)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DlvTerm](#DlvTerm)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DocumentDate](#DocumentDate)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DocumentStornoId_RU](#DocumentStornoId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DriverContact_RU](#DriverContact_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[EndDateTime](#EndDateTime)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[EntryCertificateRequired_W](#EntryCertificateRequired_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[EximExportDateTime_IN](#EximExportDateTime_IN)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentAccessKey_BR](#FiscalDocumentAccessKey_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentModel_BR](#FiscalDocumentModel_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentNumber_BR](#FiscalDocumentNumber_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentSeries_BR](#FiscalDocumentSeries_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentSpecie_BR](#FiscalDocumentSpecie_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FiscalDocumentType_BR](#FiscalDocumentType_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[FixedDueDate](#FixedDueDate)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[GoodsInRouteId_RU](#GoodsInRouteId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InventOwnerId_RU](#InventOwnerId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InventProfileType_RU](#InventProfileType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InventSiteId](#InventSiteId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InvoicePostingType_RU](#InvoicePostingType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[IssueOwnEntryCertificate_W](#IssueOwnEntryCertificate_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[LadingPostalAddress_RU](#LadingPostalAddress_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Log](#Log)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[MCRPackingBoxName](#MCRPackingBoxName)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[NeedTransIDTransit_RU](#NeedTransIDTransit_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Num_W](#Num_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[OffReportType_RU](#OffReportType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[OffSessionId_RU](#OffSessionId_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Ordering](#Ordering)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[PackingSlipIdForUpdate_W](#PackingSlipIdForUpdate_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ParmId](#ParmId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ParmJobStatus](#ParmJobStatus)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[PostingProfile_RU](#PostingProfile_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[PostponeVAT](#PostponeVAT)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[PrintBlankDate_LT](#PrintBlankDate_LT)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[PrintOverdueFineTxt_FR](#PrintOverdueFineTxt_FR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ProjId](#ProjId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ReturnDeadline](#ReturnDeadline)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ReturnItemNum](#ReturnItemNum)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ReturnPackingSlipId](#ReturnPackingSlipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ReturnStatus](#ReturnStatus)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[SalesDate_W](#SalesDate_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[SalesId](#SalesId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[SalesName](#SalesName)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ShipCarrierAccount](#ShipCarrierAccount)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ShipCarrierId](#ShipCarrierId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ShipCarrierPostalAddress](#ShipCarrierPostalAddress)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[StartDateTime](#StartDateTime)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Storno](#Storno)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TableRefId](#TableRefId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TaxPeriodPaymentCode_PL](#TaxPeriodPaymentCode_PL)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TaxServiceCodeId_BR](#TaxServiceCodeId_BR)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Transdate](#Transdate)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TransportationPayer_RU](#TransportationPayer_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TransportationPayerType_RU](#TransportationPayerType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TransportInvoiceType_RU](#TransportInvoiceType_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[UnladingPostalAddress_RU](#UnladingPostalAddress_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[VatDueDate_W](#VatDueDate_W)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[VATOnPayment_RU](#VATOnPayment_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[InvoiceType_MY](#InvoiceType_MY)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[TransportationDocument](#TransportationDocument)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DocAutoNumbering_LT](#DocAutoNumbering_LT)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[ProvisionalAssessment_IN](#ProvisionalAssessment_IN)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CFDIEnabled_MX](#CFDIEnabled_MX)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[UseOriginalDocumentAsFacture_RU](#UseOriginalDocumentAsFacture_RU)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[AllowLineLevelTaxAdjustments](#AllowLineLevelTaxAdjustments)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[CredManReleaseReasonId](#CredManReleaseReasonId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[DataAreaId](#DataAreaId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_BankLCExportLineRelationshipId](#Relationship_BankLCExportLineRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_Carrier_Cust_RURelationshipId](#Relationship_Carrier_Cust_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_Carrier_Vend_RURelationshipId](#Relationship_Carrier_Vend_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CustBankAccountRelationshipId](#Relationship_CustBankAccountRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CustomsShippingBillNumberTable_INRelationshipId](#Relationship_CustomsShippingBillNumberTable_INRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CustPackingSlipJourRelationshipId](#Relationship_CustPackingSlipJourRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_DeliveryPostalAddress_FKRelationshipId](#Relationship_DeliveryPostalAddress_FKRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_DlvModeRelationshipId](#Relationship_DlvModeRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_DlvTermRelationshipId](#Relationship_DlvTermRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_FiscalDocModel_BRRelationshipId](#Relationship_FiscalDocModel_BRRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_FiscalDocumentType_BRRelationshipId](#Relationship_FiscalDocumentType_BRRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_GoodsInRouteJour_RURelationshipId](#Relationship_GoodsInRouteJour_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_InventOwner_RURelationshipId](#Relationship_InventOwner_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_InvoiceCustomerRelationshipId](#Relationship_InvoiceCustomerRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_LadingPostalAddress_RURelationshipId](#Relationship_LadingPostalAddress_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_MCRPackingBoxTableRelationshipId](#Relationship_MCRPackingBoxTableRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_OfficialsTrans_RURelationshipId](#Relationship_OfficialsTrans_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_OrderCustomerRelationshipId](#Relationship_OrderCustomerRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_Payer_CustTable_RURelationshipId](#Relationship_Payer_CustTable_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_PlTaxDueTableRelationshipId](#Relationship_PlTaxDueTableRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_PostingProfile_RURelationshipId](#Relationship_PostingProfile_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_SalesParmUpdateRelationshipId](#Relationship_SalesParmUpdateRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_ShipCarrierPostalAddress_FKRelationshipId](#Relationship_ShipCarrierPostalAddress_FKRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_TaxInformation_INRelationshipId](#Relationship_TaxInformation_INRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_TransportationTypeTable_RURelationshipId](#Relationship_TransportationTypeTable_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_UnladingPostalAddress_RURelationshipId](#Relationship_UnladingPostalAddress_RURelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_VehicleModelTable_WRelationshipId](#Relationship_VehicleModelTable_WRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_TransportationDocumentRelationshipId](#Relationship_TransportationDocumentRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CredManReasonTableRelationshipId](#Relationship_CredManReasonTableRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SalesParmTable.md" target="_blank">Transaction/SalesParmTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttorneyDate_RU name="AttorneyDate_RU">AttorneyDate_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AttorneyId_RU name="AttorneyId_RU">AttorneyId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttorneyIssuedName_RU name="AttorneyIssuedName_RU">AttorneyIssuedName_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyIssuedName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankLCExportLine name="BankLCExportLine">BankLCExportLine</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankLCExportLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchAdministration name="BatchAdministration">BatchAdministration</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchAdministration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BatchType name="BatchType">BatchType</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOLCarrierCode_RU name="BOLCarrierCode_RU">BOLCarrierCode_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLCarrierCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLCarrierType_RU name="BOLCarrierType_RU">BOLCarrierType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLCarrierType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOLDeliveryDate_RU name="BOLDeliveryDate_RU">BOLDeliveryDate_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLDeliveryDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#BOLDriverName_RU name="BOLDriverName_RU">BOLDriverName_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLDriverName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLDrivingLicenseNum_RU name="BOLDrivingLicenseNum_RU">BOLDrivingLicenseNum_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLDrivingLicenseNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLLicenseCardNum_RU name="BOLLicenseCardNum_RU">BOLLicenseCardNum_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLLicenseCardNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLLicenseCardRegNum_RU name="BOLLicenseCardRegNum_RU">BOLLicenseCardRegNum_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLLicenseCardRegNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLLicenseCardSeries_RU name="BOLLicenseCardSeries_RU">BOLLicenseCardSeries_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLLicenseCardSeries_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLLicenseCardType_RU name="BOLLicenseCardType_RU">BOLLicenseCardType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLLicenseCardType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOLTransportationType_RU name="BOLTransportationType_RU">BOLTransportationType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLTransportationType_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLVehicleModel_RU name="BOLVehicleModel_RU">BOLVehicleModel_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLVehicleModel_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLVehiclePlateNum_RU name="BOLVehiclePlateNum_RU">BOLVehiclePlateNum_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLVehiclePlateNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLWaybillNum_RU name="BOLWaybillNum_RU">BOLWaybillNum_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLWaybillNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CargoDescription_RU name="CargoDescription_RU">CargoDescription_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoDescription_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CargoPacking_RU name="CargoPacking_RU">CargoPacking_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CargoPacking_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode_RU name="CarrierCode_RU">CarrierCode_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierType_RU name="CarrierType_RU">CarrierType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CashDiscBaseDate name="CashDiscBaseDate">CashDiscBaseDate</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscBaseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CashDiscBaseDays name="CashDiscBaseDays">CashDiscBaseDays</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscBaseDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Correct_RU name="Correct_RU">Correct_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Correct_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CorrectedFactureDate_RU name="CorrectedFactureDate_RU">CorrectedFactureDate_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facture date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Facture date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CorrectedFactureExternalId_RU name="CorrectedFactureExternalId_RU">CorrectedFactureExternalId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureExternalId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceDate_RU name="CorrectedInvoiceDate_RU">CorrectedInvoiceDate_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CorrectedInvoiceId_RU name="CorrectedInvoiceId_RU">CorrectedInvoiceId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedPeriod_RU name="CorrectedPeriod_RU">CorrectedPeriod_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Corrected period</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedPeriod_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Corrected period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CorrectionType_RU name="CorrectionType_RU">CorrectionType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustBankAccountId name="CustBankAccountId">CustBankAccountId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsExportInvoiceId_IN name="CustomsExportInvoiceId_IN">CustomsExportInvoiceId_IN</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsExportInvoiceId_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsShippingBillNumberTable_IN name="CustomsShippingBillNumberTable_IN">CustomsShippingBillNumberTable_IN</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsShippingBillNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustPackingSlipJour name="CustPackingSlipJour">CustPackingSlipJour</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPackingSlipJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DlvMode name="DlvMode">DlvMode</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvTerm name="DlvTerm">DlvTerm</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DocumentStornoId_RU name="DocumentStornoId_RU">DocumentStornoId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentStornoId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverContact_RU name="DriverContact_RU">DriverContact_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverContact_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EntryCertificateRequired_W name="EntryCertificateRequired_W">EntryCertificateRequired_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateRequired_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EximExportDateTime_IN name="EximExportDateTime_IN">EximExportDateTime_IN</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Let export date/time</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximExportDateTime_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Let export date/time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#FiscalDocumentAccessKey_BR name="FiscalDocumentAccessKey_BR">FiscalDocumentAccessKey_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentAccessKey_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentModel_BR name="FiscalDocumentModel_BR">FiscalDocumentModel_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentModel_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentNumber_BR name="FiscalDocumentNumber_BR">FiscalDocumentNumber_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal document number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries_BR name="FiscalDocumentSeries_BR">FiscalDocumentSeries_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSpecie_BR name="FiscalDocumentSpecie_BR">FiscalDocumentSpecie_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSpecie_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FiscalDocumentType_BR name="FiscalDocumentType_BR">FiscalDocumentType_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FixedDueDate name="FixedDueDate">FixedDueDate</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#GoodsInRouteId_RU name="GoodsInRouteId_RU">GoodsInRouteId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GoodsInRouteId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventOwnerId_RU name="InventOwnerId_RU">InventOwnerId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventOwnerId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileType_RU name="InventProfileType_RU">InventProfileType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePostingType_RU name="InvoicePostingType_RU">InvoicePostingType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePostingType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IssueOwnEntryCertificate_W name="IssueOwnEntryCertificate_W">IssueOwnEntryCertificate_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueOwnEntryCertificate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LadingPostalAddress_RU name="LadingPostalAddress_RU">LadingPostalAddress_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lading address</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LadingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lading address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Log attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRPackingBoxName name="MCRPackingBoxName">MCRPackingBoxName</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPackingBoxName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NeedTransIDTransit_RU name="NeedTransIDTransit_RU">NeedTransIDTransit_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NeedTransIDTransit_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Num_W name="Num_W">Num_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Num_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffReportType_RU name="OffReportType_RU">OffReportType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffReportType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OffSessionId_RU name="OffSessionId_RU">OffSessionId_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffSessionId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ordering name="Ordering">Ordering</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PackingSlipIdForUpdate_W name="PackingSlipIdForUpdate_W">PackingSlipIdForUpdate_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipIdForUpdate_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParmJobStatus name="ParmJobStatus">ParmJobStatus</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmJobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingProfile_RU name="PostingProfile_RU">PostingProfile_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostponeVAT name="PostponeVAT">PostponeVAT</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostponeVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintBlankDate_LT name="PrintBlankDate_LT">PrintBlankDate_LT</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBlankDate_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintOverdueFineTxt_FR name="PrintOverdueFineTxt_FR">PrintOverdueFineTxt_FR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintOverdueFineTxt_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDeadline name="ReturnDeadline">ReturnDeadline</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDeadline attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReturnItemNum name="ReturnItemNum">ReturnItemNum</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnItemNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnPackingSlipId name="ReturnPackingSlipId">ReturnPackingSlipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnPackingSlipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnStatus name="ReturnStatus">ReturnStatus</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesDate_W name="SalesDate_W">SalesDate_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesId name="SalesId">SalesId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesName name="SalesName">SalesName</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipCarrierAccount name="ShipCarrierAccount">ShipCarrierAccount</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipCarrierId name="ShipCarrierId">ShipCarrierId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipCarrierPostalAddress name="ShipCarrierPostalAddress">ShipCarrierPostalAddress</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Storno name="Storno">Storno</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit correction</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Storno attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit correction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TableRefId name="TableRefId">TableRefId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxPeriodPaymentCode_PL name="TaxPeriodPaymentCode_PL">TaxPeriodPaymentCode_PL</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriodPaymentCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCodeId_BR name="TaxServiceCodeId_BR">TaxServiceCodeId_BR</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCodeId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transdate name="Transdate">Transdate</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of update</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transdate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of update</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#TransportationPayer_RU name="TransportationPayer_RU">TransportationPayer_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPayer_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPayerType_RU name="TransportationPayerType_RU">TransportationPayerType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPayerType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransportInvoiceType_RU name="TransportInvoiceType_RU">TransportInvoiceType_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportInvoiceType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UnladingPostalAddress_RU name="UnladingPostalAddress_RU">UnladingPostalAddress_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unlading address</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnladingPostalAddress_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unlading address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VatDueDate_W name="VatDueDate_W">VatDueDate_W</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VATOnPayment_RU name="VATOnPayment_RU">VATOnPayment_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOnPayment_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InvoiceType_MY name="InvoiceType_MY">InvoiceType_MY</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceType_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransportationDocument name="TransportationDocument">TransportationDocument</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocAutoNumbering_LT name="DocAutoNumbering_LT">DocAutoNumbering_LT</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocAutoNumbering_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProvisionalAssessment_IN name="ProvisionalAssessment_IN">ProvisionalAssessment_IN</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provisional assessment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionalAssessment_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provisional assessment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CFDIEnabled_MX name="CFDIEnabled_MX">CFDIEnabled_MX</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIEnabled_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseOriginalDocumentAsFacture_RU name="UseOriginalDocumentAsFacture_RU">UseOriginalDocumentAsFacture_RU</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseOriginalDocumentAsFacture_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowLineLevelTaxAdjustments name="AllowLineLevelTaxAdjustments">AllowLineLevelTaxAdjustments</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLineLevelTaxAdjustments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CredManReleaseReasonId name="CredManReleaseReasonId">CredManReleaseReasonId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManReleaseReasonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/SalesParmTable (this entity)  

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

### <a href=#Relationship_BankLCExportLineRelationshipId name="Relationship_BankLCExportLineRelationshipId">Relationship_BankLCExportLineRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankLCExportLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/WorksheetLine/BankLCExportLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLCExportLine.cdm.json/BankLCExportLine</a></td><td><a href="../../../Finance/Bank/WorksheetLine/BankLCExportLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Carrier_Cust_RURelationshipId name="Relationship_Carrier_Cust_RURelationshipId">Relationship_Carrier_Cust_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Carrier_Cust_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Carrier_Vend_RURelationshipId name="Relationship_Carrier_Vend_RURelationshipId">Relationship_Carrier_Vend_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Carrier_Vend_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

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

### <a href=#Relationship_CustBankAccountRelationshipId name="Relationship_CustBankAccountRelationshipId">Relationship_CustBankAccountRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustBankAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/CustBankAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustBankAccount.cdm.json/CustBankAccount</a></td><td><a href="../../../Finance/AccountsReceivable/Main/CustBankAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsShippingBillNumberTable_INRelationshipId name="Relationship_CustomsShippingBillNumberTable_INRelationshipId">Relationship_CustomsShippingBillNumberTable_INRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsShippingBillNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/CustomsShippingBillNumberTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustomsShippingBillNumberTable_IN.cdm.json/CustomsShippingBillNumberTable_IN</a></td><td><a href="../../../Finance/AccountsReceivable/Main/CustomsShippingBillNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPackingSlipJourRelationshipId name="Relationship_CustPackingSlipJourRelationshipId">Relationship_CustPackingSlipJourRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPackingSlipJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustPackingSlipJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/CustPackingSlipJour.cdm.json/CustPackingSlipJour</a></td><td><a href="CustPackingSlipJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryPostalAddress_FKRelationshipId name="Relationship_DeliveryPostalAddress_FKRelationshipId">Relationship_DeliveryPostalAddress_FKRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryPostalAddress_FKRelationshipId attribute are listed below.</summary>

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

First included in: Transaction/SalesParmTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/DlvMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvMode.cdm.json/DlvMode</a></td><td><a href="../Group/DlvMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvTermRelationshipId name="Relationship_DlvTermRelationshipId">Relationship_DlvTermRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/DlvTerm.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvTerm.cdm.json/DlvTerm</a></td><td><a href="../Group/DlvTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocModel_BRRelationshipId name="Relationship_FiscalDocModel_BRRelationshipId">Relationship_FiscalDocModel_BRRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocModel_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.cdm.json/FiscalDocModel_BR</a></td><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentType_BRRelationshipId name="Relationship_FiscalDocumentType_BRRelationshipId">Relationship_FiscalDocumentType_BRRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.cdm.json/FiscalDocumentType_BR</a></td><td><a href="../../../Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GoodsInRouteJour_RURelationshipId name="Relationship_GoodsInRouteJour_RURelationshipId">Relationship_GoodsInRouteJour_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GoodsInRouteJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/GoodsInRouteJour_RU.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/GoodsInRouteJour_RU.cdm.json/GoodsInRouteJour_RU</a></td><td><a href="../../Inventory/Transaction/GoodsInRouteJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventOwner_RURelationshipId name="Relationship_InventOwner_RURelationshipId">Relationship_InventOwner_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventOwner_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventOwner_RU.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventOwner_RU.cdm.json/InventOwner_RU</a></td><td><a href="../../Inventory/Group/InventOwner_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

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

### <a href=#Relationship_InvoiceCustomerRelationshipId name="Relationship_InvoiceCustomerRelationshipId">Relationship_InvoiceCustomerRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceCustomerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LadingPostalAddress_RURelationshipId name="Relationship_LadingPostalAddress_RURelationshipId">Relationship_LadingPostalAddress_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LadingPostalAddress_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MCRPackingBoxTableRelationshipId name="Relationship_MCRPackingBoxTableRelationshipId">Relationship_MCRPackingBoxTableRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRPackingBoxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/TransactionLine/MCRPackingBoxTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionLine/MCRPackingBoxTable.cdm.json/MCRPackingBoxTable</a></td><td><a href="../../Inventory/TransactionLine/MCRPackingBoxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OfficialsTrans_RURelationshipId name="Relationship_OfficialsTrans_RURelationshipId">Relationship_OfficialsTrans_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfficialsTrans_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Transaction/OfficialsTrans_RU.cdm.json/OfficialsTrans_RU</a></td><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrderCustomerRelationshipId name="Relationship_OrderCustomerRelationshipId">Relationship_OrderCustomerRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderCustomerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Payer_CustTable_RURelationshipId name="Relationship_Payer_CustTable_RURelationshipId">Relationship_Payer_CustTable_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Payer_CustTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlTaxDueTableRelationshipId name="Relationship_PlTaxDueTableRelationshipId">Relationship_PlTaxDueTableRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlTaxDueTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/PlTaxDueTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/PlTaxDueTable.cdm.json/PlTaxDueTable</a></td><td><a href="../../../Finance/Tax/Group/PlTaxDueTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PostingProfile_RURelationshipId name="Relationship_PostingProfile_RURelationshipId">Relationship_PostingProfile_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PostingProfile_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Group/CustLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../../../Finance/AccountsReceivable/Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

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

### <a href=#Relationship_SalesParmUpdateRelationshipId name="Relationship_SalesParmUpdateRelationshipId">Relationship_SalesParmUpdateRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesParmUpdateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SalesParmUpdate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/SalesParmUpdate.cdm.json/SalesParmUpdate</a></td><td><a href="SalesParmUpdate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ShipCarrierPostalAddress_FKRelationshipId name="Relationship_ShipCarrierPostalAddress_FKRelationshipId">Relationship_ShipCarrierPostalAddress_FKRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ShipCarrierPostalAddress_FKRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxInformation_INRelationshipId name="Relationship_TaxInformation_INRelationshipId">Relationship_TaxInformation_INRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxInformation_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxInformation_IN.cdm.json/TaxInformation_IN</a></td><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationTypeTable_RURelationshipId name="Relationship_TransportationTypeTable_RURelationshipId">Relationship_TransportationTypeTable_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationTypeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/TransportationTypeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/TransportationTypeTable_RU.cdm.json/TransportationTypeTable_RU</a></td><td><a href="../../../Finance/AccountsReceivable/Main/TransportationTypeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnladingPostalAddress_RURelationshipId name="Relationship_UnladingPostalAddress_RURelationshipId">Relationship_UnladingPostalAddress_RURelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnladingPostalAddress_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VehicleModelTable_WRelationshipId name="Relationship_VehicleModelTable_WRelationshipId">Relationship_VehicleModelTable_WRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VehicleModelTable_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/VehicleModelTable_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/VehicleModelTable_W.cdm.json/VehicleModelTable_W</a></td><td><a href="../../../Finance/AccountsReceivable/Main/VehicleModelTable_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationDocumentRelationshipId name="Relationship_TransportationDocumentRelationshipId">Relationship_TransportationDocumentRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationDocumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/WorksheetHeader/TransportationDocument.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/TransportationDocument.cdm.json/TransportationDocument</a></td><td><a href="../../../Finance/AccountsReceivable/WorksheetHeader/TransportationDocument.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CredManReasonTableRelationshipId name="Relationship_CredManReasonTableRelationshipId">Relationship_CredManReasonTableRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CredManReasonTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Group/CredManReasonTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CredManReasonTable.cdm.json/CredManReasonTable</a></td><td><a href="../../../Finance/AccountsReceivable/Group/CredManReasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/SalesParmTable (this entity)  

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
