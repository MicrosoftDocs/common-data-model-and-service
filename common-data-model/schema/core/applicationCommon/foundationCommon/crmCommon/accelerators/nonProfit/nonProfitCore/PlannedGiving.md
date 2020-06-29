---
title: PlannedGiving - Common Data Model | Microsoft Docs
description: A planned gift is a gift made during a donor's lifetime or at the time of their death that involves their estate and/or tax planning.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/29/2020
ms.author: nebanfic
---

# Planned Giving

A planned gift is a gift made during a donor's lifetime or at the time of their death that involves their estate and/or tax planning.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitCore/PlannedGiving.cdm.json" target="_blank">GitHub</a>.  

## Instances

<details>
<summary>Entities that inherit from the currently viewed entity are listed below.  
</summary>

- [/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitForSales/PlannedGiving](../nonProfitForSales/PlannedGiving.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitForSales/PlannedGiving.cdm.json/PlannedGiving")  
- [/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitIati/PlannedGiving](../nonProfitIati/PlannedGiving.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitIati/PlannedGiving.cdm.json/PlannedGiving")  
</details>

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"2.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsCreationModificationDatesAndIds</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsOwnershipInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsTimeZoneInfo</td></tr><tr><td>/core/wellKnownCDSAttributeGroups.cdm.json<br>/cdsVersionTracking</td></tr><tr><td>/core/applicationCommon/foundationCommon<br>/crmCommon/accelerators/nonProfit/nonProfitCore<br>/PlannedGiving.cdm.json/PlannedGiving<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PlannedGiving/(resolvedAttributes)/plannedGivingId](#plannedGivingId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PlannedGiving/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned Giving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A planned gift is a gift made during a donor's lifetime or at the time of their death that involves their estate and/or tax planning.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_PlannedGiving"</td><td>string</td><td></td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[actualPercentOfEstateRecieved](#actualPercentOfEstateRecieved)|Actual percent of donor estate received by organization|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[affiliation](#affiliation)|Represents groups within the organization.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[affiliation_display](#affiliation_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[amountPerFrequency](#amountPerFrequency)|Amount distributed to organization per defined frequency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[amountPerFrequencyBase](#amountPerFrequencyBase)|Value of the Amount Per Frequency in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[annualMarketValue](#annualMarketValue)|Annual Market Value provided by official valuation source such as Kaspick.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[annualMarketValueBase](#annualMarketValueBase)|Value of the Annual Market Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[annualMarketValueDate](#annualMarketValueDate)|Date Annual Market Value provided by official valuation source such as Kaspick.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[annualPayment](#annualPayment)|Annual Payment to organization.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[annualPaymentBase](#annualPaymentBase)|Value of the Annual Payment in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[anticipatedAnnualPayment](#anticipatedAnnualPayment)|Anticipated Annual Payment to organization.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[anticipatedAnnualPaymentBase](#anticipatedAnnualPaymentBase)|Value of the Anticipated Annual Payment in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[anticipatedDistributionDateOfTrust](#anticipatedDistributionDateOfTrust)|Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[anticipatedPercentOfTrust](#anticipatedPercentOfTrust)|Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[appraisalDate](#appraisalDate)|Date the appraisal was conducted.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[appraisalValue](#appraisalValue)|Value of the appraised item or asset from qualified appraiser|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[appraisalValueBase](#appraisalValueBase)|Value of the Appraisal Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[bequestType](#bequestType)|Is the Bequest a Living Trust, Will, or both?|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[bequestType_display](#bequestType_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[capitalGainIncome](#capitalGainIncome)|Beneficiary's taxable capital gain income portion of life insurance income.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[capitalGainIncomeBase](#capitalGainIncomeBase)|Value of the Capital Gain Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[cashSurrenderValue](#cashSurrenderValue)|The current Cash Surrender Value of the insurance policy.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[cashSurrenderValueBase](#cashSurrenderValueBase)|Value of the Cash Surrender Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[charitableDeduction](#charitableDeduction)|Calculated Charitable Deduction for Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[charitableDeductionBase](#charitableDeductionBase)|Value of the Charitable Deduction in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[contractDate](#contractDate)|Date funding will start as specified on the Contract.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[costBasis](#costBasis)|Original purchase price of funding asset.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[costBasisBase](#costBasisBase)|Value of the Cost Basis in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateClaimFormsRecieved](#dateClaimFormsRecieved)|Date Claim Forms Received.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateClaimFormsSubmitted](#dateClaimFormsSubmitted)|Date Claim Forms Submitted.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateEstateClosed](#dateEstateClosed)|Date a management agreement is signed as provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateManagementAgreementSigned](#dateManagementAgreementSigned)|Date a management agreement is signed as provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateStationNotifiedOfDeath](#dateStationNotifiedOfDeath)|Date your organization is notified of the donor's death.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateStationNotifiedOfIntention](#dateStationNotifiedOfIntention)|Date organization Notified of Intention to give a Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateStationNotifiedToMakeClaim](#dateStationNotifiedToMakeClaim)|Date Organization notified to make a claim.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[dateWillExecuted](#dateWillExecuted)|Date Will Executed as provided in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceased](#deceased)|Indicates the Contact is Deceased.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedDay](#deceasedDay)|Day the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedDay_display](#deceasedDay_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedMonth](#deceasedMonth)|Month the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedMonth_display](#deceasedMonth_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedYear](#deceasedYear)|Year the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deceasedYear_display](#deceasedYear_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[deferredToDate](#deferredToDate)|Same as date of first payment when more than one year after the contract date.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[designatedOrganizationPercent](#designatedOrganizationPercent)|Percent of remainder designated to organization|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[designatedPrincipleAmount](#designatedPrincipleAmount)|Amount of principle designated to organization.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[designatedPrincipleAmountBase](#designatedPrincipleAmountBase)|Value of the Designated Principle Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[designation](#designation)|Usage of gift funds will be unrestricted, restricted or permanently restricted.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[designation_display](#designation_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[discountRate](#discountRate)|Interest rate a central bank charges depository institutions that borrow reserves from it.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[discountRateMonth](#discountRateMonth)|Month in which latest Discount Rate was populated.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[discountRateMonth_display](#discountRateMonth_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[discountRateYear](#discountRateYear)|Year in which latest Discount Rate was populated.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[discountRateYear_display](#discountRateYear_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[endowmentType](#endowmentType)|Specific endowment at organization where gift will be applied.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[endowmentType_display](#endowmentType_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[estimatedGivingAmount](#estimatedGivingAmount)|Estimated amount organization will receive as provided by executor, trustee, or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[estimatedGivingAmountBase](#estimatedGivingAmountBase)|Value of the Estimated Giving Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[estimatedTrustProbateDate](#estimatedTrustProbateDate)|Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[expectedFinalDistributionDate](#expectedFinalDistributionDate)|Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[expectedFirstDistributionDate](#expectedFirstDistributionDate)|Expected Date of First Distribution, typically information provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[externalID](#externalID)|ID from External or Legacy system.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[faceValue](#faceValue)|Value of funds donated.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[faceValueBase](#faceValueBase)|Value of the Face Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[fundId](#fundId)|Unique identifier for Account associated with Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[givingAmount](#givingAmount)|Sum of gifts entered on this record (logic field).|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[givingReceivedDate](#givingReceivedDate)|Date distribution or remainder for Planned Giving is received.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[givingSubtype](#givingSubtype)|Specific type of Planned Giving instrument.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[givingSubtype_display](#givingSubtype_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insuranceAnnualPremium](#insuranceAnnualPremium)|Annual Premium of the Life Insurance.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insuranceAnnualPremiumBase](#insuranceAnnualPremiumBase)|Value of the Insurance Annual Premium in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insuranceCompany](#insuranceCompany)|Insurance Company for related to this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insuranceDeathBenefitAmount](#insuranceDeathBenefitAmount)|Death Benefit Amount from Insurance.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insurancePolicyCode](#insurancePolicyCode)|Insurance policy code related to this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insurancePolicyName](#insurancePolicyName)|Insurance Policy Name for this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insurancePremiumDueDate](#insurancePremiumDueDate)|Insurance Premium Due Date related to this Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[insurancePremiumPaymentAddress](#insurancePremiumPaymentAddress)|Address for the Life Insurance Premium Payment.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[isRevocable](#isRevocable)|Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[leadSource](#leadSource)|Method of communication that prompted Donor to discuss Planned Giving options.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[leadSource_display](#leadSource_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[name](#name)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[ordinaryIncome](#ordinaryIncome)|Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[ordinaryIncomeBase](#ordinaryIncomeBase)|Value of the Ordinary Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[paymentFrequency](#paymentFrequency)|Defined frequency payments are distributed to the organization.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[paymentFrequency_display](#paymentFrequency_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[payoutRate](#payoutRate)|Dollar amount per share a Corporation pays for their dividend.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[plannedGivingPledgedByContactId](#plannedGivingPledgedByContactId)|Pledged By Contact|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[plannedGivingId](#plannedGivingId)|Unique identifier for entity instances|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[pledgesOnAccountId](#pledgesOnAccountId)|Unique identifier for Account associated with Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[presentValue](#presentValue)|The value on a given date of a payment or series of payments made at other times for an investment.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[presentValueBase](#presentValueBase)|Value of the Present Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[recordType](#recordType)|Type of Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[remainderAmount](#remainderAmount)|Remainder $ value a Charitable Organization receives.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[remainderAmountBase](#remainderAmountBase)|Value of the Remainder Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[rollupGiving](#rollupGiving)|Populated by trigger, reflects the most recent Date/Time for Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[salvageValueOfBuildings](#salvageValueOfBuildings)|Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[salvageValueOfBuildingsBase](#salvageValueOfBuildingsBase)|Value of the Salvage Value of Buildings in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[severDate](#severDate)|The term end date' or the date of the related Contact's death.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[stage](#stage)|The current phase the giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[stage_display](#stage_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[taxFreeIncome](#taxFreeIncome)|The tax free income from the asset related to this giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[taxFreeIncomeBase](#taxFreeIncomeBase)|Value of the Tax Free Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[termEndDate](#termEndDate)|Term end date for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[termType](#termType)|Term type for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[termType_display](#termType_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[termYears](#termYears)|Term years for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[totalEstateValue](#totalEstateValue)|Total Estate Value as provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[totalEstateValueBase](#totalEstateValueBase)|Value of the Total Estate Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[trustMarketValue](#trustMarketValue)|Trust Market Value related to this planned giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[trustMarketValueBase](#trustMarketValueBase)|Value of the Trust Market Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[trustProbateNoticeDate](#trustProbateNoticeDate)|Date Trust/Probate Notice received.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[trustValueDate](#trustValueDate)|Trust Value Date related to this planned giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[typeOfManagement](#typeOfManagement)|The type of management for the underlying asset or assets related to this Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[typeOfManagement_display](#typeOfManagement_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[stateCode](#stateCode)|Status of the Planned Giving|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[stateCode_display](#stateCode_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[statusCode](#statusCode)|Reason for the status of the Planned Giving|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[statusCode_display](#statusCode_display)||<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="PlannedGiving.md" target="_blank">nonProfitCore/PlannedGiving</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr><tr><td>en</td><td>Unique identifier of the user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.modify**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr><tr><td>en</td><td>Unique identifier of the user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>en</td><td>Unique identifier of the delegate user who created the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>en</td><td>Unique identifier of the delegate user who modified the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedonbehalfby"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**means.measurement.date.creation**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr><tr><td><a href="../../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"ownerid"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.entityName**  
**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.name**  
Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

**is.readOnly**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owneridtype"</td><td>string</td><td></td></tr></table>

**is.CDS.owner**  
contains a User or Team ID  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../BusinessUnit.md" target="_blank">/core/applicationCommon/BusinessUnit.cdm.json/BusinessUnit</a></td><td><a href="../../../../../BusinessUnit.md#businessUnitId" target="_blank">businessUnitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningbusinessunit"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**means.userId**  
contains a userId  

**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../User.md" target="_blank">/core/applicationCommon/User.cdm.json/User</a></td><td><a href="../../../../../User.md#systemUserId" target="_blank">systemUserId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owninguser"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../Team.md" target="_blank">/core/applicationCommon/Team.cdm.json/Team</a></td><td><a href="../../../../../Team.md#teamId" target="_blank">teamId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"owningteam"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>3</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**means.measurement.version**  
**is.CDS.standard**  
identifies attributes that are part of the cdsStandard base set.  

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"versionnumber"</td><td>string</td><td></td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the exchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"exchangerate"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1E-10"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange Rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#actualPercentOfEstateRecieved name="actualPercentOfEstateRecieved">actualPercentOfEstateRecieved</a>

Actual percent of donor estate received by organization  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual % of Estate Received</td></tr><tr><td>description</td><td>Actual percent of donor estate received by organization</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_actualpercentofestaterecieved</td></tr></table>

#### Traits

<details>
<summary>List of traits for the actualPercentOfEstateRecieved attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_actualpercentofestaterecieved"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual % of Estate Received</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual percent of donor estate received by organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#affiliation name="affiliation">affiliation</a>

Represents groups within the organization.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Affiliation</td></tr><tr><td>description</td><td>Represents groups within the organization.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_affiliation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>NGO</td><td>100000000</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the affiliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>NGO</td><td>100000000</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_affiliation"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Affiliation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Represents groups within the organization.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#affiliation_display name="affiliation_display">affiliation_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the affiliation_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"affiliation"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#amountPerFrequency name="amountPerFrequency">amountPerFrequency</a>

Amount distributed to organization per defined frequency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Per Frequency</td></tr><tr><td>description</td><td>Amount distributed to organization per defined frequency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountperfrequency</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountPerFrequency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_amountperfrequency"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount Per Frequency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount distributed to organization per defined frequency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#amountPerFrequencyBase name="amountPerFrequencyBase">amountPerFrequencyBase</a>

Value of the Amount Per Frequency in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Per Frequency (Base)</td></tr><tr><td>description</td><td>Value of the Amount Per Frequency in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountperfrequency_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountPerFrequencyBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_amountperfrequency_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount Per Frequency (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Amount Per Frequency in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#annualMarketValue name="annualMarketValue">annualMarketValue</a>

Annual Market Value provided by official valuation source such as Kaspick.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value</td></tr><tr><td>description</td><td>Annual Market Value provided by official valuation source such as Kaspick.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the annualMarketValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_annualmarketvalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Market Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Market Value provided by official valuation source such as Kaspick.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#annualMarketValueBase name="annualMarketValueBase">annualMarketValueBase</a>

Value of the Annual Market Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value (Base)</td></tr><tr><td>description</td><td>Value of the Annual Market Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the annualMarketValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_annualmarketvalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Market Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Annual Market Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#annualMarketValueDate name="annualMarketValueDate">annualMarketValueDate</a>

Date Annual Market Value provided by official valuation source such as Kaspick.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value Date</td></tr><tr><td>description</td><td>Date Annual Market Value provided by official valuation source such as Kaspick.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvaluedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the annualMarketValueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_annualmarketvaluedate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Market Value Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Annual Market Value provided by official valuation source such as Kaspick.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#annualPayment name="annualPayment">annualPayment</a>

Annual Payment to organization.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Payment</td></tr><tr><td>description</td><td>Annual Payment to organization.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualpayment</td></tr></table>

#### Traits

<details>
<summary>List of traits for the annualPayment attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_annualpayment"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Payment to organization.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#annualPaymentBase name="annualPaymentBase">annualPaymentBase</a>

Value of the Annual Payment in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Payment (Base)</td></tr><tr><td>description</td><td>Value of the Annual Payment in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualpayment_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the annualPaymentBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_annualpayment_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Payment (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Annual Payment in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#anticipatedAnnualPayment name="anticipatedAnnualPayment">anticipatedAnnualPayment</a>

Anticipated Annual Payment to organization.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Annual Payment</td></tr><tr><td>description</td><td>Anticipated Annual Payment to organization.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedannualpayment</td></tr></table>

#### Traits

<details>
<summary>List of traits for the anticipatedAnnualPayment attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_anticipatedannualpayment"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated Annual Payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated Annual Payment to organization.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#anticipatedAnnualPaymentBase name="anticipatedAnnualPaymentBase">anticipatedAnnualPaymentBase</a>

Value of the Anticipated Annual Payment in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Annual Payment (Base)</td></tr><tr><td>description</td><td>Value of the Anticipated Annual Payment in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedannualpayment_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the anticipatedAnnualPaymentBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_anticipatedannualpayment_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated Annual Payment (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Anticipated Annual Payment in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#anticipatedDistributionDateOfTrust name="anticipatedDistributionDateOfTrust">anticipatedDistributionDateOfTrust</a>

Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Distribution Date of Trust</td></tr><tr><td>description</td><td>Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipateddistributiondateoftrust</td></tr></table>

#### Traits

<details>
<summary>List of traits for the anticipatedDistributionDateOfTrust attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_anticipateddistributiondateoftrust"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated Distribution Date of Trust</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#anticipatedPercentOfTrust name="anticipatedPercentOfTrust">anticipatedPercentOfTrust</a>

Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated % of Trust</td></tr><tr><td>description</td><td>Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedpercentoftrust</td></tr></table>

#### Traits

<details>
<summary>List of traits for the anticipatedPercentOfTrust attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_anticipatedpercentoftrust"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated % of Trust</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#appraisalDate name="appraisalDate">appraisalDate</a>

Date the appraisal was conducted.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Date</td></tr><tr><td>description</td><td>Date the appraisal was conducted.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisaldate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the appraisalDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_appraisaldate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Appraisal Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date the appraisal was conducted.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#appraisalValue name="appraisalValue">appraisalValue</a>

Value of the appraised item or asset from qualified appraiser  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Value</td></tr><tr><td>description</td><td>Value of the appraised item or asset from qualified appraiser</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisalvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the appraisalValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_appraisalvalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Appraisal Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the appraised item or asset from qualified appraiser</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#appraisalValueBase name="appraisalValueBase">appraisalValueBase</a>

Value of the Appraisal Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Value (Base)</td></tr><tr><td>description</td><td>Value of the Appraisal Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisalvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the appraisalValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_appraisalvalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Appraisal Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Appraisal Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#bequestType name="bequestType">bequestType</a>

Is the Bequest a Living Trust, Will, or both?  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bequest Type</td></tr><tr><td>description</td><td>Is the Bequest a Living Trust, Will, or both?</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bequesttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Living Trust</td><td>100000000</td></tr><tr><td>en</td><td>Will</td><td>100000001</td></tr><tr><td>en</td><td>Living Trust and Will</td><td>100000002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the bequestType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Living Trust</td><td>100000000</td></tr><tr><td>en</td><td>Will</td><td>100000001</td></tr><tr><td>en</td><td>Living Trust and Will</td><td>100000002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_bequesttype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bequest Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is the Bequest a Living Trust, Will, or both?</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#bequestType_display name="bequestType_display">bequestType_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bequestType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"bequestType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#capitalGainIncome name="capitalGainIncome">capitalGainIncome</a>

Beneficiary's taxable capital gain income portion of life insurance income.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Gain Income</td></tr><tr><td>description</td><td>Beneficiary's taxable capital gain income portion of life insurance income.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_capitalgainincome</td></tr></table>

#### Traits

<details>
<summary>List of traits for the capitalGainIncome attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_capitalgainincome"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Capital Gain Income</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Beneficiary's taxable capital gain income portion of life insurance income.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#capitalGainIncomeBase name="capitalGainIncomeBase">capitalGainIncomeBase</a>

Value of the Capital Gain Income in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Gain Income (Base)</td></tr><tr><td>description</td><td>Value of the Capital Gain Income in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_capitalgainincome_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the capitalGainIncomeBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_capitalgainincome_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Capital Gain Income (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Capital Gain Income in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cashSurrenderValue name="cashSurrenderValue">cashSurrenderValue</a>

The current Cash Surrender Value of the insurance policy.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash Surrender Value</td></tr><tr><td>description</td><td>The current Cash Surrender Value of the insurance policy.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_cashsurrendervalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cashSurrenderValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_cashsurrendervalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash Surrender Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The current Cash Surrender Value of the insurance policy.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cashSurrenderValueBase name="cashSurrenderValueBase">cashSurrenderValueBase</a>

Value of the Cash Surrender Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash Surrender Value (Base)</td></tr><tr><td>description</td><td>Value of the Cash Surrender Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_cashsurrendervalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cashSurrenderValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_cashsurrendervalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash Surrender Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Cash Surrender Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#charitableDeduction name="charitableDeduction">charitableDeduction</a>

Calculated Charitable Deduction for Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charitable Deduction</td></tr><tr><td>description</td><td>Calculated Charitable Deduction for Planned Giving.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_charitablededuction</td></tr></table>

#### Traits

<details>
<summary>List of traits for the charitableDeduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_charitablededuction"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Charitable Deduction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated Charitable Deduction for Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#charitableDeductionBase name="charitableDeductionBase">charitableDeductionBase</a>

Value of the Charitable Deduction in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charitable Deduction (Base)</td></tr><tr><td>description</td><td>Value of the Charitable Deduction in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_charitablededuction_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the charitableDeductionBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_charitablededuction_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Charitable Deduction (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Charitable Deduction in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#contractDate name="contractDate">contractDate</a>

Date funding will start as specified on the Contract.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Date</td></tr><tr><td>description</td><td>Date funding will start as specified on the Contract.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_contractdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contractDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_contractdate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contract Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date funding will start as specified on the Contract.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#costBasis name="costBasis">costBasis</a>

Original purchase price of funding asset.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Basis</td></tr><tr><td>description</td><td>Original purchase price of funding asset.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_costbasis</td></tr></table>

#### Traits

<details>
<summary>List of traits for the costBasis attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_costbasis"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost Basis</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original purchase price of funding asset.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#costBasisBase name="costBasisBase">costBasisBase</a>

Value of the Cost Basis in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Basis (Base)</td></tr><tr><td>description</td><td>Value of the Cost Basis in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_costbasis_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the costBasisBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_costbasis_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost Basis (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Cost Basis in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#dateClaimFormsRecieved name="dateClaimFormsRecieved">dateClaimFormsRecieved</a>

Date Claim Forms Received.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Claim Forms Received</td></tr><tr><td>description</td><td>Date Claim Forms Received.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateclaimformsrecieved</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateClaimFormsRecieved attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_dateclaimformsrecieved"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Claim Forms Received</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Claim Forms Received.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateClaimFormsSubmitted name="dateClaimFormsSubmitted">dateClaimFormsSubmitted</a>

Date Claim Forms Submitted.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Claim Forms Submitted</td></tr><tr><td>description</td><td>Date Claim Forms Submitted.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateclaimformssubmitted</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateClaimFormsSubmitted attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_dateclaimformssubmitted"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Claim Forms Submitted</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Claim Forms Submitted.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateEstateClosed name="dateEstateClosed">dateEstateClosed</a>

Date a management agreement is signed as provided by executor, trustee or attorney.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Estate Closed</td></tr><tr><td>description</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateestateclosed</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateEstateClosed attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_dateestateclosed"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Estate Closed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateManagementAgreementSigned name="dateManagementAgreementSigned">dateManagementAgreementSigned</a>

Date a management agreement is signed as provided by executor, trustee or attorney.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Management Agreement Signed</td></tr><tr><td>description</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datemanagementagreementsigned</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateManagementAgreementSigned attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_datemanagementagreementsigned"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Management Agreement Signed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateStationNotifiedOfDeath name="dateStationNotifiedOfDeath">dateStationNotifiedOfDeath</a>

Date your organization is notified of the donor's death.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified of Death</td></tr><tr><td>description</td><td>Date your organization is notified of the donor's death.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedofdeath</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateStationNotifiedOfDeath attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_datestationnotifiedofdeath"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Organization Notified of Death</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date your organization is notified of the donor's death.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateStationNotifiedOfIntention name="dateStationNotifiedOfIntention">dateStationNotifiedOfIntention</a>

Date organization Notified of Intention to give a Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified of Intention</td></tr><tr><td>description</td><td>Date organization Notified of Intention to give a Planned Giving.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedofintention</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateStationNotifiedOfIntention attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_datestationnotifiedofintention"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Organization Notified of Intention</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date organization Notified of Intention to give a Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateStationNotifiedToMakeClaim name="dateStationNotifiedToMakeClaim">dateStationNotifiedToMakeClaim</a>

Date Organization notified to make a claim.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified to Make Claim</td></tr><tr><td>description</td><td>Date Organization notified to make a claim.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedtomakeclaim</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateStationNotifiedToMakeClaim attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_datestationnotifiedtomakeclaim"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Organization Notified to Make Claim</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Organization notified to make a claim.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#dateWillExecuted name="dateWillExecuted">dateWillExecuted</a>

Date Will Executed as provided in estate documentation.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Will Executed</td></tr><tr><td>description</td><td>Date Will Executed as provided in estate documentation.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datewillexecuted</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dateWillExecuted attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_datewillexecuted"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Will Executed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Will Executed as provided in estate documentation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#deceased name="deceased">deceased</a>

Indicates the Contact is Deceased.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased?</td></tr><tr><td>description</td><td>Indicates the Contact is Deceased.</td></tr><tr><td>dataFormat</td><td>15</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceased</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceased attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_deceased"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deceased?</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates the Contact is Deceased.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.boolean**  
</details>

### <a href=#deceasedDay name="deceasedDay">deceasedDay</a>

Day the Contact was deceased.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Day</td></tr><tr><td>description</td><td>Day the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>100000001</td></tr><tr><td>en</td><td>03</td><td>100000002</td></tr><tr><td>en</td><td>04</td><td>100000003</td></tr><tr><td>en</td><td>05</td><td>100000004</td></tr><tr><td>en</td><td>06</td><td>100000005</td></tr><tr><td>en</td><td>07</td><td>100000006</td></tr><tr><td>en</td><td>08</td><td>100000007</td></tr><tr><td>en</td><td>09</td><td>100000008</td></tr><tr><td>en</td><td>10</td><td>100000009</td></tr><tr><td>en</td><td>11</td><td>100000010</td></tr><tr><td>en</td><td>12</td><td>100000011</td></tr><tr><td>en</td><td>13</td><td>100000012</td></tr><tr><td>en</td><td>14</td><td>100000013</td></tr><tr><td>en</td><td>15</td><td>100000014</td></tr><tr><td>en</td><td>16</td><td>100000015</td></tr><tr><td>en</td><td>17</td><td>100000016</td></tr><tr><td>en</td><td>18</td><td>100000017</td></tr><tr><td>en</td><td>19</td><td>100000018</td></tr><tr><td>en</td><td>20</td><td>100000019</td></tr><tr><td>en</td><td>21</td><td>100000020</td></tr><tr><td>en</td><td>22</td><td>100000021</td></tr><tr><td>en</td><td>23</td><td>100000022</td></tr><tr><td>en</td><td>24</td><td>100000023</td></tr><tr><td>en</td><td>25</td><td>100000024</td></tr><tr><td>en</td><td>26</td><td>100000025</td></tr><tr><td>en</td><td>27</td><td>100000026</td></tr><tr><td>en</td><td>28</td><td>100000027</td></tr><tr><td>en</td><td>29</td><td>100000028</td></tr><tr><td>en</td><td>30</td><td>100000029</td></tr><tr><td>en</td><td>31</td><td>100000030</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedDay attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>100000001</td></tr><tr><td>en</td><td>03</td><td>100000002</td></tr><tr><td>en</td><td>04</td><td>100000003</td></tr><tr><td>en</td><td>05</td><td>100000004</td></tr><tr><td>en</td><td>06</td><td>100000005</td></tr><tr><td>en</td><td>07</td><td>100000006</td></tr><tr><td>en</td><td>08</td><td>100000007</td></tr><tr><td>en</td><td>09</td><td>100000008</td></tr><tr><td>en</td><td>10</td><td>100000009</td></tr><tr><td>en</td><td>11</td><td>100000010</td></tr><tr><td>en</td><td>12</td><td>100000011</td></tr><tr><td>en</td><td>13</td><td>100000012</td></tr><tr><td>en</td><td>14</td><td>100000013</td></tr><tr><td>en</td><td>15</td><td>100000014</td></tr><tr><td>en</td><td>16</td><td>100000015</td></tr><tr><td>en</td><td>17</td><td>100000016</td></tr><tr><td>en</td><td>18</td><td>100000017</td></tr><tr><td>en</td><td>19</td><td>100000018</td></tr><tr><td>en</td><td>20</td><td>100000019</td></tr><tr><td>en</td><td>21</td><td>100000020</td></tr><tr><td>en</td><td>22</td><td>100000021</td></tr><tr><td>en</td><td>23</td><td>100000022</td></tr><tr><td>en</td><td>24</td><td>100000023</td></tr><tr><td>en</td><td>25</td><td>100000024</td></tr><tr><td>en</td><td>26</td><td>100000025</td></tr><tr><td>en</td><td>27</td><td>100000026</td></tr><tr><td>en</td><td>28</td><td>100000027</td></tr><tr><td>en</td><td>29</td><td>100000028</td></tr><tr><td>en</td><td>30</td><td>100000029</td></tr><tr><td>en</td><td>31</td><td>100000030</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_deceasedday"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deceased Day</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Day the Contact was deceased.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#deceasedDay_display name="deceasedDay_display">deceasedDay_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedDay_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"deceasedDay"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#deceasedMonth name="deceasedMonth">deceasedMonth</a>

Month the Contact was deceased.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Month</td></tr><tr><td>description</td><td>Month the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedmonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>844060000</td></tr><tr><td>en</td><td>03</td><td>844060001</td></tr><tr><td>en</td><td>04</td><td>844060002</td></tr><tr><td>en</td><td>05</td><td>844060003</td></tr><tr><td>en</td><td>06</td><td>844060004</td></tr><tr><td>en</td><td>07</td><td>844060005</td></tr><tr><td>en</td><td>08</td><td>844060006</td></tr><tr><td>en</td><td>09</td><td>844060007</td></tr><tr><td>en</td><td>10</td><td>844060008</td></tr><tr><td>en</td><td>11</td><td>844060009</td></tr><tr><td>en</td><td>12</td><td>844060010</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>844060000</td></tr><tr><td>en</td><td>03</td><td>844060001</td></tr><tr><td>en</td><td>04</td><td>844060002</td></tr><tr><td>en</td><td>05</td><td>844060003</td></tr><tr><td>en</td><td>06</td><td>844060004</td></tr><tr><td>en</td><td>07</td><td>844060005</td></tr><tr><td>en</td><td>08</td><td>844060006</td></tr><tr><td>en</td><td>09</td><td>844060007</td></tr><tr><td>en</td><td>10</td><td>844060008</td></tr><tr><td>en</td><td>11</td><td>844060009</td></tr><tr><td>en</td><td>12</td><td>844060010</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_deceasedmonth"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deceased Month</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Month the Contact was deceased.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#deceasedMonth_display name="deceasedMonth_display">deceasedMonth_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedMonth_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"deceasedMonth"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#deceasedYear name="deceasedYear">deceasedYear</a>

Year the Contact was deceased.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Year</td></tr><tr><td>description</td><td>Year the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown</td><td>100000000</td></tr><tr><td>en</td><td>2013</td><td>844060000</td></tr><tr><td>en</td><td>2012</td><td>844060001</td></tr><tr><td>en</td><td>2011</td><td>844060002</td></tr><tr><td>en</td><td>2010</td><td>844060003</td></tr><tr><td>en</td><td>2009</td><td>844060004</td></tr><tr><td>en</td><td>2008</td><td>844060005</td></tr><tr><td>en</td><td>2007</td><td>844060006</td></tr><tr><td>en</td><td>2006</td><td>844060007</td></tr><tr><td>en</td><td>2005</td><td>844060008</td></tr><tr><td>en</td><td>2004</td><td>844060009</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown</td><td>100000000</td></tr><tr><td>en</td><td>2013</td><td>844060000</td></tr><tr><td>en</td><td>2012</td><td>844060001</td></tr><tr><td>en</td><td>2011</td><td>844060002</td></tr><tr><td>en</td><td>2010</td><td>844060003</td></tr><tr><td>en</td><td>2009</td><td>844060004</td></tr><tr><td>en</td><td>2008</td><td>844060005</td></tr><tr><td>en</td><td>2007</td><td>844060006</td></tr><tr><td>en</td><td>2006</td><td>844060007</td></tr><tr><td>en</td><td>2005</td><td>844060008</td></tr><tr><td>en</td><td>2004</td><td>844060009</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_deceasedyear"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deceased Year</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year the Contact was deceased.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#deceasedYear_display name="deceasedYear_display">deceasedYear_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deceasedYear_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"deceasedYear"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#deferredToDate name="deferredToDate">deferredToDate</a>

Same as date of first payment when more than one year after the contract date.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deferred To Date</td></tr><tr><td>description</td><td>Same as date of first payment when more than one year after the contract date.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deferredtodate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deferredToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_deferredtodate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deferred To Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Same as date of first payment when more than one year after the contract date.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#designatedOrganizationPercent name="designatedOrganizationPercent">designatedOrganizationPercent</a>

Percent of remainder designated to organization  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Organization %</td></tr><tr><td>description</td><td>Percent of remainder designated to organization</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedorganizationpercent</td></tr></table>

#### Traits

<details>
<summary>List of traits for the designatedOrganizationPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_designatedorganizationpercent"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Designated Organization %</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percent of remainder designated to organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#designatedPrincipleAmount name="designatedPrincipleAmount">designatedPrincipleAmount</a>

Amount of principle designated to organization.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Principle Amount</td></tr><tr><td>description</td><td>Amount of principle designated to organization.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedprincipleamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the designatedPrincipleAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_designatedprincipleamount"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Designated Principle Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount of principle designated to organization.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#designatedPrincipleAmountBase name="designatedPrincipleAmountBase">designatedPrincipleAmountBase</a>

Value of the Designated Principle Amount in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Principle Amount (Base)</td></tr><tr><td>description</td><td>Value of the Designated Principle Amount in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedprincipleamount_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the designatedPrincipleAmountBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_designatedprincipleamount_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Designated Principle Amount (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Designated Principle Amount in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#designation name="designation">designation</a>

Usage of gift funds will be unrestricted, restricted or permanently restricted.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designation</td></tr><tr><td>description</td><td>Usage of gift funds will be unrestricted, restricted or permanently restricted.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unrestricted</td><td>100000000</td></tr><tr><td>en</td><td>Restricted</td><td>100000001</td></tr><tr><td>en</td><td>Permanently Restriceted</td><td>100000002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the designation attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unrestricted</td><td>100000000</td></tr><tr><td>en</td><td>Restricted</td><td>100000001</td></tr><tr><td>en</td><td>Permanently Restriceted</td><td>100000002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_designation"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Designation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Usage of gift funds will be unrestricted, restricted or permanently restricted.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#designation_display name="designation_display">designation_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the designation_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"designation"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#discountRate name="discountRate">discountRate</a>

Interest rate a central bank charges depository institutions that borrow reserves from it.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate</td></tr><tr><td>description</td><td>Interest rate a central bank charges depository institutions that borrow reserves from it.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountrate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_discountrate"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount Rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest rate a central bank charges depository institutions that borrow reserves from it.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#discountRateMonth name="discountRateMonth">discountRateMonth</a>

Month in which latest Discount Rate was populated.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate Month</td></tr><tr><td>description</td><td>Month in which latest Discount Rate was populated.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountratemonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>844060000</td></tr><tr><td>en</td><td>03</td><td>844060001</td></tr><tr><td>en</td><td>04</td><td>844060002</td></tr><tr><td>en</td><td>05</td><td>844060003</td></tr><tr><td>en</td><td>06</td><td>844060004</td></tr><tr><td>en</td><td>08</td><td>844060005</td></tr><tr><td>en</td><td>09</td><td>844060006</td></tr><tr><td>en</td><td>10</td><td>844060007</td></tr><tr><td>en</td><td>11</td><td>844060008</td></tr><tr><td>en</td><td>12</td><td>844060009</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountRateMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>844060000</td></tr><tr><td>en</td><td>03</td><td>844060001</td></tr><tr><td>en</td><td>04</td><td>844060002</td></tr><tr><td>en</td><td>05</td><td>844060003</td></tr><tr><td>en</td><td>06</td><td>844060004</td></tr><tr><td>en</td><td>08</td><td>844060005</td></tr><tr><td>en</td><td>09</td><td>844060006</td></tr><tr><td>en</td><td>10</td><td>844060007</td></tr><tr><td>en</td><td>11</td><td>844060008</td></tr><tr><td>en</td><td>12</td><td>844060009</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_discountratemonth"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount Rate Month</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Month in which latest Discount Rate was populated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#discountRateMonth_display name="discountRateMonth_display">discountRateMonth_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountRateMonth_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"discountRateMonth"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#discountRateYear name="discountRateYear">discountRateYear</a>

Year in which latest Discount Rate was populated.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate Year</td></tr><tr><td>description</td><td>Year in which latest Discount Rate was populated.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountrateyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown</td><td>100000000</td></tr><tr><td>en</td><td>2013</td><td>844060000</td></tr><tr><td>en</td><td>2012</td><td>844060001</td></tr><tr><td>en</td><td>2011</td><td>844060002</td></tr><tr><td>en</td><td>2010</td><td>844060003</td></tr><tr><td>en</td><td>2009</td><td>844060004</td></tr><tr><td>en</td><td>2008</td><td>844060005</td></tr><tr><td>en</td><td>2007</td><td>844060006</td></tr><tr><td>en</td><td>2006</td><td>844060007</td></tr><tr><td>en</td><td>2005</td><td>844060008</td></tr><tr><td>en</td><td>2004</td><td>844060009</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountRateYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown</td><td>100000000</td></tr><tr><td>en</td><td>2013</td><td>844060000</td></tr><tr><td>en</td><td>2012</td><td>844060001</td></tr><tr><td>en</td><td>2011</td><td>844060002</td></tr><tr><td>en</td><td>2010</td><td>844060003</td></tr><tr><td>en</td><td>2009</td><td>844060004</td></tr><tr><td>en</td><td>2008</td><td>844060005</td></tr><tr><td>en</td><td>2007</td><td>844060006</td></tr><tr><td>en</td><td>2006</td><td>844060007</td></tr><tr><td>en</td><td>2005</td><td>844060008</td></tr><tr><td>en</td><td>2004</td><td>844060009</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_discountrateyear"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount Rate Year</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year in which latest Discount Rate was populated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#discountRateYear_display name="discountRateYear_display">discountRateYear_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountRateYear_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"discountRateYear"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#endowmentType name="endowmentType">endowmentType</a>

Specific endowment at organization where gift will be applied.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endowment Type</td></tr><tr><td>description</td><td>Specific endowment at organization where gift will be applied.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_endowmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Board-Designated Endowment</td><td>100000000</td></tr><tr><td>en</td><td>Permanent Endowment</td><td>100000001</td></tr><tr><td>en</td><td>Donor directed</td><td>100000002</td></tr><tr><td>en</td><td>Current operations</td><td>100000003</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the endowmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Board-Designated Endowment</td><td>100000000</td></tr><tr><td>en</td><td>Permanent Endowment</td><td>100000001</td></tr><tr><td>en</td><td>Donor directed</td><td>100000002</td></tr><tr><td>en</td><td>Current operations</td><td>100000003</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_endowmenttype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Endowment Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Specific endowment at organization where gift will be applied.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#endowmentType_display name="endowmentType_display">endowmentType_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endowmentType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"endowmentType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#estimatedGivingAmount name="estimatedGivingAmount">estimatedGivingAmount</a>

Estimated amount organization will receive as provided by executor, trustee, or attorney.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Giving Amount</td></tr><tr><td>description</td><td>Estimated amount organization will receive as provided by executor, trustee, or attorney.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedgivingamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the estimatedGivingAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_estimatedgivingamount"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated Giving Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated amount organization will receive as provided by executor, trustee, or attorney.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#estimatedGivingAmountBase name="estimatedGivingAmountBase">estimatedGivingAmountBase</a>

Value of the Estimated Giving Amount in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Giving Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Giving Amount in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedgivingamount_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the estimatedGivingAmountBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_estimatedgivingamount_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated Giving Amount (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Estimated Giving Amount in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#estimatedTrustProbateDate name="estimatedTrustProbateDate">estimatedTrustProbateDate</a>

Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Trust/Probate Date</td></tr><tr><td>description</td><td>Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedtrustprobatedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the estimatedTrustProbateDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_estimatedtrustprobatedate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated Trust/Probate Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#expectedFinalDistributionDate name="expectedFinalDistributionDate">expectedFinalDistributionDate</a>

Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Final Distribution Date</td></tr><tr><td>description</td><td>Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedfinaldistributiondate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the expectedFinalDistributionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_expectedfinaldistributiondate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected Final Distribution Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#expectedFirstDistributionDate name="expectedFirstDistributionDate">expectedFirstDistributionDate</a>

Expected Date of First Distribution, typically information provided by executor, trustee or attorney.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected First Distribution Date</td></tr><tr><td>description</td><td>Expected Date of First Distribution, typically information provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedfirstdistributiondate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the expectedFirstDistributionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_expectedfirstdistributiondate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected First Distribution Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expected Date of First Distribution, typically information provided by executor, trustee or attorney.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#externalID name="externalID">externalID</a>

ID from External or Legacy system.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External ID</td></tr><tr><td>description</td><td>ID from External or Legacy system.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_externalid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the externalID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_externalid"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"255"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ID from External or Legacy system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#faceValue name="faceValue">faceValue</a>

Value of funds donated.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Face Value</td></tr><tr><td>description</td><td>Value of funds donated.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_facevalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the faceValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_facevalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Face Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of funds donated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#faceValueBase name="faceValueBase">faceValueBase</a>

Value of the Face Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Face Value (Base)</td></tr><tr><td>description</td><td>Value of the Face Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_facevalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the faceValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_facevalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Face Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Face Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#fundId name="fundId">fundId</a>

Unique identifier for Account associated with Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Planned Giving.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fundid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fundId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for Account associated with Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Account.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitCore/Account.cdm.json/Account</a></td><td><a href="Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_fundid"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#givingAmount name="givingAmount">givingAmount</a>

Sum of gifts entered on this record (logic field).  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Amount</td></tr><tr><td>description</td><td>Sum of gifts entered on this record (logic field).</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the givingAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_givingamount"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Giving Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum of gifts entered on this record (logic field).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#givingReceivedDate name="givingReceivedDate">givingReceivedDate</a>

Date distribution or remainder for Planned Giving is received.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Received Date</td></tr><tr><td>description</td><td>Date distribution or remainder for Planned Giving is received.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingreceiveddate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the givingReceivedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_givingreceiveddate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Giving Received Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date distribution or remainder for Planned Giving is received.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#givingSubtype name="givingSubtype">givingSubtype</a>

Specific type of Planned Giving instrument.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Subtype</td></tr><tr><td>description</td><td>Specific type of Planned Giving instrument.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingsubtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Standard Flip</td><td>100000000</td></tr><tr><td>en</td><td>Flip with Makeup</td><td>844060000</td></tr><tr><td>en</td><td>Net Income</td><td>844060001</td></tr><tr><td>en</td><td>Net Income with Makeup</td><td>844060002</td></tr><tr><td>en</td><td>Deferred</td><td>844060003</td></tr><tr><td>en</td><td>Flexible</td><td>844060004</td></tr><tr><td>en</td><td>Grantor</td><td>844060005</td></tr><tr><td>en</td><td>Non Grantor</td><td>844060006</td></tr><tr><td>en</td><td>Regular</td><td>844060007</td></tr><tr><td>en</td><td>Testamentory</td><td>844060008</td></tr><tr><td>en</td><td>Traditional IRA</td><td>844060009</td></tr><tr><td>en</td><td>Roth IRA</td><td>844060010</td></tr><tr><td>en</td><td>403(b)/401k</td><td>844060011</td></tr><tr><td>en</td><td>KEOGH</td><td>844060012</td></tr><tr><td>en</td><td>Other Retirement Plan</td><td>844060013</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the givingSubtype attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Standard Flip</td><td>100000000</td></tr><tr><td>en</td><td>Flip with Makeup</td><td>844060000</td></tr><tr><td>en</td><td>Net Income</td><td>844060001</td></tr><tr><td>en</td><td>Net Income with Makeup</td><td>844060002</td></tr><tr><td>en</td><td>Deferred</td><td>844060003</td></tr><tr><td>en</td><td>Flexible</td><td>844060004</td></tr><tr><td>en</td><td>Grantor</td><td>844060005</td></tr><tr><td>en</td><td>Non Grantor</td><td>844060006</td></tr><tr><td>en</td><td>Regular</td><td>844060007</td></tr><tr><td>en</td><td>Testamentory</td><td>844060008</td></tr><tr><td>en</td><td>Traditional IRA</td><td>844060009</td></tr><tr><td>en</td><td>Roth IRA</td><td>844060010</td></tr><tr><td>en</td><td>403(b)/401k</td><td>844060011</td></tr><tr><td>en</td><td>KEOGH</td><td>844060012</td></tr><tr><td>en</td><td>Other Retirement Plan</td><td>844060013</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_givingsubtype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Giving Subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Specific type of Planned Giving instrument.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#givingSubtype_display name="givingSubtype_display">givingSubtype_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the givingSubtype_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"givingSubtype"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#insuranceAnnualPremium name="insuranceAnnualPremium">insuranceAnnualPremium</a>

Annual Premium of the Life Insurance.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Annual Premium</td></tr><tr><td>description</td><td>Annual Premium of the Life Insurance.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insuranceannualpremium</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insuranceAnnualPremium attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insuranceannualpremium"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Annual Premium</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Annual Premium of the Life Insurance.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#insuranceAnnualPremiumBase name="insuranceAnnualPremiumBase">insuranceAnnualPremiumBase</a>

Value of the Insurance Annual Premium in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Annual Premium (Base)</td></tr><tr><td>description</td><td>Value of the Insurance Annual Premium in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insuranceannualpremium_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insuranceAnnualPremiumBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insuranceannualpremium_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Annual Premium (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Insurance Annual Premium in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#insuranceCompany name="insuranceCompany">insuranceCompany</a>

Insurance Company for related to this Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Company</td></tr><tr><td>description</td><td>Insurance Company for related to this Planned Giving.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancecompany</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insuranceCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancecompany"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"255"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Company for related to this Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#insuranceDeathBenefitAmount name="insuranceDeathBenefitAmount">insuranceDeathBenefitAmount</a>

Death Benefit Amount from Insurance.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Death Benefit Amount</td></tr><tr><td>description</td><td>Death Benefit Amount from Insurance.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancedeathbenefitamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insuranceDeathBenefitAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancedeathbenefitamount"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Death Benefit Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Death Benefit Amount from Insurance.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#insurancePolicyCode name="insurancePolicyCode">insurancePolicyCode</a>

Insurance policy code related to this Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Policy Code</td></tr><tr><td>description</td><td>Insurance policy code related to this Planned Giving.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepolicycode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insurancePolicyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancepolicycode"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"255"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Policy Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance policy code related to this Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#insurancePolicyName name="insurancePolicyName">insurancePolicyName</a>

Insurance Policy Name for this Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Policy Name</td></tr><tr><td>description</td><td>Insurance Policy Name for this Planned Giving.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepolicyname</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insurancePolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.identity.name**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancepolicyname"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"1024"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Policy Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Policy Name for this Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#insurancePremiumDueDate name="insurancePremiumDueDate">insurancePremiumDueDate</a>

Insurance Premium Due Date related to this Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Premium Due Date</td></tr><tr><td>description</td><td>Insurance Premium Due Date related to this Planned Giving record.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepremiumduedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insurancePremiumDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancepremiumduedate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Premium Due Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Premium Due Date related to this Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#insurancePremiumPaymentAddress name="insurancePremiumPaymentAddress">insurancePremiumPaymentAddress</a>

Address for the Life Insurance Premium Payment.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Premium Payment Address</td></tr><tr><td>description</td><td>Address for the Life Insurance Premium Payment.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepremiumpaymentaddress</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insurancePremiumPaymentAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_insurancepremiumpaymentaddress"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"1024"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance Premium Payment Address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address for the Life Insurance Premium Payment.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#isRevocable name="isRevocable">isRevocable</a>

Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revocable</td></tr><tr><td>description</td><td>Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.</td></tr><tr><td>dataFormat</td><td>15</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isrevocable</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isRevocable attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_isrevocable"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Revocable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.boolean**  
</details>

### <a href=#leadSource name="leadSource">leadSource</a>

Method of communication that prompted Donor to discuss Planned Giving options.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead Source</td></tr><tr><td>description</td><td>Method of communication that prompted Donor to discuss Planned Giving options.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_leadsource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Direct Mail</td><td>100000000</td></tr><tr><td>en</td><td>E-Mail</td><td>844060000</td></tr><tr><td>en</td><td>Other</td><td>844060001</td></tr><tr><td>en</td><td>Phone In</td><td>844060002</td></tr><tr><td>en</td><td>Print Ad</td><td>844060003</td></tr><tr><td>en</td><td>Referral</td><td>844060004</td></tr><tr><td>en</td><td>Special Event</td><td>844060005</td></tr><tr><td>en</td><td>TV Promo</td><td>844060006</td></tr><tr><td>en</td><td>Web Site</td><td>844060007</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the leadSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Direct Mail</td><td>100000000</td></tr><tr><td>en</td><td>E-Mail</td><td>844060000</td></tr><tr><td>en</td><td>Other</td><td>844060001</td></tr><tr><td>en</td><td>Phone In</td><td>844060002</td></tr><tr><td>en</td><td>Print Ad</td><td>844060003</td></tr><tr><td>en</td><td>Referral</td><td>844060004</td></tr><tr><td>en</td><td>Special Event</td><td>844060005</td></tr><tr><td>en</td><td>TV Promo</td><td>844060006</td></tr><tr><td>en</td><td>Web Site</td><td>844060007</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_leadsource"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lead Source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Method of communication that prompted Donor to discuss Planned Giving options.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#leadSource_display name="leadSource_display">leadSource_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the leadSource_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"leadSource"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.identity.name**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_name"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"160"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"required"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ordinaryIncome name="ordinaryIncome">ordinaryIncome</a>

Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordinary Income</td></tr><tr><td>description</td><td>Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ordinaryincome</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ordinaryIncome attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_ordinaryincome"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ordinary Income</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ordinaryIncomeBase name="ordinaryIncomeBase">ordinaryIncomeBase</a>

Value of the Ordinary Income in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordinary Income (Base)</td></tr><tr><td>description</td><td>Value of the Ordinary Income in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ordinaryincome_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ordinaryIncomeBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_ordinaryincome_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ordinary Income (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Ordinary Income in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#paymentFrequency name="paymentFrequency">paymentFrequency</a>

Defined frequency payments are distributed to the organization.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Frequency</td></tr><tr><td>description</td><td>Defined frequency payments are distributed to the organization.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentfrequency</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Monthly</td><td>100000000</td></tr><tr><td>en</td><td>Quarterly</td><td>844060000</td></tr><tr><td>en</td><td>Annually</td><td>844060001</td></tr><tr><td>en</td><td>Semi-Annually</td><td>844060002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the paymentFrequency attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Monthly</td><td>100000000</td></tr><tr><td>en</td><td>Quarterly</td><td>844060000</td></tr><tr><td>en</td><td>Annually</td><td>844060001</td></tr><tr><td>en</td><td>Semi-Annually</td><td>844060002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_paymentfrequency"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment Frequency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Defined frequency payments are distributed to the organization.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#paymentFrequency_display name="paymentFrequency_display">paymentFrequency_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the paymentFrequency_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"paymentFrequency"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#payoutRate name="payoutRate">payoutRate</a>

Dollar amount per share a Corporation pays for their dividend.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payout Rate</td></tr><tr><td>description</td><td>Dollar amount per share a Corporation pays for their dividend.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_payoutrate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the payoutRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_payoutrate"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payout Rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dollar amount per share a Corporation pays for their dividend.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#plannedGivingPledgedByContactId name="plannedGivingPledgedByContactId">plannedGivingPledgedByContactId</a>

Pledged By Contact  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged By Contact</td></tr><tr><td>description</td><td>Pledged By Contact</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_plannedgiving_pledgedbycontactid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the plannedGivingPledgedByContactId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pledged By Contact</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pledged By Contact</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Contact.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitCore/Contact.cdm.json/Contact</a></td><td><a href="Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_plannedgiving_pledgedbycontactid"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#plannedGivingId name="plannedGivingId">plannedGivingId</a>

Unique identifier for entity instances  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Giving</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>sourceName</td><td>msnfp_plannedgivingid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the plannedGivingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PlannedGiving/(resolvedAttributes)/plannedGivingId](#plannedGivingId)</td><td>attribute</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_plannedgivingid"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned Giving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pledgesOnAccountId name="pledgesOnAccountId">pledgesOnAccountId</a>

Unique identifier for Account associated with Planned Giving.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledges On Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Planned Giving.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_pledgesonaccountid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pledgesOnAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pledges On Account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for Account associated with Planned Giving.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Account.md" target="_blank">/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/nonProfitCore/Account.cdm.json/Account</a></td><td><a href="Account.md#accountId" target="_blank">accountId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_pledgesonaccountid"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#presentValue name="presentValue">presentValue</a>

The value on a given date of a payment or series of payments made at other times for an investment.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Present Value</td></tr><tr><td>description</td><td>The value on a given date of a payment or series of payments made at other times for an investment.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_presentvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the presentValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_presentvalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Present Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The value on a given date of a payment or series of payments made at other times for an investment.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#presentValueBase name="presentValueBase">presentValueBase</a>

Value of the Present Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Present Value (Base)</td></tr><tr><td>description</td><td>Value of the Present Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_presentvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the presentValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_presentvalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Present Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Present Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#recordType name="recordType">recordType</a>

Type of Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Type</td></tr><tr><td>description</td><td>Type of Planned Giving record.</td></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recordtype</td></tr></table>

#### Traits

<details>
<summary>List of traits for the recordType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_recordtype"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"255"</td><td>integer</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#remainderAmount name="remainderAmount">remainderAmount</a>

Remainder $ value a Charitable Organization receives.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remainder Amount</td></tr><tr><td>description</td><td>Remainder $ value a Charitable Organization receives.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_remainderamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the remainderAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_remainderamount"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remainder Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remainder $ value a Charitable Organization receives.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#remainderAmountBase name="remainderAmountBase">remainderAmountBase</a>

Value of the Remainder Amount in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remainder Amount (Base)</td></tr><tr><td>description</td><td>Value of the Remainder Amount in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_remainderamount_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the remainderAmountBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_remainderamount_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remainder Amount (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Remainder Amount in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#rollupGiving name="rollupGiving">rollupGiving</a>

Populated by trigger, reflects the most recent Date/Time for Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Giving</td></tr><tr><td>description</td><td>Populated by trigger, reflects the most recent Date/Time for Giving record.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_rollupgiving</td></tr></table>

#### Traits

<details>
<summary>List of traits for the rollupGiving attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_rollupgiving"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Giving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Populated by trigger, reflects the most recent Date/Time for Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#salvageValueOfBuildings name="salvageValueOfBuildings">salvageValueOfBuildings</a>

Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salvage Value of Buildings</td></tr><tr><td>description</td><td>Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_salvagevalueofbuildings</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salvageValueOfBuildings attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_salvagevalueofbuildings"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Salvage Value of Buildings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#salvageValueOfBuildingsBase name="salvageValueOfBuildingsBase">salvageValueOfBuildingsBase</a>

Value of the Salvage Value of Buildings in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salvage Value of Buildings (Base)</td></tr><tr><td>description</td><td>Value of the Salvage Value of Buildings in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_salvagevalueofbuildings_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salvageValueOfBuildingsBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_salvagevalueofbuildings_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Salvage Value of Buildings (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Salvage Value of Buildings in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#severDate name="severDate">severDate</a>

The term end date' or the date of the related Contact's death.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sever Date</td></tr><tr><td>description</td><td>The term end date' or the date of the related Contact's death.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_severdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the severDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_severdate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sever Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The term end date' or the date of the related Contact's death.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#stage name="stage">stage</a>

The current phase the giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage</td></tr><tr><td>description</td><td>The current phase the giving record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_stage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>100000000</td></tr><tr><td>en</td><td>Cultivating</td><td>844060000</td></tr><tr><td>en</td><td>Intention</td><td>844060001</td></tr><tr><td>en</td><td>Anonymous</td><td>844060002</td></tr><tr><td>en</td><td>Very Contingent</td><td>844060003</td></tr><tr><td>en</td><td>Language Requested</td><td>844060004</td></tr><tr><td>en</td><td>Matured</td><td>844060005</td></tr><tr><td>en</td><td>Claim administration process</td><td>844060006</td></tr><tr><td>en</td><td>Pending</td><td>844060007</td></tr><tr><td>en</td><td>Estate in Probate</td><td>844060008</td></tr><tr><td>en</td><td>Final Distribution</td><td>844060009</td></tr><tr><td>en</td><td>Finished</td><td>844060010</td></tr><tr><td>en</td><td>Severed</td><td>844060011</td></tr><tr><td>en</td><td>Inactive</td><td>844060012</td></tr><tr><td>en</td><td>Estate in Administration process</td><td>844060013</td></tr><tr><td>en</td><td>1st spouse deceased</td><td>844060014</td></tr><tr><td>en</td><td>Termination processing</td><td>844060015</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stage attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>100000000</td></tr><tr><td>en</td><td>Cultivating</td><td>844060000</td></tr><tr><td>en</td><td>Intention</td><td>844060001</td></tr><tr><td>en</td><td>Anonymous</td><td>844060002</td></tr><tr><td>en</td><td>Very Contingent</td><td>844060003</td></tr><tr><td>en</td><td>Language Requested</td><td>844060004</td></tr><tr><td>en</td><td>Matured</td><td>844060005</td></tr><tr><td>en</td><td>Claim administration process</td><td>844060006</td></tr><tr><td>en</td><td>Pending</td><td>844060007</td></tr><tr><td>en</td><td>Estate in Probate</td><td>844060008</td></tr><tr><td>en</td><td>Final Distribution</td><td>844060009</td></tr><tr><td>en</td><td>Finished</td><td>844060010</td></tr><tr><td>en</td><td>Severed</td><td>844060011</td></tr><tr><td>en</td><td>Inactive</td><td>844060012</td></tr><tr><td>en</td><td>Estate in Administration process</td><td>844060013</td></tr><tr><td>en</td><td>1st spouse deceased</td><td>844060014</td></tr><tr><td>en</td><td>Termination processing</td><td>844060015</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_stage"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The current phase the giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#stage_display name="stage_display">stage_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stage_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"stage"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#taxFreeIncome name="taxFreeIncome">taxFreeIncome</a>

The tax free income from the asset related to this giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Free Income</td></tr><tr><td>description</td><td>The tax free income from the asset related to this giving record.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_taxfreeincome</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taxFreeIncome attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_taxfreeincome"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Free Income</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The tax free income from the asset related to this giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#taxFreeIncomeBase name="taxFreeIncomeBase">taxFreeIncomeBase</a>

Value of the Tax Free Income in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Free Income (Base)</td></tr><tr><td>description</td><td>Value of the Tax Free Income in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_taxfreeincome_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taxFreeIncomeBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_taxfreeincome_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Free Income (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Tax Free Income in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#termEndDate name="termEndDate">termEndDate</a>

Term end date for the asset related to the Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term End Date</td></tr><tr><td>description</td><td>Term end date for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termenddate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the termEndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_termenddate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term End Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term end date for the asset related to the Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#termType name="termType">termType</a>

Term type for the asset related to the Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term Type</td></tr><tr><td>description</td><td>Term type for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Lives only</td><td>100000000</td></tr><tr><td>en</td><td>Fixed term only</td><td>844060000</td></tr><tr><td>en</td><td>Longer of term or lives</td><td>844060001</td></tr><tr><td>en</td><td>Shorter of term or lives</td><td>844060002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the termType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Lives only</td><td>100000000</td></tr><tr><td>en</td><td>Fixed term only</td><td>844060000</td></tr><tr><td>en</td><td>Longer of term or lives</td><td>844060001</td></tr><tr><td>en</td><td>Shorter of term or lives</td><td>844060002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_termtype"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term type for the asset related to the Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#termType_display name="termType_display">termType_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the termType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"termType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#termYears name="termYears">termYears</a>

Term years for the asset related to the Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term Years</td></tr><tr><td>description</td><td>Term years for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termyears</td></tr></table>

#### Traits

<details>
<summary>List of traits for the termYears attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_termyears"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term Years</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Term years for the asset related to the Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#totalEstateValue name="totalEstateValue">totalEstateValue</a>

Total Estate Value as provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Estate Value</td></tr><tr><td>description</td><td>Total Estate Value as provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalestatevalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalEstateValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_totalestatevalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total Estate Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total Estate Value as provided by executor, trustee or attorney or in estate documentation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#totalEstateValueBase name="totalEstateValueBase">totalEstateValueBase</a>

Value of the Total Estate Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Estate Value (Base)</td></tr><tr><td>description</td><td>Value of the Total Estate Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalestatevalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalEstateValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_totalestatevalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total Estate Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Total Estate Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#trustMarketValue name="trustMarketValue">trustMarketValue</a>

Trust Market Value related to this planned giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Market Value</td></tr><tr><td>description</td><td>Trust Market Value related to this planned giving record.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustmarketvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the trustMarketValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_trustmarketvalue"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"1000000000"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust Market Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust Market Value related to this planned giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#trustMarketValueBase name="trustMarketValueBase">trustMarketValueBase</a>

Value of the Trust Market Value in base currency.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Market Value (Base)</td></tr><tr><td>description</td><td>Value of the Trust Market Value in base currency.</td></tr><tr><td>dataFormat</td><td>16</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustmarketvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the trustMarketValueBase attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**means.measurement.currency**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_trustmarketvalue_base"</td><td>string</td><td></td></tr></table>

**is.constrained**  
maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-922337203685477"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"922337203685477"</td><td>decimal</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust Market Value (Base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the Trust Market Value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#trustProbateNoticeDate name="trustProbateNoticeDate">trustProbateNoticeDate</a>

Date Trust/Probate Notice received.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust/Probate Notice Date</td></tr><tr><td>description</td><td>Date Trust/Probate Notice received.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustprobatenoticedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the trustProbateNoticeDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_trustprobatenoticedate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust/Probate Notice Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Trust/Probate Notice received.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#trustValueDate name="trustValueDate">trustValueDate</a>

Trust Value Date related to this planned giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Value Date</td></tr><tr><td>description</td><td>Trust Value Date related to this planned giving record.</td></tr><tr><td>dataFormat</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustvaluedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the trustValueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.time**  
**means.measurement.time**  
**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_trustvaluedate"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust Value Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trust Value Date related to this planned giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
**is.dataFormat.date**  
</details>

### <a href=#typeOfManagement name="typeOfManagement">typeOfManagement</a>

The type of management for the underlying asset or assets related to this Planned Giving record.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type of Management</td></tr><tr><td>description</td><td>The type of management for the underlying asset or assets related to this Planned Giving record.</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_typeofmanagement</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inside</td><td>100000000</td></tr><tr><td>en</td><td>Outside - donor self-trustee</td><td>100000001</td></tr><tr><td>en</td><td>Outside - Institution or other trusteem
Outside</td><td>100000002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the typeOfManagement attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inside</td><td>100000000</td></tr><tr><td>en</td><td>Outside - donor self-trustee</td><td>100000001</td></tr><tr><td>en</td><td>Outside - Institution or other trusteem
Outside</td><td>100000002</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msnfp_typeofmanagement"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of Management</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of management for the underlying asset or assets related to this Planned Giving record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#typeOfManagement_display name="typeOfManagement_display">typeOfManagement_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the typeOfManagement_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"typeOfManagement"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Planned Giving  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Planned Giving</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**means.entityState**  
the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PlannedGiving/(resolvedAttributes)/stateCode](#stateCode)</td><td>attribute</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Planned Giving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"stateCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Planned Giving  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Planned Giving</td></tr><tr><td>dataFormat</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.correlatedWith**  
the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"stateCode"</td><td>attributeName</td><td></td></tr></table>

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Planned Giving</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"statusCode"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfitCore/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>6</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionCurrencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.CDS.lookup**  
The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

**is.requiredAtLevel**  
The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the currency associated with the entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../../Currency.md" target="_blank">/core/applicationCommon/Currency.cdm.json/Currency</a></td><td><a href="../../../../../Currency.md#transactionCurrencyId" target="_blank">transactionCurrencyId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.nullable**  
The attribute value may be set to NULL.  

**is.CDS.sourceNamed**  
the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"transactioncurrencyid"</td><td>string</td><td></td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
