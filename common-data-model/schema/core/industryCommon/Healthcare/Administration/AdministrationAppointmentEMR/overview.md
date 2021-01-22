---
title: overview of AdministrationAppointmentEMR - Common Data Model | Microsoft Docs
description: AdministrationAppointmentEMR is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of AdministrationAppointmentEMR

CDM standard entities for 'AdministrationAppointmentEMR'  

## Entities

|Name|Description|
|---|---|
|[AppointmentEMRIndication](AppointmentEMRIndication.md)|Reason the appointment has been scheduled to take place, as specified using information from another entity. The indication will typically be a Condition or a Procedure|
|[AppointmentEMRParticipant](AppointmentEMRParticipant.md)|List of participants involved in the appointment.|
|[AppointmentEMRReason](AppointmentEMRReason.md)|The reason that this appointment is being scheduled. This is more clinical than administrative.|
|[AppointmentEMRReferralRequest](AppointmentEMRReferralRequest.md)|The referral request this appointment is allocated to assess (incoming referral).|
|[AppointmentEMRRequestedPeriod](AppointmentEMRRequestedPeriod.md)|A set of date ranges (potentially including times) that the appointment is preferred to be scheduled within.|
|[AppointmentEMRServiceType](AppointmentEMRServiceType.md)|The specific service that is to be performed during this appointment.s|
|[AppointmentEMRSlot](AppointmentEMRSlot.md)|The slots from the participants' schedules that will be filled by the appointment.|
|[AppointmentEMRSpecialty](AppointmentEMRSpecialty.md)|The specialty of a practitioner that would be required to perform the service requested in this appointment.|
|[AppointmentServiceCategory](AppointmentServiceCategory.md)|A broad categorization of the service that is to be performed during this appointment.|
|[ScheduleActor](ScheduleActor.md)|The specialty of a practitioner that would be required to perform the service requested in this appointment.|
|[ScheduleServiceType](ScheduleServiceType.md)|The specific service that is to be performed during this appointment.|
|[ScheduleSpecialty](ScheduleSpecialty.md)|A container for slots of time that may be available for booking appointments.|
|[Slot](Slot.md)|A slot of time on a schedule that may be available for booking appointments.|
|[SlotServiceType](SlotServiceType.md)|The type of appointments that can be booked into this slot. If provided then this overrides the value provided on the availability resource.|
|[SlotSpecialty](SlotSpecialty.md)|The specialty of a practitioner that would be required to perform the service requested in this appointment.|
