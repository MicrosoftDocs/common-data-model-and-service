---
title: overview of Commoncore - Common Data Model | Microsoft Docs
description: Commoncore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of Commoncore

CDM standard entities for 'Commoncore'  

## Entities

|Name|Description|
|---|---|
|[AccountType](AccountType.md)||
|[ActivityDefinition](ActivityDefinition.md)|This entity allows for the definition of some activity to be performed, independent of a particular patient, practitioner, or other performance context.|
|[AppointmentEMR](AppointmentEMR.md)|A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s).|
|[CarePlan](CarePlan.md)|Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition|
|[CareTeam](CareTeam.md)|The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care for a patient.|
|[CodeableConcept](CodeableConcept.md)|A Codeable Concept represents a value that is usually supplied by providing a reference to one or more terminologies, but may also be defined by the provision of text.|
|[CommunicationRequest](CommunicationRequest.md)|A request to convey information.|
|[Condition](Condition.md)|A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern.|
|[DataRequirement](DataRequirement.md)|Describes a required data item for evaluation in terms of the type of data, and optional code or date-based filters of the data.|
|[Device](Device.md)|This entity identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|
|[DeviceComponent](DeviceComponent.md)|The characteristics, operational status and capabilities of a medical-related component of a medical device.|
|[DeviceMetric](DeviceMetric.md)|Describes a measurement, calculation or setting capability of a medical device.|
|[DeviceRequest](DeviceRequest.md)|Represents a request for a patient to employ a medical device. The device may be an implantable device, or an external assistive device, such as a walker.|
|[Dosage](Dosage.md)|Indicates how the medication is/was taken or should be taken by the patient.|
|[DosageAddInstruction](DosageAddInstruction.md)|Additional instruction such as "Swallow with plenty of water" which may or may not be coded.|
|[Encounter](Encounter.md)|An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.|
|[Endpoint](Endpoint.md)|The technical details of an endpoint that can be used for electronic services.This may include any security context information.|
|[EpisodeOfCare](EpisodeOfCare.md)|An association between a patient and an organization / healthcare provider(s) during which time encounters may occur.|
|[Goal](Goal.md)|Describes the intended objective(s) for a patient, group or organization care|
|[HealthcareService](HealthcareService.md)|The details of a healthcare service available at a location.|
|[Location](Location.md)|Details and position information for a physical place where services are provided and resources and participants may be stored, found, contained or accommodated.|
|[LocationEndPoint](LocationEndPoint.md)|Technical endpoints providing access to services operated for the location.|
|[LocationTelecom](LocationTelecom.md)|The contact details of communication devices available at the location. This can include phone numbers, fax numbers, mobile numbers, email addresses and web sites.|
|[Medication](Medication.md)|Medications|
|[MedicationAdministration](MedicationAdministration.md)|Describes the event of a patient consuming or otherwise being administered a medication.|
|[MedicationRequest](MedicationRequest.md)|An order or request for both supply of the medication and the instructions for administration of the medication to a patient.|
|[NutritionOrder](NutritionOrder.md)|A request to supply a diet, formula feeding (eternal) or oral nutritional supplement to a patient/resident.|
|[Observation](Observation.md)|Measurements and simple assertions made about a patient, device or other subject.|
|[PlanDefinition](PlanDefinition.md)|This entity allows for the definition of various types of plans as a shareable, consumable, and executable artifact.|
|[PractitionerRole](PractitionerRole.md)|A specific set of Roles/Locations/specialties/services that a practitioner may perform at an organization for a period of time.|
|[Procedure](Procedure.md)|An action that is or was performed on a patient. This can be a physical intervention like an operation, or less invasive like counseling or hypnotherapy.|
|[ProcedureRequest](ProcedureRequest.md)|A record of a request for diagnostic investigations, treatments, or operations to be performed.|
|[ReferralRequest](ReferralRequest.md)|Used to record and send details about a request for referral service or transfer of a patient to the care of another provider or provider organization.|
|[RelatedPerson](RelatedPerson.md)|Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process.|
|[RequestGroup](RequestGroup.md)|A group of related requests that can be used to capture intended activities that have inter-dependencies such as "give this medication after that one".|
|[Schedule](Schedule.md)|A container for slots of time that may be available for booking appointments.|
|[Specimen](Specimen.md)|A sample to be used for analysis.|
|[Substance](Substance.md)|A homogeneous material with a definite composition.|
|[Timing](Timing.md)|Specifies an event that may occur multiple times. Timing schedules are used to record when things are planned, expected or requested to occur.|
|[TimingDayOfWeek](TimingDayOfWeek.md)|If one or more days of week is provided, then the action happens only on the specified day(s).|
|[TimingEvent](TimingEvent.md)|Identifies specific times when the event occurs.|
|[TimingTimeOfDay](TimingTimeOfDay.md)|Specified time of day for action to take place.|
|[TimingWhen](TimingWhen.md)|Real world events that the occurrence of the event should be tied to.|
|[VisionPrescription](VisionPrescription.md)|An authorization for the supply of glasses and/or contact lenses to a patient.|
