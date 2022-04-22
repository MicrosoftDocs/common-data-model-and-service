---
title: RetailPositionPosPermissionEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS permissions by position in BrickAndMortarStore(RetailPositionPosPermissionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailPositionPosPermissionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS permissions by position</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowBlindClose](#AllowBlindClose)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowChangeNoVoid](#AllowChangeNoVoid)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowChangePeripheralStation](#AllowChangePeripheralStation)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowCreateOrder](#AllowCreateOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowEditOrder](#AllowEditOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowFloatingDeclaration](#AllowFloatingDeclaration)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowKitDisassembly](#AllowKitDisassembly)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowMultipleLogons](#AllowMultipleLogons)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowMultipleShiftLogon](#AllowMultipleShiftLogon)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[OpenDrawerWithoutSale](#OpenDrawerWithoutSale)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowPasswordChange](#AllowPasswordChange)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowPriceOverride](#AllowPriceOverride)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowResetPassword](#AllowResetPassword)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowRetrieveOrder](#AllowRetrieveOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowSalesTaxChange](#AllowSalesTaxChange)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTenderDeclaration](#AllowTenderDeclaration)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTransactionSuspension](#AllowTransactionSuspension)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTransactionVoiding](#AllowTransactionVoiding)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowXReportPrinting](#AllowXReportPrinting)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowZReportPrinting](#AllowZReportPrinting)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[ManageDevice](#ManageDevice)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[ManagerPrivileges](#ManagerPrivileges)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumDiscountPercentage](#MaximumDiscountPercentage)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumLineDiscountAmount](#MaximumLineDiscountAmount)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumLineReturnAmount](#MaximumLineReturnAmount)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumTotalDiscountAmount](#MaximumTotalDiscountAmount)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumDiscountTotalPercentage](#MaximumDiscountTotalPercentage)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[MaximumTotalReturnAmount](#MaximumTotalReturnAmount)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[Description](#Description)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[StoreInventoryUser](#StoreInventoryUser)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[ViewTimeclockEntries](#ViewTimeclockEntries)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowManageSharedShift](#AllowManageSharedShift)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTheSetupOfALabelPrinter](#AllowTheSetupOfALabelPrinter)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowUseSharedShift](#AllowUseSharedShift)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[PositionId](#PositionId)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[PosPermissionGroupId](#PosPermissionGroupId)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTaskGuides](#AllowTaskGuides)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowSaleOutsideAssortment](#AllowSaleOutsideAssortment)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowPrintingReceiptCopy](#AllowPrintingReceiptCopy)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowSkipFiscalRegistration](#AllowSkipFiscalRegistration)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowCreateTransferOrder](#AllowCreateTransferOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowAcceptOrder](#AllowAcceptOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowRejectOrder](#AllowRejectOrder)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowMassActivation](#AllowMassActivation)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowSkipRegistrationOrMarkAsRegistered](#AllowSkipRegistrationOrMarkAsRegistered)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowSkipHealthCheckError](#AllowSkipHealthCheckError)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[AllowTaskManagement](#AllowTaskManagement)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[Relationship_RetailPosPermissionGroupEntityRelationshipId](#Relationship_RetailPosPermissionGroupEntityRelationshipId)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|
|[BackingTable_RetailPositionPosPermissionRelationshipId](#BackingTable_RetailPositionPosPermissionRelationshipId)||<a href="RetailPositionPosPermissionEntity.md" target="_blank">BrickAndMortarStore/RetailPositionPosPermissionEntity</a>|

### <a href=#AllowBlindClose name="AllowBlindClose">AllowBlindClose</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowChangePeripheralStation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowCreateOrder name="AllowCreateOrder">AllowCreateOrder</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#AllowFloatingDeclaration name="AllowFloatingDeclaration">AllowFloatingDeclaration</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowFloatingDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowKitDisassembly name="AllowKitDisassembly">AllowKitDisassembly</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#AllowMultipleLogons name="AllowMultipleLogons">AllowMultipleLogons</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMultipleLogons attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowMultipleShiftLogon name="AllowMultipleShiftLogon">AllowMultipleShiftLogon</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#OpenDrawerWithoutSale name="OpenDrawerWithoutSale">OpenDrawerWithoutSale</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenDrawerWithoutSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPasswordChange name="AllowPasswordChange">AllowPasswordChange</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPasswordChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowPriceOverride name="AllowPriceOverride">AllowPriceOverride</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowResetPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowRetrieveOrder name="AllowRetrieveOrder">AllowRetrieveOrder</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#MaximumDiscountPercentage name="MaximumDiscountPercentage">MaximumDiscountPercentage</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLineDiscountAmount name="MaximumLineDiscountAmount">MaximumLineDiscountAmount</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLineReturnAmount name="MaximumLineReturnAmount">MaximumLineReturnAmount</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLineReturnAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumTotalDiscountAmount name="MaximumTotalDiscountAmount">MaximumTotalDiscountAmount</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumDiscountTotalPercentage name="MaximumDiscountTotalPercentage">MaximumDiscountTotalPercentage</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumDiscountTotalPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumTotalReturnAmount name="MaximumTotalReturnAmount">MaximumTotalReturnAmount</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTotalReturnAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreInventoryUser name="StoreInventoryUser">StoreInventoryUser</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreInventoryUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViewTimeclockEntries name="ViewTimeclockEntries">ViewTimeclockEntries</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewTimeclockEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowManageSharedShift name="AllowManageSharedShift">AllowManageSharedShift</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowManageSharedShift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowTheSetupOfALabelPrinter name="AllowTheSetupOfALabelPrinter">AllowTheSetupOfALabelPrinter</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTheSetupOfALabelPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowUseSharedShift name="AllowUseSharedShift">AllowUseSharedShift</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowUseSharedShift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosPermissionGroupId name="PosPermissionGroupId">PosPermissionGroupId</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#AllowTaskGuides name="AllowTaskGuides">AllowTaskGuides</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

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

### <a href=#Relationship_RetailPosPermissionGroupEntityRelationshipId name="Relationship_RetailPosPermissionGroupEntityRelationshipId">Relationship_RetailPosPermissionGroupEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPosPermissionGroupEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailPositionPosPermissionRelationshipId name="BackingTable_RetailPositionPosPermissionRelationshipId">BackingTable_RetailPositionPosPermissionRelationshipId</a>

First included in: BrickAndMortarStore/RetailPositionPosPermissionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailPositionPosPermissionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPositionPosPermission.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPositionPosPermission.cdm.json/RetailPositionPosPermission</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailPositionPosPermission.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
