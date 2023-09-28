---
title: overview of PropertyandCasualtyDataModel - Common Data Model | Microsoft Docs
description: PropertyandCasualtyDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/5/2023
ms.author: cdmditeam
---

# Overview of PropertyandCasualtyDataModel

Property and Casualty Data Model CDM entity definitions  

## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|[Affiliation](Affiliation.md)|A company that contracted the Insurer (sometime via an Agency/Agent\) to issue policies under a set of product’s terms and conditions.|
|[Agency](Agency.md)|An office or intermediary where insurance is sold and can be independent or an Insurer office.|
|[Agent](Agent.md)|Information about the Agent, or other insurance representative who has responsibility for selling insurance.|
|[AgentAgency](AgentAgency.md)|Information about the relationship between the Agency and the Agent.|
|[AgentInsurer](AgentInsurer.md)|Information about the relationship between the Insurer and the Agent.|
|[AssetDetail](AssetDetail.md)|Details (attributes\) extensions to an Insured Asset which varies based on Line of business. e.g., vehicle for Auto insurance, apartment for home insurance.|
|[AssetDetailCatalog](AssetDetailCatalog.md)|A definition of an asset detail (attribute\) which is later used when extending a Policy Insured Asset’s detail.|
|[AuthorizedJurisdiction](AuthorizedJurisdiction.md)|Country and State where business is authorized/not authorized to be conducted.|
|[BrokerAgency](BrokerAgency.md)|Information about the relationship between the broker and its Agency.|
|[CauseOfLoss](CauseOfLoss.md)|The perils that can trigger damage or loss. Relates to Policy's Coverages, Exclusions and Inclusions.|
|[CauseOfLossCatalog](CauseOfLossCatalog.md)|The inventory of all cause of loss.|
|[CauseOfLossLOB](CauseOfLossLOB.md)|Definition of cause of loss related to Coverages/Exclusions/Inclusion for a Line of business. One or more LOBs comprise a product which is subsequently used to create a Policy.|
|[Claim](Claim.md)|A demand raised by a customer with an active Insurance Policy to recover in the event of a loss that is covered under their Policy.|
|[ClaimRevision](ClaimRevision.md)|Captures any updates that happen to the claim incident.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|[Country](Country.md)|Generic country table.|
|[Coverage](Coverage.md)|Protection provided by the Insurer and the level of indemnification provided under an Insurance Policy, example include liability, earthquake, or collision.|
|[CoverageCatalog](CoverageCatalog.md)|Inventory of all Coverages which are subsequently used to create the Line of business.|
|[CoverageDetail](CoverageDetail.md)|Details (attributes\) extensions to a Coverage which varies based on Line of business.|
|[CoverageDetailCatalog](CoverageDetailCatalog.md)|A definition of a Coverage detail (attribute\) which is later used when extending a Policy Coverages detail.|
|[CoverageLOB](CoverageLOB.md)|Definition of Coverage for a Line of business. One or more LOBs comprise a product which is subsequently used to create a Policy.|
|[DetailType](DetailType.md)|The details type provides additional semantics to the Coverage/Insured Assets details, to be used when performing analytics on the details extended information.|
|[Document](Document.md)|Correspondence document between insurance personas about insurance items.|
|[DocumentPartyContract](DocumentPartyContract.md)|Information about the relationship between the contract (e.g., Policy\) and a party, including the party role relating to the document.|
|[ExclusionInclusion](ExclusionInclusion.md)|A provision related to hazards, circumstances, or specific property not covered by the Insurance Policy (related to a Coverage\).|
|[ExclusionInclusionCatalog](ExclusionInclusionCatalog.md)|Inventory of all Exclusions/Inclusions which are subsequently used to create the Line of business.|
|[ExclusionInclusionLOB](ExclusionInclusionLOB.md)|Definition of provisions related to Coverages for a Line of business. One or more LOBs comprise a product which is subsequently used to create a Policy.|
|[InsuredAssetClaim](InsuredAssetClaim.md)|Information about the relationship between the Insured Asset/location and a claim.|
|[InsuredAssetLocation](InsuredAssetLocation.md)|Information about an Insured Asset's location. In many cases the asset's location (e.g., car parking lot, mall\) are also insured with the asset.|
|[InsuredAssetLocationAsset](InsuredAssetLocationAsset.md)|Information about the relationship between the Insured Asset and its location.|
|[InsuredAutoAsset](InsuredAutoAsset.md)|Information of an Insured Auto.|
|[InsuredGenericAsset](InsuredGenericAsset.md)|Information on a generic insurable item. Insured cars and Homes have specialized tables. The model can be extended by adding other specialized Insured Asset tables.|
|[InsuredHomeAsset](InsuredHomeAsset.md)|Information of an Insured Home.|
|[Insurer](Insurer.md)|Information about the business that insures or carries the insurance policies. e.g., insurance company. An Insurer can relate to a parent Insurer as in the case of subsidiaries.|
|[InsurerAgency](InsurerAgency.md)|Information about the relationship between an Insurer and an Agency.|
|[LOB](LOB.md)|A Line of business definition (Coverages, exclusions, Inclusions, cause of loss, details\). One or more LOBs comprise a product which is subsequently used to create a Policy.|
|[LOBAssetDetailCatalog](LOBAssetDetailCatalog.md)|Information about the relationship between a Line of business and a detail in the details catalog. This information is subsequently used, in conjunction with Insured Asset/location categories, to create the details extensions for the Insured Assets in the generated Policy.|
|[LOBCatalog](LOBCatalog.md)|Inventory of all LOBs which are subsequently used to create the Line of business.|
|[Payment](Payment.md)|Any payment that relates to a Policy, e.g., Policy monthly premium payment from the insured to the Insurer, claim payment from the Insurer to the insured, payment to the tow company for towing a damaged car.|
|[PaymentParty](PaymentParty.md)|Participants of a payment transaction.|
|[Policy](Policy.md)|A contract of insurance between the customer and the Insurer. The Policy relates to a parent Policy. This provides support to different scenarios, e.g., handling Policy amendments (add only the new amendments to a child Policy record\) or handling collective policies.|
|[PolicyAgency](PolicyAgency.md)|Information about the relationship between an Insurance Policy and Agency.|
|[PolicyAgent](PolicyAgent.md)|Information about the relationship between the Agent and a Policy he handles.|
|[PolicyProduct](PolicyProduct.md)|Definitions of Policy product. A product is comprised of one or more Line of business.|
|[PolicyProductLOB](PolicyProductLOB.md)|Information about the relationship between a Policy product and one or more lines of business.|
|[PolicyTransaction](PolicyTransaction.md)|A Policy transaction provides information of each transaction (e.g., amendment\) of the Policy.|
|[ProfessionalLicense](ProfessionalLicense.md)|A permit from an authority for insurance professionals, for example to sell insurance policies.|
|[RelatedPartyContract](RelatedPartyContract.md)|A related party having an agreement with an insurance party on a contract.&#xA;1. Party:an insurance entity (Insurer, Agent...\)&#xA;2. Related party:either a 1st party (a law office being insured\), or a 3rd party (a law office handling a claim\).&#xA;3. Contract part \x2d Policy, claim...|
|[StateProvince](StateProvince.md)|Generic State/Province table.|
|[TermDocumentCatalog](TermDocumentCatalog.md)|Reference to terms and conditions applicable to various catalog parts.|
|[TermDocumentPolicyPart](TermDocumentPolicyPart.md)|A helper table to define the relationship between a term document and its Policy part.|
