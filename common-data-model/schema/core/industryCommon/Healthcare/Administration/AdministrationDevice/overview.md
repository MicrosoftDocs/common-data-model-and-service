---
title: overview of AdministrationDevice - Common Data Model | Microsoft Docs
description: AdministrationDevice is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of AdministrationDevice

CDM standard entities for 'AdministrationDevice'  

## Entities

|Name|Description|
|---|---|
|[DeviceCalibration](DeviceCalibration.md)|Describes the calibrations that have been performed or that are required to be performed.|
|[DeviceComponentOperationalStatus](DeviceComponentOperationalStatus.md)|The current operational status of the device. For example: On, Off, Standby, etc.|
|[DeviceComponentProductionSpecification](DeviceComponentProductionSpecification.md)|The production specification such as component revision, serial number, etc.|
|[DeviceContactPoint](DeviceContactPoint.md)|Contact details for an organization or a particular human that is responsible for the device.|
|[DeviceMetricType](DeviceMetricType.md)|Describes the type of the metric. For example: Heart Rate, PEEP Setting, etc.|
|[DeviceRequestBasedOn](DeviceRequestBasedOn.md)|Plan/proposal/order fulfilled by this request.|
|[DeviceRequestDefinition](DeviceRequestDefinition.md)|Protocol or definition followed by this request.|
|[DeviceRequestPriorRequest](DeviceRequestPriorRequest.md)|The request takes the place of the referenced completed or terminated request(s).|
|[DeviceRequestReasonCode](DeviceRequestReasonCode.md)|Reason or justification for the use of this device.|
|[DeviceRequestReasonReference](DeviceRequestReasonReference.md)|Reason or justification for the use of this device.|
|[DeviceRequestRelevantHistory](DeviceRequestRelevantHistory.md)|Key events in the history of the request.|
|[DeviceRequestSupportingInfo](DeviceRequestSupportingInfo.md)|Additional clinical information about the patient that may influence the request fulfillment. For example, this may includes body where on the subject's the device will be used.|
|[DeviceSafety](DeviceSafety.md)|Provides additional safety characteristics about a medical device. For example devices containing latex.|
|[DeviceStatus](DeviceStatus.md)||
