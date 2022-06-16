---
title: overview of ClinicalProcedure - Common Data Model | Microsoft Docs
description: ClinicalProcedure is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of ClinicalProcedure

CDM standard entities for 'ClinicalProcedure'  

## Entities

|Name|Description|
|---|---|
|[ProcedureBasedOn](ProcedureBasedOn.md)|A reference to a resource that contains details of the request for this procedure.|
|[ProcedureBodySite](ProcedureBodySite.md)|Detailed and structured anatomical location information. Multiple locations are allowed - e.g. multiple punch biopsies of a lesion.|
|[ProcedureCode](ProcedureCode.md)||
|[ProcedureComplication](ProcedureComplication.md)|Any complications that occurred during the procedure, or in the immediate post-performance period.|
|[ProcedureComplicationDetail](ProcedureComplicationDetail.md)|Any complications that occurred during the procedure, or in the immediate post-performance period.|
|[ProcedureDefinition](ProcedureDefinition.md)|A protocol, guideline, order set or other definition that was adhered to in whole or in part by this procedure.|
|[ProcedureFocalDevice](ProcedureFocalDevice.md)|A device that is implanted, removed or otherwise manipulated (calibration, battery replacement, fitting a prosthesis, attaching a wound-vac, etc.) as a focal portion of the Procedure.|
|[ProcedureFollowUp](ProcedureFollowUp.md)|If the procedure required specific follow up - e.g. removal of sutures. The followup may be represented as a simple note.|
|[ProcedurePartOf](ProcedurePartOf.md)|A larger event of which this particular procedure is a component or step.|
|[ProcedurePerformer](ProcedurePerformer.md)|Limited to 'real' people rather than equipment.|
|[ProcedureReason](ProcedureReason.md)|The coded reason why the procedure was performed. This may be coded entity of some type, or may simply be present as text.|
|[ProcedureReasonReference](ProcedureReasonReference.md)|The condition that is the reason why the procedure was performed.|
|[ProcedureReport](ProcedureReport.md)|Procedure report could represent histology result, pathology report, surgical report, etc.|
|[ProcedureRequestBasedOn](ProcedureRequestBasedOn.md)|Plan/proposal/order fulfilled by this request.|
|[ProcedureRequestBodySite](ProcedureRequestBodySite.md)|Anatomic location where the procedure should be performed. This is the target site.|
|[ProcedureRequestCategory](ProcedureRequestCategory.md)|A code that classifies the procedure for searching, sorting and display purposes (e.g. "Surgical Procedure").|
|[ProcedureRequestDefinition](ProcedureRequestDefinition.md)|Protocol or definition followed by this request.|
|[ProcedureRequestReasonCode](ProcedureRequestReasonCode.md)|An explanation or justification for why this diagnostic investigation is being requested in coded or textual form. This is often for billing purposes. May relate to the resources referred to in supp|
|[ProcedureRequestReasonReference](ProcedureRequestReasonReference.md)|Indicates another resource that provides a justification for why this diagnostic investigation is being requested. May relate to the resources referred to in supporting Information.|
|[ProcedureRequestRelevantHistory](ProcedureRequestRelevantHistory.md)|Key events in the history of the request.|
|[ProcedureRequestReplace](ProcedureRequestReplace.md)|The request takes the place of the referenced completed or terminated request(s).|
|[ProcedureRequestSpecimen](ProcedureRequestSpecimen.md)|One or more specimens that the laboratory procedure will use.|
|[ProcedureRequestSupportingInformation](ProcedureRequestSupportingInformation.md)|Additional clinical information about the patient or specimen that may influence the procedure or diagnostics or their interpretations.|
|[ProcedureUsedCode](ProcedureUsedCode.md)|Identifies coded items that were used as part of the procedure.|
|[ProcedureUsedReference](ProcedureUsedReference.md)|Identifies medications, devices and any other substance used as part of the procedure.|
