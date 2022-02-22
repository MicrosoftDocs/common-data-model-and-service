---
title: RetailPosPermissionGroupEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS permission group in BrickAndMortarStore(RetailPosPermissionGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailPosPermissionGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS permission group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowBlindClose](#AllowBlindClose)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowChangeNoVoid](#AllowChangeNoVoid)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowChangePeripheralStation](#AllowChangePeripheralStation)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowCreateOrder](#AllowCreateOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowEditOrder](#AllowEditOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowFloatingTenderDeclaration](#AllowFloatingTenderDeclaration)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowKitDisassembly](#AllowKitDisassembly)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowMultipleLogins](#AllowMultipleLogins)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowMultipleShiftLogon](#AllowMultipleShiftLogon)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowOpenDrawerOnly](#AllowOpenDrawerOnly)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowPasswordChange](#AllowPasswordChange)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowPriceOverride](#AllowPriceOverride)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowResetPassword](#AllowResetPassword)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowRetrieveOrder](#AllowRetrieveOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSalesTaxChange](#AllowSalesTaxChange)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowTenderDeclaration](#AllowTenderDeclaration)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowTransactionSuspension](#AllowTransactionSuspension)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowTransactionVoiding](#AllowTransactionVoiding)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowXReportPrinting](#AllowXReportPrinting)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowZReportPrinting](#AllowZReportPrinting)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[ManageDevice](#ManageDevice)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[ManagerPrivileges](#ManagerPrivileges)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxDiscountPercentage](#MaxDiscountPercentage)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxLineDiscountAmount](#MaxLineDiscountAmount)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxLineReturnAmount](#MaxLineReturnAmount)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxTotalDiscountAmount](#MaxTotalDiscountAmount)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxTotalDiscountPercentage](#MaxTotalDiscountPercentage)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[MaxTotalReturnAmount](#MaxTotalReturnAmount)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[Name](#Name)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[PosPermissionGroupId](#PosPermissionGroupId)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[UseHandheld](#UseHandheld)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowViewTimeclockEntries](#AllowViewTimeclockEntries)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowManageSharedShift](#AllowManageSharedShift)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSetupLabelPrinter](#AllowSetupLabelPrinter)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowUseSharedShift](#AllowUseSharedShift)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowTaskGuides](#AllowTaskGuides)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSaleOutsideAssortment](#AllowSaleOutsideAssortment)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowPrintingReceiptCopy](#AllowPrintingReceiptCopy)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSkipFiscalRegistration](#AllowSkipFiscalRegistration)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowCreateTransferOrder](#AllowCreateTransferOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowAcceptOrder](#AllowAcceptOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowRejectOrder](#AllowRejectOrder)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowMassActivation](#AllowMassActivation)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSkipRegistrationOrMarkAsRegistered](#AllowSkipRegistrationOrMarkAsRegistered)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowSkipHealthCheckError](#AllowSkipHealthCheckError)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[AllowTaskManagement](#AllowTaskManagement)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|
|[BackingTable_RetailPosPermissionGroupRelationshipId](#BackingTable_RetailPosPermissionGroupRelationshipId)||<a href="RetailPosPermissionGroupEntity.md" target="_blank">BrickAndMortarStore/RetailPosPermissionGroupEntity</a>|

### <a href=#AllowBlindClose name="AllowBlindClose">AllowBlindClose</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBlindClose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowChangeNoVoid name="AllowChangeNoVoid">AllowChangeNoVoid</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowChangeNoVoid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowChangePeripheralStation name="AllowChangePeripheralStation">AllowChangePeripheralStation</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow change peripheral station</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowChangePeripheralStation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow change peripheral station</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowCreateOrder name="AllowCreateOrder">AllowCreateOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCreateOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowEditOrder name="AllowEditOrder">AllowEditOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowEditOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowFloatingTenderDeclaration name="AllowFloatingTenderDeclaration">AllowFloatingTenderDeclaration</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowFloatingTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowKitDisassembly name="AllowKitDisassembly">AllowKitDisassembly</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowKitDisassembly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMultipleLogins name="AllowMultipleLogins">AllowMultipleLogins</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleLogins attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMultipleShiftLogon name="AllowMultipleShiftLogon">AllowMultipleShiftLogon</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleShiftLogon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowOpenDrawerOnly name="AllowOpenDrawerOnly">AllowOpenDrawerOnly</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowOpenDrawerOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPasswordChange name="AllowPasswordChange">AllowPasswordChange</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow password change</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPasswordChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow password change</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPriceOverride name="AllowPriceOverride">AllowPriceOverride</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPriceOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowResetPassword name="AllowResetPassword">AllowResetPassword</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow reset password</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowResetPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow reset password</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowRetrieveOrder name="AllowRetrieveOrder">AllowRetrieveOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRetrieveOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSalesTaxChange name="AllowSalesTaxChange">AllowSalesTaxChange</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSalesTaxChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTenderDeclaration name="AllowTenderDeclaration">AllowTenderDeclaration</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTransactionSuspension name="AllowTransactionSuspension">AllowTransactionSuspension</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTransactionSuspension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTransactionVoiding name="AllowTransactionVoiding">AllowTransactionVoiding</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTransactionVoiding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowXReportPrinting name="AllowXReportPrinting">AllowXReportPrinting</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowXReportPrinting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowZReportPrinting name="AllowZReportPrinting">AllowZReportPrinting</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowZReportPrinting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManageDevice name="ManageDevice">ManageDevice</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManageDevice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManagerPrivileges name="ManagerPrivileges">ManagerPrivileges</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManagerPrivileges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxDiscountPercentage name="MaxDiscountPercentage">MaxDiscountPercentage</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxLineDiscountAmount name="MaxLineDiscountAmount">MaxLineDiscountAmount</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum line discount amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum line discount amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxLineReturnAmount name="MaxLineReturnAmount">MaxLineReturnAmount</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum line return amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxLineReturnAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum line return amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxTotalDiscountAmount name="MaxTotalDiscountAmount">MaxTotalDiscountAmount</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum total discount amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum total discount amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxTotalDiscountPercentage name="MaxTotalDiscountPercentage">MaxTotalDiscountPercentage</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum discount total percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxTotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum discount total percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxTotalReturnAmount name="MaxTotalReturnAmount">MaxTotalReturnAmount</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum total return amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxTotalReturnAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum total return amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

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

### <a href=#PosPermissionGroupId name="PosPermissionGroupId">PosPermissionGroupId</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosPermissionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseHandheld name="UseHandheld">UseHandheld</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseHandheld attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowViewTimeclockEntries name="AllowViewTimeclockEntries">AllowViewTimeclockEntries</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>View time clock entries</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowViewTimeclockEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>View time clock entries</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowManageSharedShift name="AllowManageSharedShift">AllowManageSharedShift</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow manage shared shift</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowManageSharedShift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow manage shared shift</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSetupLabelPrinter name="AllowSetupLabelPrinter">AllowSetupLabelPrinter</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSetupLabelPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowUseSharedShift name="AllowUseSharedShift">AllowUseSharedShift</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow use shared shift</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowUseSharedShift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow use shared shift</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTaskGuides name="AllowTaskGuides">AllowTaskGuides</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTaskGuides attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSaleOutsideAssortment name="AllowSaleOutsideAssortment">AllowSaleOutsideAssortment</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSaleOutsideAssortment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPrintingReceiptCopy name="AllowPrintingReceiptCopy">AllowPrintingReceiptCopy</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPrintingReceiptCopy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSkipFiscalRegistration name="AllowSkipFiscalRegistration">AllowSkipFiscalRegistration</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipFiscalRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowCreateTransferOrder name="AllowCreateTransferOrder">AllowCreateTransferOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCreateTransferOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowAcceptOrder name="AllowAcceptOrder">AllowAcceptOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAcceptOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowRejectOrder name="AllowRejectOrder">AllowRejectOrder</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRejectOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMassActivation name="AllowMassActivation">AllowMassActivation</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMassActivation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSkipRegistrationOrMarkAsRegistered name="AllowSkipRegistrationOrMarkAsRegistered">AllowSkipRegistrationOrMarkAsRegistered</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipRegistrationOrMarkAsRegistered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowSkipHealthCheckError name="AllowSkipHealthCheckError">AllowSkipHealthCheckError</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipHealthCheckError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTaskManagement name="AllowTaskManagement">AllowTaskManagement</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTaskManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailPosPermissionGroupRelationshipId name="BackingTable_RetailPosPermissionGroupRelationshipId">BackingTable_RetailPosPermissionGroupRelationshipId</a>

First included in: BrickAndMortarStore/RetailPosPermissionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailPosPermissionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPosPermissionGroup.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPosPermissionGroup.cdm.json/RetailPosPermissionGroup</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPosPermissionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
