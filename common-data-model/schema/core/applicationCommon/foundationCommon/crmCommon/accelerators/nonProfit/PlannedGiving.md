---
title: PlannedGiving - Common Data Model | Microsoft Docs
description: This describes the PlannedGiving entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Planned Giving

A planned gift is a major gift that's made during a donor's lifetime or at the time of their death and that involves their estate and tax planning.  There are many forms of planned giving, but the three most common vehicles are CRTs (Charitable Remainder Trusts), bequests, and annuities, which all have different tax benefits and financial-reconciliation guidelines for the nonprofit organization. Planned gifts are in contrast to annual gifts, which are made through a donor's discretionary income and not tied to an estate.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/PlannedGiving.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/PlannedGiving  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[plannedGivingId](#plannedGivingId)|Unique identifier for entity instances|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[stateCode](#stateCode)|Status of the Planned Giving|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[stateCode_display](#stateCode_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[statusCode](#statusCode)|Reason for the status of the Planned Giving|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[statusCode_display](#statusCode_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[name](#name)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[actualPercentOfEstateRecieved](#actualPercentOfEstateRecieved)|Actual percent of donor estate received by organization|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[affiliation](#affiliation)|Represents groups within the organization.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[affiliation_display](#affiliation_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[amountPerFrequency](#amountPerFrequency)|Amount distributed to organization per defined frequency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[amountperfrequencyBase](#amountperfrequencyBase)|Value of the Amount Per Frequency in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[annualMarketValue](#annualMarketValue)|Annual Market Value provided by official valuation source such as Kaspick.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[annualmarketvalueBase](#annualmarketvalueBase)|Value of the Annual Market Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[annualMarketValueDate](#annualMarketValueDate)|Date Annual Market Value provided by official valuation source such as Kaspick.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[annualPayment](#annualPayment)|Annual Payment to organization.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[annualpaymentBase](#annualpaymentBase)|Value of the Annual Payment in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[anticipatedAnnualPayment](#anticipatedAnnualPayment)|Anticipated Annual Payment to organization.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[anticipatedannualpaymentBase](#anticipatedannualpaymentBase)|Value of the Anticipated Annual Payment in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[anticipatedDistributionDateOfTrust](#anticipatedDistributionDateOfTrust)|Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[anticipatedPercentOfTrust](#anticipatedPercentOfTrust)|Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[appraisalDate](#appraisalDate)|Date the appraisal was conducted.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[appraisalValue](#appraisalValue)|Value of the appraised item or asset from qualified appraiser|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[appraisalvalueBase](#appraisalvalueBase)|Value of the Appraisal Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[bequestType](#bequestType)|Is the Bequest a Living Trust, Will, or both?|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[bequestType_display](#bequestType_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[capitalGainIncome](#capitalGainIncome)|Beneficiary's taxable capital gain income portion of life insurance income.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[capitalgainincomeBase](#capitalgainincomeBase)|Value of the Capital Gain Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[cashSurrenderValue](#cashSurrenderValue)|The current Cash Surrender Value of the insurance policy.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[cashsurrendervalueBase](#cashsurrendervalueBase)|Value of the Cash Surrender Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[charitableDeduction](#charitableDeduction)|Calculated Charitable Deduction for Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[charitabledeductionBase](#charitabledeductionBase)|Value of the Charitable Deduction in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[contractDate](#contractDate)|Date funding will start as specified on the Contract.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[costBasis](#costBasis)|Original purchase price of funding asset.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[costbasisBase](#costbasisBase)|Value of the Cost Basis in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateClaimFormsRecieved](#dateClaimFormsRecieved)|Date Claim Forms Received.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateClaimFormsSubmitted](#dateClaimFormsSubmitted)|Date Claim Forms Submitted.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateEstateClosed](#dateEstateClosed)|Date a management agreement is signed as provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateManagementAgreementSigned](#dateManagementAgreementSigned)|Date a management agreement is signed as provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateStationNotifiedOfDeath](#dateStationNotifiedOfDeath)|Date your organization is notified of the donor's death.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateStationNotifiedOfIntention](#dateStationNotifiedOfIntention)|Date organization Notified of Intention to give a Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateStationNotifiedToMakeClaim](#dateStationNotifiedToMakeClaim)|Date Organization notified to make a claim.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[dateWillExecuted](#dateWillExecuted)|Date Will Executed as provided in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceased](#deceased)|Indicates the Contact is Deceased.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedDay](#deceasedDay)|Day the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedDay_display](#deceasedDay_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedMonth](#deceasedMonth)|Month the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedMonth_display](#deceasedMonth_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedYear](#deceasedYear)|Year the Contact was deceased.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deceasedYear_display](#deceasedYear_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[deferredToDate](#deferredToDate)|Same as date of first payment when more than one year after the contract date.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[designatedOrganizationPercent](#designatedOrganizationPercent)|Percent of remainder designated to organization|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[designatedPrincipleAmount](#designatedPrincipleAmount)|Amount of principle designated to organization.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[designatedprincipleamountBase](#designatedprincipleamountBase)|Value of the Designated Principle Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[designation](#designation)|Usage of gift funds will be unrestricted, restricted or permanently restricted.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[designation_display](#designation_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[discountRate](#discountRate)|Interest rate a central bank charges depository institutions that borrow reserves from it.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[discountRateMonth](#discountRateMonth)|Month in which latest Discount Rate was populated.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[discountRateMonth_display](#discountRateMonth_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[discountRateYear](#discountRateYear)|Year in which latest Discount Rate was populated.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[discountRateYear_display](#discountRateYear_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[endowmentType](#endowmentType)|Specific endowment at organization where gift will be applied.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[endowmentType_display](#endowmentType_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[estimatedGivingAmount](#estimatedGivingAmount)|Estimated amount organization will receive as provided by executor, trustee, or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[estimatedgivingamountBase](#estimatedgivingamountBase)|Value of the Estimated Giving Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[estimatedTrustProbateDate](#estimatedTrustProbateDate)|Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[expectedFinalDistributionDate](#expectedFinalDistributionDate)|Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[expectedFirstDistributionDate](#expectedFirstDistributionDate)|Expected Date of First Distribution, typically information provided by executor, trustee or attorney.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[externalID](#externalID)|ID from External or Legacy system.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[faceValue](#faceValue)|Value of funds donated.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[facevalueBase](#facevalueBase)|Value of the Face Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[fundId](#fundId)|Unique identifier for Account associated with Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[givingAmount](#givingAmount)|Sum of gifts entered on this record (logic field).|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[givingReceivedDate](#givingReceivedDate)|Date distribution or remainder for Planned Giving is received.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[givingSubtype](#givingSubtype)|Specific type of Planned Giving instrument.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[givingSubtype_display](#givingSubtype_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insuranceAnnualPremium](#insuranceAnnualPremium)|Annual Premium of the Life Insurance.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insuranceannualpremiumBase](#insuranceannualpremiumBase)|Value of the Insurance Annual Premium in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insuranceCompany](#insuranceCompany)|Insurance Company for related to this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insuranceDeathBenefitAmount](#insuranceDeathBenefitAmount)|Death Benefit Amount from Insurance.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insurancePolicyCode](#insurancePolicyCode)|Insurance policy code related to this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insurancePolicyName](#insurancePolicyName)|Insurance Policy Name for this Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insurancePremiumDueDate](#insurancePremiumDueDate)|Insurance Premium Due Date related to this Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[insurancePremiumPaymentAddress](#insurancePremiumPaymentAddress)|Address for the Life Insurance Premium Payment.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[isRevocable](#isRevocable)|Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[leadSource](#leadSource)|Method of communication that prompted Donor to discuss Planned Giving options.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[leadSource_display](#leadSource_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[ordinaryIncome](#ordinaryIncome)|Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[ordinaryincomeBase](#ordinaryincomeBase)|Value of the Ordinary Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[paymentFrequency](#paymentFrequency)|Defined frequency payments are distributed to the organization.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[paymentFrequency_display](#paymentFrequency_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[payoutRate](#payoutRate)|Dollar amount per share a Corporation pays for their dividend.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[plannedGivingCampaignId](#plannedGivingCampaignId)|Campaign|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[plannedGivingPledgedByContactId](#plannedGivingPledgedByContactId)|Pledged By Contact|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[pledgesOnAccountId](#pledgesOnAccountId)|Unique identifier for Account associated with Planned Giving.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[presentValue](#presentValue)|The value on a given date of a payment or series of payments made at other times for an investment.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[presentvalueBase](#presentvalueBase)|Value of the Present Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[recordType](#recordType)|Type of Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[remainderAmount](#remainderAmount)|Remainder $ value a Charitable Organization receives.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[remainderamountBase](#remainderamountBase)|Value of the Remainder Amount in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[rollupGiving](#rollupGiving)|Populated by trigger, reflects the most recent Date/Time for Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[salvageValueofBuildings](#salvageValueofBuildings)|Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[salvagevalueofbuildingsBase](#salvagevalueofbuildingsBase)|Value of the Salvage Value of Buildings in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[severDate](#severDate)|The term end date' or the date of the related Contact's death.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[stage](#stage)|The current phase the giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[stage_display](#stage_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[taxFreeIncome](#taxFreeIncome)|The tax free income from the asset related to this giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[taxfreeincomeBase](#taxfreeincomeBase)|Value of the Tax Free Income in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[termEndDate](#termEndDate)|Term end date for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[termType](#termType)|Term type for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[termType_display](#termType_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[termYears](#termYears)|Term years for the asset related to the Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[totalEstateValue](#totalEstateValue)|Total Estate Value as provided by executor, trustee or attorney or in estate documentation.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[totalestatevalueBase](#totalestatevalueBase)|Value of the Total Estate Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[trustMarketValue](#trustMarketValue)|Trust Market Value related to this planned giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[trustmarketvalueBase](#trustmarketvalueBase)|Value of the Trust Market Value in base currency.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[trustProbateNoticeDate](#trustProbateNoticeDate)|Date Trust/Probate Notice received.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[trustValueDate](#trustValueDate)|Trust Value Date related to this planned giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[typeOfManagement](#typeOfManagement)|The type of management for the underlying asset or assets related to this Planned Giving record.|<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|
|[typeOfManagement_display](#typeOfManagement_display)||<a href="PlannedGiving.md" target="_blank">nonProfit/PlannedGiving</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#plannedGivingId name="plannedGivingId">plannedGivingId</a>

Unique identifier for entity instances  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Giving</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_plannedgivingid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Planned Giving  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Planned Giving</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Planned Giving  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Planned Giving</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#actualPercentOfEstateRecieved name="actualPercentOfEstateRecieved">actualPercentOfEstateRecieved</a>

Actual percent of donor estate received by organization  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual % of Estate Received</td></tr><tr><td>description</td><td>Actual percent of donor estate received by organization</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_actualpercentofestaterecieved</td></tr></table>

### <a href=#affiliation name="affiliation">affiliation</a>

Represents groups within the organization.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Affiliation</td></tr><tr><td>description</td><td>Represents groups within the organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_affiliation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>NGO</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#affiliation_display name="affiliation_display">affiliation_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amountPerFrequency name="amountPerFrequency">amountPerFrequency</a>

Amount distributed to organization per defined frequency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Per Frequency</td></tr><tr><td>description</td><td>Amount distributed to organization per defined frequency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountperfrequency</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountperfrequencyBase name="amountperfrequencyBase">amountperfrequencyBase</a>

Value of the Amount Per Frequency in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Per Frequency (Base)</td></tr><tr><td>description</td><td>Value of the Amount Per Frequency in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amountperfrequency_base</td></tr></table>

### <a href=#annualMarketValue name="annualMarketValue">annualMarketValue</a>

Annual Market Value provided by official valuation source such as Kaspick.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value</td></tr><tr><td>description</td><td>Annual Market Value provided by official valuation source such as Kaspick.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvalue</td></tr></table>

### <a href=#annualmarketvalueBase name="annualmarketvalueBase">annualmarketvalueBase</a>

Value of the Annual Market Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value (Base)</td></tr><tr><td>description</td><td>Value of the Annual Market Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvalue_base</td></tr></table>

### <a href=#annualMarketValueDate name="annualMarketValueDate">annualMarketValueDate</a>

Date Annual Market Value provided by official valuation source such as Kaspick.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Market Value Date</td></tr><tr><td>description</td><td>Date Annual Market Value provided by official valuation source such as Kaspick.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualmarketvaluedate</td></tr></table>

### <a href=#annualPayment name="annualPayment">annualPayment</a>

Annual Payment to organization.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Payment</td></tr><tr><td>description</td><td>Annual Payment to organization.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualpayment</td></tr></table>

### <a href=#annualpaymentBase name="annualpaymentBase">annualpaymentBase</a>

Value of the Annual Payment in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Payment (Base)</td></tr><tr><td>description</td><td>Value of the Annual Payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_annualpayment_base</td></tr></table>

### <a href=#anticipatedAnnualPayment name="anticipatedAnnualPayment">anticipatedAnnualPayment</a>

Anticipated Annual Payment to organization.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Annual Payment</td></tr><tr><td>description</td><td>Anticipated Annual Payment to organization.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedannualpayment</td></tr></table>

### <a href=#anticipatedannualpaymentBase name="anticipatedannualpaymentBase">anticipatedannualpaymentBase</a>

Value of the Anticipated Annual Payment in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Annual Payment (Base)</td></tr><tr><td>description</td><td>Value of the Anticipated Annual Payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedannualpayment_base</td></tr></table>

### <a href=#anticipatedDistributionDateOfTrust name="anticipatedDistributionDateOfTrust">anticipatedDistributionDateOfTrust</a>

Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated Distribution Date of Trust</td></tr><tr><td>description</td><td>Anticipated distribution date of trust typically provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipateddistributiondateoftrust</td></tr></table>

### <a href=#anticipatedPercentOfTrust name="anticipatedPercentOfTrust">anticipatedPercentOfTrust</a>

Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipated % of Trust</td></tr><tr><td>description</td><td>Anticipated percent of trust that will go to the organization. This is typically provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anticipatedpercentoftrust</td></tr></table>

### <a href=#appraisalDate name="appraisalDate">appraisalDate</a>

Date the appraisal was conducted.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Date</td></tr><tr><td>description</td><td>Date the appraisal was conducted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisaldate</td></tr></table>

### <a href=#appraisalValue name="appraisalValue">appraisalValue</a>

Value of the appraised item or asset from qualified appraiser  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Value</td></tr><tr><td>description</td><td>Value of the appraised item or asset from qualified appraiser</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisalvalue</td></tr></table>

### <a href=#appraisalvalueBase name="appraisalvalueBase">appraisalvalueBase</a>

Value of the Appraisal Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appraisal Value (Base)</td></tr><tr><td>description</td><td>Value of the Appraisal Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_appraisalvalue_base</td></tr></table>

### <a href=#bequestType name="bequestType">bequestType</a>

Is the Bequest a Living Trust, Will, or both?  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bequest Type</td></tr><tr><td>description</td><td>Is the Bequest a Living Trust, Will, or both?</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bequesttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Living Trust</td><td>100000000</td></tr><tr><td>en</td><td>Will</td><td>100000001</td></tr><tr><td>en</td><td>Living Trust and Will</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#bequestType_display name="bequestType_display">bequestType_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#capitalGainIncome name="capitalGainIncome">capitalGainIncome</a>

Beneficiary's taxable capital gain income portion of life insurance income.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Gain Income</td></tr><tr><td>description</td><td>Beneficiary's taxable capital gain income portion of life insurance income.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_capitalgainincome</td></tr></table>

### <a href=#capitalgainincomeBase name="capitalgainincomeBase">capitalgainincomeBase</a>

Value of the Capital Gain Income in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Gain Income (Base)</td></tr><tr><td>description</td><td>Value of the Capital Gain Income in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_capitalgainincome_base</td></tr></table>

### <a href=#cashSurrenderValue name="cashSurrenderValue">cashSurrenderValue</a>

The current Cash Surrender Value of the insurance policy.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash Surrender Value</td></tr><tr><td>description</td><td>The current Cash Surrender Value of the insurance policy.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_cashsurrendervalue</td></tr></table>

### <a href=#cashsurrendervalueBase name="cashsurrendervalueBase">cashsurrendervalueBase</a>

Value of the Cash Surrender Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash Surrender Value (Base)</td></tr><tr><td>description</td><td>Value of the Cash Surrender Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_cashsurrendervalue_base</td></tr></table>

### <a href=#charitableDeduction name="charitableDeduction">charitableDeduction</a>

Calculated Charitable Deduction for Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charitable Deduction</td></tr><tr><td>description</td><td>Calculated Charitable Deduction for Planned Giving.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_charitablededuction</td></tr></table>

### <a href=#charitabledeductionBase name="charitabledeductionBase">charitabledeductionBase</a>

Value of the Charitable Deduction in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Charitable Deduction (Base)</td></tr><tr><td>description</td><td>Value of the Charitable Deduction in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_charitablededuction_base</td></tr></table>

### <a href=#contractDate name="contractDate">contractDate</a>

Date funding will start as specified on the Contract.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Date</td></tr><tr><td>description</td><td>Date funding will start as specified on the Contract.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_contractdate</td></tr></table>

### <a href=#costBasis name="costBasis">costBasis</a>

Original purchase price of funding asset.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Basis</td></tr><tr><td>description</td><td>Original purchase price of funding asset.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_costbasis</td></tr></table>

### <a href=#costbasisBase name="costbasisBase">costbasisBase</a>

Value of the Cost Basis in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Basis (Base)</td></tr><tr><td>description</td><td>Value of the Cost Basis in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_costbasis_base</td></tr></table>

### <a href=#dateClaimFormsRecieved name="dateClaimFormsRecieved">dateClaimFormsRecieved</a>

Date Claim Forms Received.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Claim Forms Received</td></tr><tr><td>description</td><td>Date Claim Forms Received.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateclaimformsrecieved</td></tr></table>

### <a href=#dateClaimFormsSubmitted name="dateClaimFormsSubmitted">dateClaimFormsSubmitted</a>

Date Claim Forms Submitted.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Claim Forms Submitted</td></tr><tr><td>description</td><td>Date Claim Forms Submitted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateclaimformssubmitted</td></tr></table>

### <a href=#dateEstateClosed name="dateEstateClosed">dateEstateClosed</a>

Date a management agreement is signed as provided by executor, trustee or attorney.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Estate Closed</td></tr><tr><td>description</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dateestateclosed</td></tr></table>

### <a href=#dateManagementAgreementSigned name="dateManagementAgreementSigned">dateManagementAgreementSigned</a>

Date a management agreement is signed as provided by executor, trustee or attorney.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Management Agreement Signed</td></tr><tr><td>description</td><td>Date a management agreement is signed as provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datemanagementagreementsigned</td></tr></table>

### <a href=#dateStationNotifiedOfDeath name="dateStationNotifiedOfDeath">dateStationNotifiedOfDeath</a>

Date your organization is notified of the donor's death.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified of Death</td></tr><tr><td>description</td><td>Date your organization is notified of the donor's death.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedofdeath</td></tr></table>

### <a href=#dateStationNotifiedOfIntention name="dateStationNotifiedOfIntention">dateStationNotifiedOfIntention</a>

Date organization Notified of Intention to give a Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified of Intention</td></tr><tr><td>description</td><td>Date organization Notified of Intention to give a Planned Giving.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedofintention</td></tr></table>

### <a href=#dateStationNotifiedToMakeClaim name="dateStationNotifiedToMakeClaim">dateStationNotifiedToMakeClaim</a>

Date Organization notified to make a claim.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Organization Notified to Make Claim</td></tr><tr><td>description</td><td>Date Organization notified to make a claim.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datestationnotifiedtomakeclaim</td></tr></table>

### <a href=#dateWillExecuted name="dateWillExecuted">dateWillExecuted</a>

Date Will Executed as provided in estate documentation.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Will Executed</td></tr><tr><td>description</td><td>Date Will Executed as provided in estate documentation.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_datewillexecuted</td></tr></table>

### <a href=#deceased name="deceased">deceased</a>

Indicates the Contact is Deceased.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased?</td></tr><tr><td>description</td><td>Indicates the Contact is Deceased.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceased</td></tr></table>

### <a href=#deceasedDay name="deceasedDay">deceasedDay</a>

Day the Contact was deceased.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Day</td></tr><tr><td>description</td><td>Day the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01</td><td>100000000</td></tr><tr><td>en</td><td>02</td><td>100000001</td></tr><tr><td>en</td><td>03</td><td>100000002</td></tr><tr><td>en</td><td>04</td><td>100000003</td></tr><tr><td>en</td><td>05</td><td>100000004</td></tr><tr><td>en</td><td>06</td><td>100000005</td></tr><tr><td>en</td><td>07</td><td>100000006</td></tr><tr><td>en</td><td>08</td><td>100000007</td></tr><tr><td>en</td><td>09</td><td>100000008</td></tr><tr><td>en</td><td>10</td><td>100000009</td></tr><tr><td>en</td><td>11</td><td>100000010</td></tr><tr><td>en</td><td>12</td><td>100000011</td></tr><tr><td>en</td><td>13</td><td>100000012</td></tr><tr><td>en</td><td>14</td><td>100000013</td></tr><tr><td>en</td><td>15</td><td>100000014</td></tr><tr><td>en</td><td>16</td><td>100000015</td></tr><tr><td>en</td><td>17</td><td>100000016</td></tr><tr><td>en</td><td>18</td><td>100000017</td></tr><tr><td>en</td><td>19</td><td>100000018</td></tr><tr><td>en</td><td>20</td><td>100000019</td></tr><tr><td>en</td><td>21</td><td>100000020</td></tr><tr><td>en</td><td>22</td><td>100000021</td></tr><tr><td>en</td><td>23</td><td>100000022</td></tr><tr><td>en</td><td>24</td><td>100000023</td></tr><tr><td>en</td><td>25</td><td>100000024</td></tr><tr><td>en</td><td>26</td><td>100000025</td></tr><tr><td>en</td><td>27</td><td>100000026</td></tr><tr><td>en</td><td>28</td><td>100000027</td></tr><tr><td>en</td><td>29</td><td>100000028</td></tr><tr><td>en</td><td>30</td><td>100000029</td></tr><tr><td>en</td><td>31</td><td>100000030</td></tr></table></td></tr></table>

### <a href=#deceasedDay_display name="deceasedDay_display">deceasedDay_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deceasedMonth name="deceasedMonth">deceasedMonth</a>

Month the Contact was deceased.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Month</td></tr><tr><td>description</td><td>Month the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedmonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01
02
03
04
05
06
07
08
09
10
11
12</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#deceasedMonth_display name="deceasedMonth_display">deceasedMonth_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deceasedYear name="deceasedYear">deceasedYear</a>

Year the Contact was deceased.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deceased Year</td></tr><tr><td>description</td><td>Year the Contact was deceased.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deceasedyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown
2013
2012
2011
2010
2009
2008
2007
2006
2005
2004</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#deceasedYear_display name="deceasedYear_display">deceasedYear_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deferredToDate name="deferredToDate">deferredToDate</a>

Same as date of first payment when more than one year after the contract date.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deferred To Date</td></tr><tr><td>description</td><td>Same as date of first payment when more than one year after the contract date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deferredtodate</td></tr></table>

### <a href=#designatedOrganizationPercent name="designatedOrganizationPercent">designatedOrganizationPercent</a>

Percent of remainder designated to organization  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Organization %</td></tr><tr><td>description</td><td>Percent of remainder designated to organization</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedorganizationpercent</td></tr></table>

### <a href=#designatedPrincipleAmount name="designatedPrincipleAmount">designatedPrincipleAmount</a>

Amount of principle designated to organization.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Principle Amount</td></tr><tr><td>description</td><td>Amount of principle designated to organization.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedprincipleamount</td></tr></table>

### <a href=#designatedprincipleamountBase name="designatedprincipleamountBase">designatedprincipleamountBase</a>

Value of the Designated Principle Amount in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Principle Amount (Base)</td></tr><tr><td>description</td><td>Value of the Designated Principle Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designatedprincipleamount_base</td></tr></table>

### <a href=#designation name="designation">designation</a>

Usage of gift funds will be unrestricted, restricted or permanently restricted.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designation</td></tr><tr><td>description</td><td>Usage of gift funds will be unrestricted, restricted or permanently restricted.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_designation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unrestricted</td><td>100000000</td></tr><tr><td>en</td><td>Restricted</td><td>100000001</td></tr><tr><td>en</td><td>Permanently Restriceted</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#designation_display name="designation_display">designation_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#discountRate name="discountRate">discountRate</a>

Interest rate a central bank charges depository institutions that borrow reserves from it.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate</td></tr><tr><td>description</td><td>Interest rate a central bank charges depository institutions that borrow reserves from it.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountrate</td></tr></table>

### <a href=#discountRateMonth name="discountRateMonth">discountRateMonth</a>

Month in which latest Discount Rate was populated.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate Month</td></tr><tr><td>description</td><td>Month in which latest Discount Rate was populated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountratemonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>01
02
03
04
05
06
07
08
09
10
11
12</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#discountRateMonth_display name="discountRateMonth_display">discountRateMonth_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#discountRateYear name="discountRateYear">discountRateYear</a>

Year in which latest Discount Rate was populated.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Rate Year</td></tr><tr><td>description</td><td>Year in which latest Discount Rate was populated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_discountrateyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unknown
2013
2012
2011
2010
2009
2008
2007
2006
2005
2004</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#discountRateYear_display name="discountRateYear_display">discountRateYear_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#endowmentType name="endowmentType">endowmentType</a>

Specific endowment at organization where gift will be applied.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endowment Type</td></tr><tr><td>description</td><td>Specific endowment at organization where gift will be applied.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_endowmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Board-Designated Endowment</td><td>100000000</td></tr><tr><td>en</td><td>Permanent Endowment</td><td>100000001</td></tr><tr><td>en</td><td>Donor directed</td><td>100000002</td></tr><tr><td>en</td><td>Current operations</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#endowmentType_display name="endowmentType_display">endowmentType_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#estimatedGivingAmount name="estimatedGivingAmount">estimatedGivingAmount</a>

Estimated amount organization will receive as provided by executor, trustee, or attorney.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Giving Amount</td></tr><tr><td>description</td><td>Estimated amount organization will receive as provided by executor, trustee, or attorney.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedgivingamount</td></tr></table>

### <a href=#estimatedgivingamountBase name="estimatedgivingamountBase">estimatedgivingamountBase</a>

Value of the Estimated Giving Amount in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Giving Amount (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Giving Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedgivingamount_base</td></tr></table>

### <a href=#estimatedTrustProbateDate name="estimatedTrustProbateDate">estimatedTrustProbateDate</a>

Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Trust/Probate Date</td></tr><tr><td>description</td><td>Estimated Date Trust/Probate received as provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_estimatedtrustprobatedate</td></tr></table>

### <a href=#expectedFinalDistributionDate name="expectedFinalDistributionDate">expectedFinalDistributionDate</a>

Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Final Distribution Date</td></tr><tr><td>description</td><td>Expected Date of Final Distribution, typically information provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedfinaldistributiondate</td></tr></table>

### <a href=#expectedFirstDistributionDate name="expectedFirstDistributionDate">expectedFirstDistributionDate</a>

Expected Date of First Distribution, typically information provided by executor, trustee or attorney.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected First Distribution Date</td></tr><tr><td>description</td><td>Expected Date of First Distribution, typically information provided by executor, trustee or attorney.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedfirstdistributiondate</td></tr></table>

### <a href=#externalID name="externalID">externalID</a>

ID from External or Legacy system.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External ID</td></tr><tr><td>description</td><td>ID from External or Legacy system.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_externalid</td></tr></table>

### <a href=#faceValue name="faceValue">faceValue</a>

Value of funds donated.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Face Value</td></tr><tr><td>description</td><td>Value of funds donated.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_facevalue</td></tr></table>

### <a href=#facevalueBase name="facevalueBase">facevalueBase</a>

Value of the Face Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Face Value (Base)</td></tr><tr><td>description</td><td>Value of the Face Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_facevalue_base</td></tr></table>

### <a href=#fundId name="fundId">fundId</a>

Unique identifier for Account associated with Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Planned Giving.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_fundid</td></tr></table>

### <a href=#givingAmount name="givingAmount">givingAmount</a>

Sum of gifts entered on this record (logic field).  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Amount</td></tr><tr><td>description</td><td>Sum of gifts entered on this record (logic field).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingamount</td></tr></table>

### <a href=#givingReceivedDate name="givingReceivedDate">givingReceivedDate</a>

Date distribution or remainder for Planned Giving is received.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Received Date</td></tr><tr><td>description</td><td>Date distribution or remainder for Planned Giving is received.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingreceiveddate</td></tr></table>

### <a href=#givingSubtype name="givingSubtype">givingSubtype</a>

Specific type of Planned Giving instrument.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Giving Subtype</td></tr><tr><td>description</td><td>Specific type of Planned Giving instrument.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_givingsubtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Standard
Flip
Flip with Makeup
Net Income
Net Income with Makeup
Deferred
Flexible
Grantor
Non Grantor
Regular
Testamentory
Traditional IRA
Roth IRA
403(b)/401k
KEOGH
Other Retirement Plan</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#givingSubtype_display name="givingSubtype_display">givingSubtype_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#insuranceAnnualPremium name="insuranceAnnualPremium">insuranceAnnualPremium</a>

Annual Premium of the Life Insurance.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Annual Premium</td></tr><tr><td>description</td><td>Annual Premium of the Life Insurance.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insuranceannualpremium</td></tr></table>

### <a href=#insuranceannualpremiumBase name="insuranceannualpremiumBase">insuranceannualpremiumBase</a>

Value of the Insurance Annual Premium in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Annual Premium (Base)</td></tr><tr><td>description</td><td>Value of the Insurance Annual Premium in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insuranceannualpremium_base</td></tr></table>

### <a href=#insuranceCompany name="insuranceCompany">insuranceCompany</a>

Insurance Company for related to this Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Company</td></tr><tr><td>description</td><td>Insurance Company for related to this Planned Giving.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancecompany</td></tr></table>

### <a href=#insuranceDeathBenefitAmount name="insuranceDeathBenefitAmount">insuranceDeathBenefitAmount</a>

Death Benefit Amount from Insurance.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Death Benefit Amount</td></tr><tr><td>description</td><td>Death Benefit Amount from Insurance.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancedeathbenefitamount</td></tr></table>

### <a href=#insurancePolicyCode name="insurancePolicyCode">insurancePolicyCode</a>

Insurance policy code related to this Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Policy Code</td></tr><tr><td>description</td><td>Insurance policy code related to this Planned Giving.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepolicycode</td></tr></table>

### <a href=#insurancePolicyName name="insurancePolicyName">insurancePolicyName</a>

Insurance Policy Name for this Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Policy Name</td></tr><tr><td>description</td><td>Insurance Policy Name for this Planned Giving.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepolicyname</td></tr></table>

### <a href=#insurancePremiumDueDate name="insurancePremiumDueDate">insurancePremiumDueDate</a>

Insurance Premium Due Date related to this Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Premium Due Date</td></tr><tr><td>description</td><td>Insurance Premium Due Date related to this Planned Giving record.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepremiumduedate</td></tr></table>

### <a href=#insurancePremiumPaymentAddress name="insurancePremiumPaymentAddress">insurancePremiumPaymentAddress</a>

Address for the Life Insurance Premium Payment.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insurance Premium Payment Address</td></tr><tr><td>description</td><td>Address for the Life Insurance Premium Payment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_insurancepremiumpaymentaddress</td></tr></table>

### <a href=#isRevocable name="isRevocable">isRevocable</a>

Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revocable</td></tr><tr><td>description</td><td>Related trust may be amended, altered or revoked by its settlor at any time, provided the settlor is not mentally incapacitated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isrevocable</td></tr></table>

### <a href=#leadSource name="leadSource">leadSource</a>

Method of communication that prompted Donor to discuss Planned Giving options.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead Source</td></tr><tr><td>description</td><td>Method of communication that prompted Donor to discuss Planned Giving options.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_leadsource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Direct Mail
E-Mail
Other
Phone In
Print Ad
Referral
Special Event
TV Promo
Web Site</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#leadSource_display name="leadSource_display">leadSource_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ordinaryIncome name="ordinaryIncome">ordinaryIncome</a>

Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordinary Income</td></tr><tr><td>description</td><td>Income other than capital gain. Examples of Ordinary income can consist of income from wages, salaries, tips, commissions, bonuses, and other types of compensation from employment.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ordinaryincome</td></tr></table>

### <a href=#ordinaryincomeBase name="ordinaryincomeBase">ordinaryincomeBase</a>

Value of the Ordinary Income in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordinary Income (Base)</td></tr><tr><td>description</td><td>Value of the Ordinary Income in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_ordinaryincome_base</td></tr></table>

### <a href=#paymentFrequency name="paymentFrequency">paymentFrequency</a>

Defined frequency payments are distributed to the organization.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Frequency</td></tr><tr><td>description</td><td>Defined frequency payments are distributed to the organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentfrequency</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Monthly
Quarterly**
Annually
Semi-Annually</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#paymentFrequency_display name="paymentFrequency_display">paymentFrequency_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#payoutRate name="payoutRate">payoutRate</a>

Dollar amount per share a Corporation pays for their dividend.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payout Rate</td></tr><tr><td>description</td><td>Dollar amount per share a Corporation pays for their dividend.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_payoutrate</td></tr></table>

### <a href=#plannedGivingCampaignId name="plannedGivingCampaignId">plannedGivingCampaignId</a>

Campaign  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign</td></tr><tr><td>description</td><td>Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_plannedgiving_campaignid</td></tr></table>

### <a href=#plannedGivingPledgedByContactId name="plannedGivingPledgedByContactId">plannedGivingPledgedByContactId</a>

Pledged By Contact  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged By Contact</td></tr><tr><td>description</td><td>Pledged By Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_plannedgiving_pledgedbycontactid</td></tr></table>

### <a href=#pledgesOnAccountId name="pledgesOnAccountId">pledgesOnAccountId</a>

Unique identifier for Account associated with Planned Giving.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledges On Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Planned Giving.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_pledgesonaccountid</td></tr></table>

### <a href=#presentValue name="presentValue">presentValue</a>

The value on a given date of a payment or series of payments made at other times for an investment.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Present Value</td></tr><tr><td>description</td><td>The value on a given date of a payment or series of payments made at other times for an investment.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_presentvalue</td></tr></table>

### <a href=#presentvalueBase name="presentvalueBase">presentvalueBase</a>

Value of the Present Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Present Value (Base)</td></tr><tr><td>description</td><td>Value of the Present Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_presentvalue_base</td></tr></table>

### <a href=#recordType name="recordType">recordType</a>

Type of Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Type</td></tr><tr><td>description</td><td>Type of Planned Giving record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recordtype</td></tr></table>

### <a href=#remainderAmount name="remainderAmount">remainderAmount</a>

Remainder $ value a Charitable Organization receives.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remainder Amount</td></tr><tr><td>description</td><td>Remainder $ value a Charitable Organization receives.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_remainderamount</td></tr></table>

### <a href=#remainderamountBase name="remainderamountBase">remainderamountBase</a>

Value of the Remainder Amount in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remainder Amount (Base)</td></tr><tr><td>description</td><td>Value of the Remainder Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_remainderamount_base</td></tr></table>

### <a href=#rollupGiving name="rollupGiving">rollupGiving</a>

Populated by trigger, reflects the most recent Date/Time for Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Giving</td></tr><tr><td>description</td><td>Populated by trigger, reflects the most recent Date/Time for Giving record.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_rollupgiving</td></tr></table>

### <a href=#salvageValueofBuildings name="salvageValueofBuildings">salvageValueofBuildings</a>

Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salvage Value of Buildings</td></tr><tr><td>description</td><td>Estimated value of property at the end of its useful life. It is what you expect to get for the property if you sell it after you can no longer use it productively.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_salvagevalueofbuildings</td></tr></table>

### <a href=#salvagevalueofbuildingsBase name="salvagevalueofbuildingsBase">salvagevalueofbuildingsBase</a>

Value of the Salvage Value of Buildings in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salvage Value of Buildings (Base)</td></tr><tr><td>description</td><td>Value of the Salvage Value of Buildings in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_salvagevalueofbuildings_base</td></tr></table>

### <a href=#severDate name="severDate">severDate</a>

The term end date' or the date of the related Contact's death.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sever Date</td></tr><tr><td>description</td><td>The term end date' or the date of the related Contact's death.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_severdate</td></tr></table>

### <a href=#stage name="stage">stage</a>

The current phase the giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage</td></tr><tr><td>description</td><td>The current phase the giving record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_stage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active
Cultivating
Intention
Anonymous
Very Contingent
Language Requested
Matured
Claim administration process
Pending
Estate in Probate
Final Distribution
Finished
Severed
Inactive
Estate in Administration process
1st spouse deceased
Termination processing</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#stage_display name="stage_display">stage_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#taxFreeIncome name="taxFreeIncome">taxFreeIncome</a>

The tax free income from the asset related to this giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Free Income</td></tr><tr><td>description</td><td>The tax free income from the asset related to this giving record.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_taxfreeincome</td></tr></table>

### <a href=#taxfreeincomeBase name="taxfreeincomeBase">taxfreeincomeBase</a>

Value of the Tax Free Income in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Free Income (Base)</td></tr><tr><td>description</td><td>Value of the Tax Free Income in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_taxfreeincome_base</td></tr></table>

### <a href=#termEndDate name="termEndDate">termEndDate</a>

Term end date for the asset related to the Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term End Date</td></tr><tr><td>description</td><td>Term end date for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termenddate</td></tr></table>

### <a href=#termType name="termType">termType</a>

Term type for the asset related to the Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term Type</td></tr><tr><td>description</td><td>Term type for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Lives only
Fixed term only
Longer of term or lives
Shorter of term or lives</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#termType_display name="termType_display">termType_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#termYears name="termYears">termYears</a>

Term years for the asset related to the Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term Years</td></tr><tr><td>description</td><td>Term years for the asset related to the Planned Giving record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_termyears</td></tr></table>

### <a href=#totalEstateValue name="totalEstateValue">totalEstateValue</a>

Total Estate Value as provided by executor, trustee or attorney or in estate documentation.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Estate Value</td></tr><tr><td>description</td><td>Total Estate Value as provided by executor, trustee or attorney or in estate documentation.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalestatevalue</td></tr></table>

### <a href=#totalestatevalueBase name="totalestatevalueBase">totalestatevalueBase</a>

Value of the Total Estate Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Estate Value (Base)</td></tr><tr><td>description</td><td>Value of the Total Estate Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalestatevalue_base</td></tr></table>

### <a href=#trustMarketValue name="trustMarketValue">trustMarketValue</a>

Trust Market Value related to this planned giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Market Value</td></tr><tr><td>description</td><td>Trust Market Value related to this planned giving record.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustmarketvalue</td></tr></table>

### <a href=#trustmarketvalueBase name="trustmarketvalueBase">trustmarketvalueBase</a>

Value of the Trust Market Value in base currency.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Market Value (Base)</td></tr><tr><td>description</td><td>Value of the Trust Market Value in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustmarketvalue_base</td></tr></table>

### <a href=#trustProbateNoticeDate name="trustProbateNoticeDate">trustProbateNoticeDate</a>

Date Trust/Probate Notice received.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust/Probate Notice Date</td></tr><tr><td>description</td><td>Date Trust/Probate Notice received.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustprobatenoticedate</td></tr></table>

### <a href=#trustValueDate name="trustValueDate">trustValueDate</a>

Trust Value Date related to this planned giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Trust Value Date</td></tr><tr><td>description</td><td>Trust Value Date related to this planned giving record.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_trustvaluedate</td></tr></table>

### <a href=#typeOfManagement name="typeOfManagement">typeOfManagement</a>

The type of management for the underlying asset or assets related to this Planned Giving record.  
First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type of Management</td></tr><tr><td>description</td><td>The type of management for the underlying asset or assets related to this Planned Giving record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_typeofmanagement</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inside</td><td>100000000</td></tr><tr><td>en</td><td>Outside - donor self-trustee</td><td>100000001</td></tr><tr><td>en</td><td>Outside - Institution or other trusteem
Outside</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#typeOfManagement_display name="typeOfManagement_display">typeOfManagement_display</a>

First included in: nonProfit/PlannedGiving (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
