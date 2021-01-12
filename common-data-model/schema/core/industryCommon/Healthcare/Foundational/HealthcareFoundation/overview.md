---
title: overview of HealthcareFoundation - Common Data Model | Microsoft Docs
description: HealthcareFoundation is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of HealthcareFoundation

CDM standard entities for 'HealthcareFoundation'  

## Entities

|Name|Description|
|---|---|
|[AllergyIntolerance](AllergyIntolerance.md)|Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance.|
|[AppointmentEMR](AppointmentEMR.md)|A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s).|
|[CarePlan](CarePlan.md)|Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition|
|[CarePlanActivity](CarePlanActivity.md)|Identifies a planned action to occur as part of the plan. For example, a medication to be used, lab tests to perform, self-monitoring, education, etc.|
|[CarePlanActivityGoal](CarePlanActivityGoal.md)|Internal reference that identifies the goals that this activity is intended to contribute towards meeting.|
|[CarePlanGoal](CarePlanGoal.md)|Describes the intended objective(s) of carrying out the care plan.|
|[CareTeam](CareTeam.md)|The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care for a patient.|
|[CareTeamCategory](CareTeamCategory.md)|Identifies what kind of team. This is to support differentiation between multiple co-existing teams, such as care plan team, episode of care team, longitudinal care team.|
|[CareTeamManagingOrganization](CareTeamManagingOrganization.md)|The organization responsible for the care team.|
|[CareTeamParticipant](CareTeamParticipant.md)|Identifies all people and organizations who are expected to be involved in the care team.|
|[CareTeamReasonCode](CareTeamReasonCode.md)|Describes why the care team exists.|
|[CareTeamReasonReference](CareTeamReasonReference.md)|Condition(s) that this care team addresses.|
|[Condition](Condition.md)|A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern.|
|[ConditionBodySite](ConditionBodySite.md)|The anatomical location where this condition manifests itself.|
|[ConditionCategory](ConditionCategory.md)|A category assigned to the condition.|
|[ConditionEvidence](ConditionEvidence.md)|Supporting Evidence / manifestations that are the basis on which this condition is suspected or confirmed.|
|[ConditionStage](ConditionStage.md)|Clinical stage or grade of a condition. May include formal severity assessments.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|[Encounter](Encounter.md)|An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.|
|[EncounterAccount](EncounterAccount.md)|The set of accounts that may be used for billing for this Encounter.|
|[EncounterClassHistory](EncounterClassHistory.md)|The class history permits the tracking of the encounters transitions without needing to go through the entity history.|
|[EncounterDiagnosis](EncounterDiagnosis.md)|The list of diagnosis relevant to this encounter.|
|[EncounterEpisodeOfCare](EncounterEpisodeOfCare.md)|Where a specific encounter should be classified as a part of a specific episode(s) of care this field should be used.|
|[EncounterHospitalizationArrangement](EncounterHospitalizationArrangement.md)|Any special requests that have been made for this hospitalization encounter, such as the provision of specific equipment or other things.|
|[EncounterHospitalizationCourtesy](EncounterHospitalizationCourtesy.md)|Special courtesies (VIP, board member).|
|[EncounterHospitalizationDiet](EncounterHospitalizationDiet.md)|Used to track patient's diet restrictions and/or preference.|
|[EncounterLocation](EncounterLocation.md)|List of locations where the patient has been during this encounter.|
|[EncounterParticipant](EncounterParticipant.md)|The list of people responsible for providing the service.|
|[EncounterParticipantType](EncounterParticipantType.md)|The participant type indicates how an individual participates in an encounter.|
|[EncounterReason](EncounterReason.md)|Reason the encounter takes place, expressed as a code. For admissions, this can be used for a coded admission diagnosis.|
|[EncounterReferralRequest](EncounterReferralRequest.md)|The referral request this encounter satisfies (incoming referral).|
|[EncounterStatusHistory](EncounterStatusHistory.md)|The status history permits the encounter entity to contain the status history without needing to read through the historical versions of the entity, or even have the server store them|
|[EncounterType](EncounterType.md)|Specific type of encounter (e.g. e-mail consultation, surgical day-care, skilled nursing, rehabilitation).|
|[MedicationAdministration](MedicationAdministration.md)|Describes the event of a patient consuming or otherwise being administered a medication.|
|[MedicationAdministrationDefinition](MedicationAdministrationDefinition.md)|A protocol, guideline, order set or other definition that was adhered to in whole or in part by this event.|
|[MedicationAdministrationDevice](MedicationAdministrationDevice.md)|The device used in administering the medication to the patient. For example, a particular infusion pump.|
|[MedicationAdministrationEventHistory](MedicationAdministrationEventHistory.md)|A summary of the events of interest that have occurred, such as when the administration was verified.|
|[MedicationAdministrationPartOf](MedicationAdministrationPartOf.md)|A larger event of which this particular event is a component or step.|
|[MedicationAdministrationPerformer](MedicationAdministrationPerformer.md)|The individual who was responsible for giving the medication to the patient.|
|[MedicationAdministrationReasonCode](MedicationAdministrationReasonCode.md)|A code indicating why the medication was given.|
|[MedicationAdministrationReasonNotGiven](MedicationAdministrationReasonNotGiven.md)|A code indicating why the administration was not performed.|
|[MedicationAdministrationReasonReference](MedicationAdministrationReasonReference.md)|Condition or observation that supports why the medication was administered.|
|[MedicationAdministrationSupportingInformation](MedicationAdministrationSupportingInformation.md)|Additional information (for example, patient height and weight) that supports the administration of the medication.|
|[MedicationRequest](MedicationRequest.md)|An order or request for both supply of the medication and the instructions for administration of the medication to a patient.|
|[MedicationRequestBasedOn](MedicationRequestBasedOn.md)|A plan or request that is fulfilled in whole or in part by this medication request.|
|[MedicationRequestDefinition](MedicationRequestDefinition.md)|Protocol or definition followed by this request.|
|[MedicationRequestDetectedIssue](MedicationRequestDetectedIssue.md)|Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, duplicate therapy, dosage alert etc.|
|[MedicationRequestDosageInstruction](MedicationRequestDosageInstruction.md)|Indicates how the medication is to be used by the patient.|
|[MedicationRequestEventHistory](MedicationRequestEventHistory.md)|Links to Provenance records for past versions of this entity that identify key state transitions or updates that are likely to be relevant to user looking at the current version of the entity.|
|[MedicationRequestReasonCode](MedicationRequestReasonCode.md)|The reason or the indication for ordering the medication.|
|[MedicationRequestReasonReference](MedicationRequestReasonReference.md)|Condition or observation that supports why the medication was ordered.|
|[MedicationRequestSupportingInfo](MedicationRequestSupportingInfo.md)|Include additional information (for example, patient height and weight) that supports the ordering of the medication.|
|[Observation](Observation.md)|Measurements and simple assertions made about a patient, device or other subject.|
|[ObservationBasedOn](ObservationBasedOn.md)|A plan, proposal or order that is fulfilled in whole or in part by this event.|
|[ObservationCategory](ObservationCategory.md)|A code that classifies the general type of observation being made.|
|[ObservationCode](ObservationCode.md)|Describes what was observed.|
|[ObservationComponent](ObservationComponent.md)|Some observations have multiple component observations. These component observations are expressed as separate code value pairs that share the same attributes.|
|[ObservationComponentReferenceRange](ObservationComponentReferenceRange.md)|Guidance on how to interpret the value by comparison to a normal or recommended range.|
|[ObservationInterpretation](ObservationInterpretation.md)|The assessment made based on the result of the observation.|
|[ObservationMethod](ObservationMethod.md)|Indicates the mechanism used to perform the observation.|
|[ObservationPerformer](ObservationPerformer.md)|Who was responsible for asserting the observed value as "true".|
|[ObservationReferenceRange](ObservationReferenceRange.md)|Guidance on how to interpret the value by comparison to a normal or recommended range.|
|[ObservationReferenceRangeAppliesTo](ObservationReferenceRangeAppliesTo.md)|Codes to indicate the target population this reference range applies to. For example, a reference range may be based on the normal population or a particular sex or race.|
|[ObservationRelatedResource](ObservationRelatedResource.md)|A reference to another entity(usually another Observation) whose relationship is defined by the relationship type code.|
|[Procedure](Procedure.md)|An action that is or was performed on a patient. This can be a physical intervention like an operation, or less invasive like counseling or hypnotherapy.|
|[ProcedureBasedOn](ProcedureBasedOn.md)|A reference to a resource that contains details of the request for this procedure.|
|[ProcedureBodySite](ProcedureBodySite.md)|Detailed and structured anatomical location information. Multiple locations are allowed - e.g. multiple punch biopsies of a lesion.|
|[ProcedureCode](ProcedureCode.md)||
|[ProcedureComplicationDetail](ProcedureComplicationDetail.md)|Any complications that occurred during the procedure, or in the immediate post-performance period.|
|[ProcedureDefinition](ProcedureDefinition.md)|A protocol, guideline, order set or other definition that was adhered to in whole or in part by this procedure.|
|[ProcedureFocalDevice](ProcedureFocalDevice.md)|A device that is implanted, removed or otherwise manipulated (calibration, battery replacement, fitting a prosthesis, attaching a wound-vac, etc.) as a focal portion of the Procedure.|
|[ProcedureFollowUp](ProcedureFollowUp.md)|If the procedure required specific follow up - e.g. removal of sutures. The followup may be represented as a simple note.|
|[ProcedurePartOf](ProcedurePartOf.md)|A larger event of which this particular procedure is a component or step.|
|[ProcedurePerformer](ProcedurePerformer.md)|Limited to 'real' people rather than equipment.|
|[ProcedureReason](ProcedureReason.md)|The coded reason why the procedure was performed. This may be coded entity of some type, or may simply be present as text.|
|[ProcedureReasonReference](ProcedureReasonReference.md)|The condition that is the reason why the procedure was performed.|
|[ProcedureReport](ProcedureReport.md)|Procedure report could represent histology result, pathology report, surgical report, etc.|
|[ProcedureRequest](ProcedureRequest.md)|A record of a request for diagnostic investigations, treatments, or operations to be performed.|
|[ProcedureRequestBasedOn](ProcedureRequestBasedOn.md)|Plan/proposal/order fulfilled by this request.|
|[ProcedureRequestCategory](ProcedureRequestCategory.md)|A code that classifies the procedure for searching, sorting and display purposes (e.g. "Surgical Procedure").|
|[ProcedureRequestDefinition](ProcedureRequestDefinition.md)|Protocol or definition followed by this request.|
|[ProcedureRequestReasonCode](ProcedureRequestReasonCode.md)|An explanation or justification for why this diagnostic investigation is being requested in coded or textual form. This is often for billing purposes. May relate to the resources referred to in supp|
|[ProcedureRequestReasonReference](ProcedureRequestReasonReference.md)|Indicates another resource that provides a justification for why this diagnostic investigation is being requested. May relate to the resources referred to in supporting Information.|
|[ProcedureRequestRelevantHistory](ProcedureRequestRelevantHistory.md)|Key events in the history of the request.|
|[ProcedureRequestReplace](ProcedureRequestReplace.md)|The request takes the place of the referenced completed or terminated request(s).|
|[ProcedureRequestSpecimen](ProcedureRequestSpecimen.md)|One or more specimens that the laboratory procedure will use.|
|[ProcedureRequestSupportingInformation](ProcedureRequestSupportingInformation.md)|Additional clinical information about the patient or specimen that may influence the procedure or diagnostics or their interpretations.|
|[ProcedureUsedReference](ProcedureUsedReference.md)|Identifies medications, devices and any other substance used as part of the procedure.|
|[RelatedPerson](RelatedPerson.md)|Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process.|
|[Task](Task.md)|Generic activity representing work needed to be done.|
