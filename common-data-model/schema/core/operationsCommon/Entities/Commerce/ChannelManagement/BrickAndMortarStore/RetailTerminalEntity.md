---
title: RetailTerminalEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# POS registers in BrickAndMortarStore(RetailTerminalEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailTerminalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS registers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TerminalNumber](#TerminalNumber)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[HardwareProfile](#HardwareProfile)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[VisualProfile](#VisualProfile)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Name](#Name)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[AutoLogoffTimeout](#AutoLogoffTimeout)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ClosingStatus](#ClosingStatus)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[CustomerDisplayText1](#CustomerDisplayText1)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[CustomerDisplayText2](#CustomerDisplayText2)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ElectronicFundsTransferTenderTypeIdDefault](#ElectronicFundsTransferTenderTypeIdDefault)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ElectronicFundsTransferTerminal](#ElectronicFundsTransferTerminal)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ExitAfterEachTransaction](#ExitAfterEachTransaction)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[InternetProtocolAddress](#InternetProtocolAddress)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ProductNumberOnReceipt](#ProductNumberOnReceipt)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[LayoutId](#LayoutId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Location](#Location)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ManagerKeyOnReturn](#ManagerKeyOnReturn)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[MaxDisplayTextLength](#MaxDisplayTextLength)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[MaxReceiptTextLength](#MaxReceiptTextLength)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[NumberOfTopBottomLines](#NumberOfTopBottomLines)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[OnlyTotalInSuspendedTransaction](#OnlyTotalInSuspendedTransaction)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[OpenDrawerAtLastInLastOut](#OpenDrawerAtLastInLastOut)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[PrintTaxRefundChecks](#PrintTaxRefundChecks)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ReceiptBarcode](#ReceiptBarcode)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ReceiptPrintingDefaultOff](#ReceiptPrintingDefaultOff)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ReceiptSetupLocation](#ReceiptSetupLocation)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[ReturnInTransaction](#ReturnInTransaction)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[SlipIfReturn](#SlipIfReturn)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[StandAlone](#StandAlone)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[StatementMethod](#StatementMethod)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[TerminalStatement](#TerminalStatement)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[UpdateServicePort](#UpdateServicePort)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[RetailTerminalOperationMode](#RetailTerminalOperationMode)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[SelectHardwareStationOnTendering](#SelectHardwareStationOnTendering)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[SupportOffline](#SupportOffline)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[OfflineDatabaseProfileName](#OfflineDatabaseProfileName)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[StoreNumberForElectronicFundsTransfer](#StoreNumberForElectronicFundsTransfer)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[DefaultDimensionLegalEntity](#DefaultDimensionLegalEntity)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[CreateRecording](#CreateRecording)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[PlaybackRecording](#PlaybackRecording)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[AutoExitMethod](#AutoExitMethod)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[CardNotPresentProcessingConfiguration](#CardNotPresentProcessingConfiguration)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Relationship_RetailStoreRelationshipId](#Relationship_RetailStoreRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Relationship_RetailHardwareProfileRelationshipId](#Relationship_RetailHardwareProfileRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Relationship_RetailVisualProfileRelationshipId](#Relationship_RetailVisualProfileRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[Relationship_RetailElectronicFundTransferStoreRelationshipId](#Relationship_RetailElectronicFundTransferStoreRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|
|[BackingTable_RetailTerminalTableRelationshipId](#BackingTable_RetailTerminalTableRelationshipId)||<a href="RetailTerminalEntity.md" target="_blank">BrickAndMortarStore/RetailTerminalEntity</a>|

### <a href=#TerminalNumber name="TerminalNumber">TerminalNumber</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareProfile name="HardwareProfile">HardwareProfile</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VisualProfile name="VisualProfile">VisualProfile</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisualProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoLogoffTimeout name="AutoLogoffTimeout">AutoLogoffTimeout</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoLogoffTimeout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosingStatus name="ClosingStatus">ClosingStatus</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosingStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDisplayText1 name="CustomerDisplayText1">CustomerDisplayText1</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDisplayText1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDisplayText2 name="CustomerDisplayText2">CustomerDisplayText2</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDisplayText2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferTenderTypeIdDefault name="ElectronicFundsTransferTenderTypeIdDefault">ElectronicFundsTransferTenderTypeIdDefault</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferTenderTypeIdDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferTerminal name="ElectronicFundsTransferTerminal">ElectronicFundsTransferTerminal</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExitAfterEachTransaction name="ExitAfterEachTransaction">ExitAfterEachTransaction</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitAfterEachTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternetProtocolAddress name="InternetProtocolAddress">InternetProtocolAddress</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternetProtocolAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumberOnReceipt name="ProductNumberOnReceipt">ProductNumberOnReceipt</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumberOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManagerKeyOnReturn name="ManagerKeyOnReturn">ManagerKeyOnReturn</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManagerKeyOnReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxDisplayTextLength name="MaxDisplayTextLength">MaxDisplayTextLength</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxDisplayTextLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxReceiptTextLength name="MaxReceiptTextLength">MaxReceiptTextLength</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxReceiptTextLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfTopBottomLines name="NumberOfTopBottomLines">NumberOfTopBottomLines</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfTopBottomLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnlyTotalInSuspendedTransaction name="OnlyTotalInSuspendedTransaction">OnlyTotalInSuspendedTransaction</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnlyTotalInSuspendedTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpenDrawerAtLastInLastOut name="OpenDrawerAtLastInLastOut">OpenDrawerAtLastInLastOut</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenDrawerAtLastInLastOut attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintTaxRefundChecks name="PrintTaxRefundChecks">PrintTaxRefundChecks</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTaxRefundChecks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptBarcode name="ReceiptBarcode">ReceiptBarcode</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptBarcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptPrintingDefaultOff name="ReceiptPrintingDefaultOff">ReceiptPrintingDefaultOff</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptPrintingDefaultOff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptSetupLocation name="ReceiptSetupLocation">ReceiptSetupLocation</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptSetupLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnInTransaction name="ReturnInTransaction">ReturnInTransaction</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnInTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipIfReturn name="SlipIfReturn">SlipIfReturn</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipIfReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandAlone name="StandAlone">StandAlone</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandAlone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementMethod name="StatementMethod">StatementMethod</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminalStatement name="TerminalStatement">TerminalStatement</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpdateServicePort name="UpdateServicePort">UpdateServicePort</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateServicePort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTerminalOperationMode name="RetailTerminalOperationMode">RetailTerminalOperationMode</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTerminalOperationMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SelectHardwareStationOnTendering name="SelectHardwareStationOnTendering">SelectHardwareStationOnTendering</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelectHardwareStationOnTendering attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SupportOffline name="SupportOffline">SupportOffline</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SupportOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfflineDatabaseProfileName name="OfflineDatabaseProfileName">OfflineDatabaseProfileName</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfflineDatabaseProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumberForElectronicFundsTransfer name="StoreNumberForElectronicFundsTransfer">StoreNumberForElectronicFundsTransfer</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumberForElectronicFundsTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionLegalEntity name="DefaultDimensionLegalEntity">DefaultDimensionLegalEntity</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateRecording name="CreateRecording">CreateRecording</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateRecording attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlaybackRecording name="PlaybackRecording">PlaybackRecording</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlaybackRecording attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoExitMethod name="AutoExitMethod">AutoExitMethod</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoExitMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNotPresentProcessingConfiguration name="CardNotPresentProcessingConfiguration">CardNotPresentProcessingConfiguration</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNotPresentProcessingConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailStoreRelationshipId name="Relationship_RetailStoreRelationshipId">Relationship_RetailStoreRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailHardwareProfileRelationshipId name="Relationship_RetailHardwareProfileRelationshipId">Relationship_RetailHardwareProfileRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailHardwareProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailVisualProfileRelationshipId name="Relationship_RetailVisualProfileRelationshipId">Relationship_RetailVisualProfileRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailVisualProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailElectronicFundTransferStoreRelationshipId name="Relationship_RetailElectronicFundTransferStoreRelationshipId">Relationship_RetailElectronicFundTransferStoreRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailElectronicFundTransferStoreRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailTerminalTableRelationshipId name="BackingTable_RetailTerminalTableRelationshipId">BackingTable_RetailTerminalTableRelationshipId</a>

First included in: BrickAndMortarStore/RetailTerminalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
