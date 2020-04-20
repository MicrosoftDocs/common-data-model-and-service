---
title: RetailPositionPosPermission - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailPositionPosPermission

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Group/RetailPositionPosPermission.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPositionPosPermission/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowBlindClose](#AllowBlindClose)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowChangeNoVoid](#allowChangeNoVoid)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowChangePeripheralStation](#allowChangePeripheralStation)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowCreateOrder](#allowCreateOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowDifferentPaymentMethodRefunds_RU](#AllowDifferentPaymentMethodRefunds_RU)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowEditOrder](#allowEditOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowFloatingTenderDeclaration](#allowFloatingTenderDeclaration)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowKitDisassembly](#allowKitDisassembly)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowMultipleLogins](#allowMultipleLogins)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowMultipleShiftLogon](#allowMultipleShiftLogon)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowNotSameDateReturn_RU](#AllowNotSameDateReturn_RU)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowOpenDrawerOnly](#allowOpenDrawerOnly)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowPasswordChange](#AllowPasswordChange)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowPriceOverride](#allowPriceOverride)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowResetPassword](#AllowResetPassword)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowRetrieveOrder](#allowRetrieveOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowReturnOfNonReturnableItem_RU](#AllowReturnOfNonReturnableItem_RU)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowSalesTaxChange](#allowSalesTaxChange)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowTenderDeclaration](#allowTenderDeclaration)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowTransactionSuspension](#allowTransactionSuspension)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowTransactionVoiding](#allowTransactionVoiding)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowXReportPrinting](#allowXReportPrinting)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowZReportPrinting](#AllowZReportPrinting)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[manageDevice](#manageDevice)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[managerPrivileges](#managerPrivileges)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maximumDiscountPct](#maximumDiscountPct)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maxLineDiscountAmount](#maxLineDiscountAmount)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maxLineReturnAmount](#maxLineReturnAmount)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maxTotalDiscountAmount](#maxTotalDiscountAmount)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maxTotalDiscountPct](#maxTotalDiscountPct)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[maxTotalReturnAmount](#maxTotalReturnAmount)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[name](#name)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[Position](#Position)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[PosPermissionGroup](#PosPermissionGroup)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[UseHandheld](#UseHandheld)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[viewTimeclockEntries](#viewTimeclockEntries)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowManageSharedShift](#allowManageSharedShift)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowSetupLabelPrinter](#AllowSetupLabelPrinter)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[allowUseSharedShift](#allowUseSharedShift)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowTaskGuides](#AllowTaskGuides)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowSaleOutsideAssortment](#AllowSaleOutsideAssortment)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowPrintingReceiptCopy](#AllowPrintingReceiptCopy)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowSkipFiscalRegistration](#AllowSkipFiscalRegistration)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowCreateTransferOrder](#AllowCreateTransferOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowAcceptOrder](#AllowAcceptOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowRejectOrder](#AllowRejectOrder)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowMassActivation](#AllowMassActivation)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowSkipRegistrationOrMarkAsRegistered](#AllowSkipRegistrationOrMarkAsRegistered)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowSkipHealthCheckError](#AllowSkipHealthCheckError)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[AllowTaskManagement](#AllowTaskManagement)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|
|[Relationship_RetailPosPermissionGroupRelationshipId](#Relationship_RetailPosPermissionGroupRelationshipId)||<a href="RetailPositionPosPermission.md" target="_blank">Group/RetailPositionPosPermission</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPositionPosPermission/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowBlindClose name="AllowBlindClose">AllowBlindClose</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowBlindClose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowChangeNoVoid name="allowChangeNoVoid">allowChangeNoVoid</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowChangeNoVoid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowChangePeripheralStation name="allowChangePeripheralStation">allowChangePeripheralStation</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowChangePeripheralStation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowCreateOrder name="allowCreateOrder">allowCreateOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowCreateOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowDifferentPaymentMethodRefunds_RU name="AllowDifferentPaymentMethodRefunds_RU">AllowDifferentPaymentMethodRefunds_RU</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowDifferentPaymentMethodRefunds_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowEditOrder name="allowEditOrder">allowEditOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowEditOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowFloatingTenderDeclaration name="allowFloatingTenderDeclaration">allowFloatingTenderDeclaration</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowFloatingTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowKitDisassembly name="allowKitDisassembly">allowKitDisassembly</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowKitDisassembly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowMultipleLogins name="allowMultipleLogins">allowMultipleLogins</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowMultipleLogins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowMultipleShiftLogon name="allowMultipleShiftLogon">allowMultipleShiftLogon</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowMultipleShiftLogon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowNotSameDateReturn_RU name="AllowNotSameDateReturn_RU">AllowNotSameDateReturn_RU</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNotSameDateReturn_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowOpenDrawerOnly name="allowOpenDrawerOnly">allowOpenDrawerOnly</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowOpenDrawerOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowPasswordChange name="AllowPasswordChange">AllowPasswordChange</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPasswordChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowPriceOverride name="allowPriceOverride">allowPriceOverride</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowPriceOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowResetPassword name="AllowResetPassword">AllowResetPassword</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowResetPassword attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowRetrieveOrder name="allowRetrieveOrder">allowRetrieveOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowRetrieveOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowReturnOfNonReturnableItem_RU name="AllowReturnOfNonReturnableItem_RU">AllowReturnOfNonReturnableItem_RU</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowReturnOfNonReturnableItem_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowSalesTaxChange name="allowSalesTaxChange">allowSalesTaxChange</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowSalesTaxChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTenderDeclaration name="allowTenderDeclaration">allowTenderDeclaration</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTransactionSuspension name="allowTransactionSuspension">allowTransactionSuspension</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTransactionSuspension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTransactionVoiding name="allowTransactionVoiding">allowTransactionVoiding</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTransactionVoiding attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowXReportPrinting name="allowXReportPrinting">allowXReportPrinting</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowXReportPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowZReportPrinting name="AllowZReportPrinting">AllowZReportPrinting</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowZReportPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#manageDevice name="manageDevice">manageDevice</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the manageDevice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#managerPrivileges name="managerPrivileges">managerPrivileges</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the managerPrivileges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#maximumDiscountPct name="maximumDiscountPct">maximumDiscountPct</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumDiscountPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxLineDiscountAmount name="maxLineDiscountAmount">maxLineDiscountAmount</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxLineReturnAmount name="maxLineReturnAmount">maxLineReturnAmount</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxLineReturnAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTotalDiscountAmount name="maxTotalDiscountAmount">maxTotalDiscountAmount</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTotalDiscountPct name="maxTotalDiscountPct">maxTotalDiscountPct</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTotalDiscountPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTotalReturnAmount name="maxTotalReturnAmount">maxTotalReturnAmount</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTotalReturnAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#name name="name">name</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PosPermissionGroup name="PosPermissionGroup">PosPermissionGroup</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosPermissionGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UseHandheld name="UseHandheld">UseHandheld</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseHandheld attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#viewTimeclockEntries name="viewTimeclockEntries">viewTimeclockEntries</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the viewTimeclockEntries attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowManageSharedShift name="allowManageSharedShift">allowManageSharedShift</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowManageSharedShift attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSetupLabelPrinter name="AllowSetupLabelPrinter">AllowSetupLabelPrinter</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSetupLabelPrinter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowUseSharedShift name="allowUseSharedShift">allowUseSharedShift</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowUseSharedShift attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowTaskGuides name="AllowTaskGuides">AllowTaskGuides</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTaskGuides attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSaleOutsideAssortment name="AllowSaleOutsideAssortment">AllowSaleOutsideAssortment</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSaleOutsideAssortment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowPrintingReceiptCopy name="AllowPrintingReceiptCopy">AllowPrintingReceiptCopy</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPrintingReceiptCopy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSkipFiscalRegistration name="AllowSkipFiscalRegistration">AllowSkipFiscalRegistration</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipFiscalRegistration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowCreateTransferOrder name="AllowCreateTransferOrder">AllowCreateTransferOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCreateTransferOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowAcceptOrder name="AllowAcceptOrder">AllowAcceptOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAcceptOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowRejectOrder name="AllowRejectOrder">AllowRejectOrder</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRejectOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowMassActivation name="AllowMassActivation">AllowMassActivation</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowMassActivation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSkipRegistrationOrMarkAsRegistered name="AllowSkipRegistrationOrMarkAsRegistered">AllowSkipRegistrationOrMarkAsRegistered</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipRegistrationOrMarkAsRegistered attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSkipHealthCheckError name="AllowSkipHealthCheckError">AllowSkipHealthCheckError</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipHealthCheckError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowTaskManagement name="AllowTaskManagement">AllowTaskManagement</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTaskManagement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailPosPermissionGroupRelationshipId name="Relationship_RetailPosPermissionGroupRelationshipId">Relationship_RetailPosPermissionGroupRelationshipId</a>

First included in: Group/RetailPositionPosPermission (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPosPermissionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailPosPermissionGroup.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailPosPermissionGroup.cdm.json/RetailPosPermissionGroup</a></td><td><a href="RetailPosPermissionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
