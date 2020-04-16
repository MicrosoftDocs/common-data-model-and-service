---
title: overview - Common Data Model | Microsoft Docs
description: service is a folder that contains standard entities related to the Common Data Model.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# service

CDM standard entities  

## Entities

|Name|Description|
|---|---|
|[ActivityParty](ActivityParty.md)|Person or group associated with an activity. An activity can have multiple activity parties.|
|[Case](Case.md)|Service request case associated with a contract.|
|[CaseResolution](CaseResolution.md)|Special type of activity that includes description of the resolution, billing status, and the duration of the case.|
|[ChildIncidentCount](ChildIncidentCount.md)|For internal use only.|
|[Contract](Contract.md)|Agreement to provide customer service during a specified amount of time or number of cases.|
|[ContractLine](ContractLine.md)|Line item in a contract that specifies the type of service a customer is entitled to.|
|[Entitlement](Entitlement.md)|Defines the amount and type of support a customer should receive.|
|[EntitlementContact](EntitlementContact.md)||
|[EntitlementProduct](EntitlementProduct.md)||
|[FacilityEquipment](FacilityEquipment.md)|Resource that can be scheduled.|
|[IncidentKnowledgeBaseRecord](IncidentKnowledgeBaseRecord.md)||
|[KnowledgeArticleIncident](KnowledgeArticleIncident.md)|Association between an knowledge article and incident.|
|[Resource](Resource.md)|User or facility/equipment that can be scheduled for a service.|
|[ResourceExpansion](ResourceExpansion.md)|Resource Expansions.|
|[ResourceSpecification](ResourceSpecification.md)|Selection rule that allows the scheduling engine to select a number of resources from a pool of resources. The rules can be associated with a service.|
|[SchedulingGroup](SchedulingGroup.md)|Resource group or team whose members can be scheduled for a service.|
|[Service](Service.md)|Activity that represents work done to satisfy a customer's need.|
|[ServiceActivity](ServiceActivity.md)|Activity offered by the organization to satisfy its customer's needs. Each service activity includes date, time, duration, and required resources.|
|[ServiceContractContact](ServiceContractContact.md)|Item in a Service contract.|
|[Site](Site.md)|Location or branch office where an organization does business. An organization can have multiple sites.|
|[SLAKPIInstance](SLAKPIInstance.md)|Service level agreement (SLA) key performance indicator (KPI) instance that is tracked for an individual case|
|[Task](Task.md)|Generic activity representing work needed to be done.|
|[User](User.md)|Person with access to the Microsoft CRM system and who owns objects in the Microsoft CRM database.|
