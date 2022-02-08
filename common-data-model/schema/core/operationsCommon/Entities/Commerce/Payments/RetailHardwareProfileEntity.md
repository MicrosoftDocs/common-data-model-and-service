---
title: RetailHardwareProfileEntity in Payments - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS hardware profiles in Payments(RetailHardwareProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Payments/RetailHardwareProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS hardware profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CaptureExtraData](#CaptureExtraData)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[CashChanger](#CashChanger)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[CashChangerInitialSettings](#CashChangerInitialSettings)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[CashChangerPortSettings](#CashChangerPortSettings)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ClosedCaptionTelevision](#ClosedCaptionTelevision)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ClosedCaptionTelevisionCamera](#ClosedCaptionTelevisionCamera)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ClosedCaptionTelevisionHostName](#ClosedCaptionTelevisionHostName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ClosedCaptionTelevisionPort](#ClosedCaptionTelevisionPort)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DelayForLinkedItems](#DelayForLinkedItems)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DeviceDescription](#DeviceDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DeviceName](#DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayBalanceText](#DisplayBalanceText)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayBinaryConversion](#DisplayBinaryConversion)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayCharacterSet](#DisplayCharacterSet)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayClosedLine1](#DisplayClosedLine1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayClosedLine2](#DisplayClosedLine2)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayDescription](#DisplayDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayDevice](#DisplayDevice)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayDeviceName](#DisplayDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayLinkedItem](#DisplayLinkedItem)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayTerminalClosed](#DisplayTerminalClosed)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DisplayTotalText](#DisplayTotalText)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1DocumentInsertRemovalTimeout](#Printer1DocumentInsertRemovalTimeout)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1](#Drawer1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2](#Drawer2)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2Description](#Drawer2Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2DeviceName](#Drawer2DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2Make](#Drawer2Make)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2Model](#Drawer2Model)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1Description](#Drawer1Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1DeviceName](#Drawer1DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1Make](#Drawer1Make)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1Model](#Drawer1Model)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplay](#DualDisplay)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplayBrowserUrl](#DualDisplayBrowserUrl)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplayImageInterval](#DualDisplayImageInterval)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplayImagePath](#DualDisplayImagePath)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplayReceiptPercentage](#DualDisplayReceiptPercentage)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[DualDisplayType](#DualDisplayType)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransfer](#ElectronicFundsTransfer)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferCompanyId](#ElectronicFundsTransferCompanyId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferConfiguration](#ElectronicFundsTransferConfiguration)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferConnectorName](#ElectronicFundsTransferConnectorName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferConnectorProperties](#ElectronicFundsTransferConnectorProperties)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferData](#ElectronicFundsTransferData)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferDescription](#ElectronicFundsTransferDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferMerchantId](#ElectronicFundsTransferMerchantId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferPassword](#ElectronicFundsTransferPassword)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferServerName](#ElectronicFundsTransferServerName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferServerPort](#ElectronicFundsTransferServerPort)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferUserId](#ElectronicFundsTransferUserId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderEndTrack1Sentinel](#MagneticStripeReaderEndTrack1Sentinel)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderEndTrack2Sentinel](#MagneticStripeReaderEndTrack2Sentinel)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalPrinter](#FiscalPrinter)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalPrinterDescription](#FiscalPrinterDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalPrinterDeviceName](#FiscalPrinterDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FormXPosition](#FormXPosition)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FormYPosition](#FormYPosition)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[HardTotal](#HardTotal)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[HardTotalDescription](#HardTotalDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[HardTotalDeviceName](#HardTotalDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ImagePath](#ImagePath)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[KeyboardMappingId](#KeyboardMappingId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Keylock](#Keylock)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[KeylockDescription](#KeylockDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[KeylockDeviceName](#KeylockDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Logo](#Logo)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[LogoAlignment](#LogoAlignment)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[LogoBitmap](#LogoBitmap)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[IsManualInputAllowed](#IsManualInputAllowed)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MaxInvoiceLines](#MaxInvoiceLines)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticInkCharacterRecognition](#MagneticInkCharacterRecognition)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticInkCharacterRecognitionDescription](#MagneticInkCharacterRecognitionDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticInkCharacterRecognitionDriverName](#MagneticInkCharacterRecognitionDriverName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReader](#MagneticStripeReader)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderDescription](#MagneticStripeReaderDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderDeviceName](#MagneticStripeReaderDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderMake](#MagneticStripeReaderMake)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderModel](#MagneticStripeReaderModel)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Name](#Name)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Pharmacy](#Pharmacy)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PharmacyHost](#PharmacyHost)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PharmacyPort](#PharmacyPort)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PinPad](#PinPad)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PinPadDescription](#PinPadDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PinPadDeviceName](#PinPadDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PinPadMake](#PinPadMake)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PinPadModel](#PinPadModel)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[PrintBinaryConversion](#PrintBinaryConversion)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1](#Printer1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2](#Printer2)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2BinaryConversion](#Printer2BinaryConversion)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2Characterset](#Printer2Characterset)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2Description](#Printer2Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2DeviceName](#Printer2DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2DocumentInsertRemovalTimeout](#Printer2DocumentInsertRemovalTimeout)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2Logo](#Printer2Logo)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2LogoAlignment](#Printer2LogoAlignment)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2LogoBitmap](#Printer2LogoBitmap)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2Make](#Printer2Make)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2Model](#Printer2Model)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer2ReceiptProfileId](#Printer2ReceiptProfileId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1Characterset](#Printer1Characterset)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1Description](#Printer1Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1DeviceName](#Printer1DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1Make](#Printer1Make)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1Model](#Printer1Model)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Printer1ReceiptProfileId](#Printer1ReceiptProfileId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ProfileId](#ProfileId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ProfileVersion](#ProfileVersion)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[RadioFrequencyIdDescription](#RadioFrequencyIdDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[RadioFrequencyIdDeviceName](#RadioFrequencyIdDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[RadioFrequencyIdScannerType](#RadioFrequencyIdScannerType)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scale](#Scale)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ScaleDescription](#ScaleDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ScaleDeviceName](#ScaleDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner1](#Scanner1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner2](#Scanner2)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner2Description](#Scanner2Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner2DeviceName](#Scanner2DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner1Description](#Scanner1Description)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner1DeviceName](#Scanner1DeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ScreenKeyboard](#ScreenKeyboard)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderSeparator1](#MagneticStripeReaderSeparator1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ShowPicture](#ShowPicture)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCapture](#SignatureCapture)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCaptureDescription](#SignatureCaptureDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCaptureDeviceName](#SignatureCaptureDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCaptureFormName](#SignatureCaptureFormName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCaptureMake](#SignatureCaptureMake)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[SignatureCaptureModel](#SignatureCaptureModel)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderStartTrack1](#MagneticStripeReaderStartTrack1)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MagneticStripeReaderStartTrack2After](#MagneticStripeReaderStartTrack2After)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[TimeoutInSec](#TimeoutInSec)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[UseElectronicFundsTransferService](#UseElectronicFundsTransferService)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[UseExternalPaymentsDevice](#UseExternalPaymentsDevice)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2DevicePool](#Drawer2DevicePool)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer2UseCashDrawerPool](#Drawer2UseCashDrawerPool)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1DevicePool](#Drawer1DevicePool)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Drawer1UseCashDrawerPool](#Drawer1UseCashDrawerPool)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[ElectronicFundsTransferMaximumCardPayments](#ElectronicFundsTransferMaximumCardPayments)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalPrinterConfigId](#FiscalPrinterConfigId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalRegister](#FiscalRegister)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalRegisterConfigId](#FiscalRegisterConfigId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalRegisterDescription](#FiscalRegisterDescription)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[FiscalRegisterDeviceName](#FiscalRegisterDeviceName)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner2DecodeScanData](#Scanner2DecodeScanData)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[Scanner1DecodeScanData](#Scanner1DecodeScanData)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[MergedSelfServicePackageReference](#MergedSelfServicePackageReference)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|
|[BackingTable_RetailHardwareProfileRelationshipId](#BackingTable_RetailHardwareProfileRelationshipId)||<a href="RetailHardwareProfileEntity.md" target="_blank">Payments/RetailHardwareProfileEntity</a>|

### <a href=#CaptureExtraData name="CaptureExtraData">CaptureExtraData</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaptureExtraData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashChanger name="CashChanger">CashChanger</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashChanger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashChangerInitialSettings name="CashChangerInitialSettings">CashChangerInitialSettings</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashChangerInitialSettings attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashChangerPortSettings name="CashChangerPortSettings">CashChangerPortSettings</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashChangerPortSettings attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedCaptionTelevision name="ClosedCaptionTelevision">ClosedCaptionTelevision</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedCaptionTelevision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedCaptionTelevisionCamera name="ClosedCaptionTelevisionCamera">ClosedCaptionTelevisionCamera</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedCaptionTelevisionCamera attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedCaptionTelevisionHostName name="ClosedCaptionTelevisionHostName">ClosedCaptionTelevisionHostName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedCaptionTelevisionHostName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedCaptionTelevisionPort name="ClosedCaptionTelevisionPort">ClosedCaptionTelevisionPort</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedCaptionTelevisionPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DelayForLinkedItems name="DelayForLinkedItems">DelayForLinkedItems</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DelayForLinkedItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceDescription name="DeviceDescription">DeviceDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceName name="DeviceName">DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayBalanceText name="DisplayBalanceText">DisplayBalanceText</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayBalanceText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayBinaryConversion name="DisplayBinaryConversion">DisplayBinaryConversion</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayBinaryConversion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayCharacterSet name="DisplayCharacterSet">DisplayCharacterSet</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayCharacterSet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayClosedLine1 name="DisplayClosedLine1">DisplayClosedLine1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayClosedLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayClosedLine2 name="DisplayClosedLine2">DisplayClosedLine2</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayClosedLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayDescription name="DisplayDescription">DisplayDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayDevice name="DisplayDevice">DisplayDevice</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayDevice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayDeviceName name="DisplayDeviceName">DisplayDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayLinkedItem name="DisplayLinkedItem">DisplayLinkedItem</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayLinkedItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayTerminalClosed name="DisplayTerminalClosed">DisplayTerminalClosed</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTerminalClosed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayTotalText name="DisplayTotalText">DisplayTotalText</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTotalText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1DocumentInsertRemovalTimeout name="Printer1DocumentInsertRemovalTimeout">Printer1DocumentInsertRemovalTimeout</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1DocumentInsertRemovalTimeout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1 name="Drawer1">Drawer1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2 name="Drawer2">Drawer2</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2Description name="Drawer2Description">Drawer2Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2DeviceName name="Drawer2DeviceName">Drawer2DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2Make name="Drawer2Make">Drawer2Make</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2Model name="Drawer2Model">Drawer2Model</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1Description name="Drawer1Description">Drawer1Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1DeviceName name="Drawer1DeviceName">Drawer1DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1Make name="Drawer1Make">Drawer1Make</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1Model name="Drawer1Model">Drawer1Model</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplay name="DualDisplay">DualDisplay</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplayBrowserUrl name="DualDisplayBrowserUrl">DualDisplayBrowserUrl</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplayBrowserUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplayImageInterval name="DualDisplayImageInterval">DualDisplayImageInterval</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplayImageInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplayImagePath name="DualDisplayImagePath">DualDisplayImagePath</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplayImagePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplayReceiptPercentage name="DualDisplayReceiptPercentage">DualDisplayReceiptPercentage</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplayReceiptPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DualDisplayType name="DualDisplayType">DualDisplayType</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DualDisplayType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransfer name="ElectronicFundsTransfer">ElectronicFundsTransfer</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransfer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferCompanyId name="ElectronicFundsTransferCompanyId">ElectronicFundsTransferCompanyId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferConfiguration name="ElectronicFundsTransferConfiguration">ElectronicFundsTransferConfiguration</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferConnectorName name="ElectronicFundsTransferConnectorName">ElectronicFundsTransferConnectorName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferConnectorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferConnectorProperties name="ElectronicFundsTransferConnectorProperties">ElectronicFundsTransferConnectorProperties</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferConnectorProperties attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferData name="ElectronicFundsTransferData">ElectronicFundsTransferData</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferDescription name="ElectronicFundsTransferDescription">ElectronicFundsTransferDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferMerchantId name="ElectronicFundsTransferMerchantId">ElectronicFundsTransferMerchantId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferMerchantId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferPassword name="ElectronicFundsTransferPassword">ElectronicFundsTransferPassword</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferServerName name="ElectronicFundsTransferServerName">ElectronicFundsTransferServerName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferServerPort name="ElectronicFundsTransferServerPort">ElectronicFundsTransferServerPort</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferServerPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferUserId name="ElectronicFundsTransferUserId">ElectronicFundsTransferUserId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderEndTrack1Sentinel name="MagneticStripeReaderEndTrack1Sentinel">MagneticStripeReaderEndTrack1Sentinel</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderEndTrack1Sentinel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderEndTrack2Sentinel name="MagneticStripeReaderEndTrack2Sentinel">MagneticStripeReaderEndTrack2Sentinel</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderEndTrack2Sentinel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinter name="FiscalPrinter">FiscalPrinter</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterDescription name="FiscalPrinterDescription">FiscalPrinterDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterDeviceName name="FiscalPrinterDeviceName">FiscalPrinterDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormXPosition name="FormXPosition">FormXPosition</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormXPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormYPosition name="FormYPosition">FormYPosition</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormYPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardTotal name="HardTotal">HardTotal</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardTotalDescription name="HardTotalDescription">HardTotalDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardTotalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardTotalDeviceName name="HardTotalDeviceName">HardTotalDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardTotalDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImagePath name="ImagePath">ImagePath</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImagePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyboardMappingId name="KeyboardMappingId">KeyboardMappingId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyboardMappingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Keylock name="Keylock">Keylock</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Keylock attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeylockDescription name="KeylockDescription">KeylockDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeylockDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeylockDeviceName name="KeylockDeviceName">KeylockDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeylockDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Logo name="Logo">Logo</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Logo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogoAlignment name="LogoAlignment">LogoAlignment</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogoAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogoBitmap name="LogoBitmap">LogoBitmap</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogoBitmap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsManualInputAllowed name="IsManualInputAllowed">IsManualInputAllowed</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManualInputAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxInvoiceLines name="MaxInvoiceLines">MaxInvoiceLines</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInvoiceLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticInkCharacterRecognition name="MagneticInkCharacterRecognition">MagneticInkCharacterRecognition</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticInkCharacterRecognition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticInkCharacterRecognitionDescription name="MagneticInkCharacterRecognitionDescription">MagneticInkCharacterRecognitionDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticInkCharacterRecognitionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticInkCharacterRecognitionDriverName name="MagneticInkCharacterRecognitionDriverName">MagneticInkCharacterRecognitionDriverName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticInkCharacterRecognitionDriverName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReader name="MagneticStripeReader">MagneticStripeReader</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderDescription name="MagneticStripeReaderDescription">MagneticStripeReaderDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderDeviceName name="MagneticStripeReaderDeviceName">MagneticStripeReaderDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderMake name="MagneticStripeReaderMake">MagneticStripeReaderMake</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderMake attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderModel name="MagneticStripeReaderModel">MagneticStripeReaderModel</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

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

### <a href=#Pharmacy name="Pharmacy">Pharmacy</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pharmacy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PharmacyHost name="PharmacyHost">PharmacyHost</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PharmacyHost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PharmacyPort name="PharmacyPort">PharmacyPort</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PharmacyPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PinPad name="PinPad">PinPad</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PinPad attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PinPadDescription name="PinPadDescription">PinPadDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PinPadDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PinPadDeviceName name="PinPadDeviceName">PinPadDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PinPadDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PinPadMake name="PinPadMake">PinPadMake</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PinPadMake attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PinPadModel name="PinPadModel">PinPadModel</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PinPadModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBinaryConversion name="PrintBinaryConversion">PrintBinaryConversion</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBinaryConversion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1 name="Printer1">Printer1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2 name="Printer2">Printer2</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2BinaryConversion name="Printer2BinaryConversion">Printer2BinaryConversion</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2BinaryConversion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2Characterset name="Printer2Characterset">Printer2Characterset</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2Characterset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2Description name="Printer2Description">Printer2Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2DeviceName name="Printer2DeviceName">Printer2DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2DocumentInsertRemovalTimeout name="Printer2DocumentInsertRemovalTimeout">Printer2DocumentInsertRemovalTimeout</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2DocumentInsertRemovalTimeout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2Logo name="Printer2Logo">Printer2Logo</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2Logo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2LogoAlignment name="Printer2LogoAlignment">Printer2LogoAlignment</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2LogoAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2LogoBitmap name="Printer2LogoBitmap">Printer2LogoBitmap</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2LogoBitmap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2Make name="Printer2Make">Printer2Make</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2Model name="Printer2Model">Printer2Model</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer2ReceiptProfileId name="Printer2ReceiptProfileId">Printer2ReceiptProfileId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer2ReceiptProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1Characterset name="Printer1Characterset">Printer1Characterset</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1Characterset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1Description name="Printer1Description">Printer1Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1DeviceName name="Printer1DeviceName">Printer1DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1Make name="Printer1Make">Printer1Make</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1Make attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1Model name="Printer1Model">Printer1Model</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1Model attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Printer1ReceiptProfileId name="Printer1ReceiptProfileId">Printer1ReceiptProfileId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printer1ReceiptProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileVersion name="ProfileVersion">ProfileVersion</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RadioFrequencyIdDescription name="RadioFrequencyIdDescription">RadioFrequencyIdDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RadioFrequencyIdDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RadioFrequencyIdDeviceName name="RadioFrequencyIdDeviceName">RadioFrequencyIdDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RadioFrequencyIdDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RadioFrequencyIdScannerType name="RadioFrequencyIdScannerType">RadioFrequencyIdScannerType</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RadioFrequencyIdScannerType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scale name="Scale">Scale</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScaleDescription name="ScaleDescription">ScaleDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScaleDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScaleDeviceName name="ScaleDeviceName">ScaleDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScaleDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner1 name="Scanner1">Scanner1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner2 name="Scanner2">Scanner2</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner2Description name="Scanner2Description">Scanner2Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner2Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner2DeviceName name="Scanner2DeviceName">Scanner2DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner2DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner1Description name="Scanner1Description">Scanner1Description</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner1Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner1DeviceName name="Scanner1DeviceName">Scanner1DeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner1DeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScreenKeyboard name="ScreenKeyboard">ScreenKeyboard</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenKeyboard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderSeparator1 name="MagneticStripeReaderSeparator1">MagneticStripeReaderSeparator1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderSeparator1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowPicture name="ShowPicture">ShowPicture</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPicture attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCapture name="SignatureCapture">SignatureCapture</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCapture attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureDescription name="SignatureCaptureDescription">SignatureCaptureDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureDeviceName name="SignatureCaptureDeviceName">SignatureCaptureDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureFormName name="SignatureCaptureFormName">SignatureCaptureFormName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureFormName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureMake name="SignatureCaptureMake">SignatureCaptureMake</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureMake attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureModel name="SignatureCaptureModel">SignatureCaptureModel</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderStartTrack1 name="MagneticStripeReaderStartTrack1">MagneticStripeReaderStartTrack1</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderStartTrack1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MagneticStripeReaderStartTrack2After name="MagneticStripeReaderStartTrack2After">MagneticStripeReaderStartTrack2After</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MagneticStripeReaderStartTrack2After attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeoutInSec name="TimeoutInSec">TimeoutInSec</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeoutInSec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseElectronicFundsTransferService name="UseElectronicFundsTransferService">UseElectronicFundsTransferService</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseElectronicFundsTransferService attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseExternalPaymentsDevice name="UseExternalPaymentsDevice">UseExternalPaymentsDevice</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseExternalPaymentsDevice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2DevicePool name="Drawer2DevicePool">Drawer2DevicePool</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2DevicePool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer2UseCashDrawerPool name="Drawer2UseCashDrawerPool">Drawer2UseCashDrawerPool</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer2UseCashDrawerPool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1DevicePool name="Drawer1DevicePool">Drawer1DevicePool</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1DevicePool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Drawer1UseCashDrawerPool name="Drawer1UseCashDrawerPool">Drawer1UseCashDrawerPool</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Drawer1UseCashDrawerPool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicFundsTransferMaximumCardPayments name="ElectronicFundsTransferMaximumCardPayments">ElectronicFundsTransferMaximumCardPayments</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicFundsTransferMaximumCardPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterConfigId name="FiscalPrinterConfigId">FiscalPrinterConfigId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalRegister name="FiscalRegister">FiscalRegister</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalRegisterConfigId name="FiscalRegisterConfigId">FiscalRegisterConfigId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalRegisterConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalRegisterDescription name="FiscalRegisterDescription">FiscalRegisterDescription</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalRegisterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalRegisterDeviceName name="FiscalRegisterDeviceName">FiscalRegisterDeviceName</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalRegisterDeviceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner2DecodeScanData name="Scanner2DecodeScanData">Scanner2DecodeScanData</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner2DecodeScanData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Scanner1DecodeScanData name="Scanner1DecodeScanData">Scanner1DecodeScanData</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scanner1DecodeScanData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MergedSelfServicePackageReference name="MergedSelfServicePackageReference">MergedSelfServicePackageReference</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MergedSelfServicePackageReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailHardwareProfileRelationshipId name="BackingTable_RetailHardwareProfileRelationshipId">BackingTable_RetailHardwareProfileRelationshipId</a>

First included in: Payments/RetailHardwareProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailHardwareProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Payments/Group/RetailHardwareProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Payments/Group/RetailHardwareProfile.cdm.json/RetailHardwareProfile</a></td><td><a href="../../../Tables/Commerce/Payments/Group/RetailHardwareProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
