---
title: ProductFootprint in Cloud for Sustainability carbon data model - Common Data Model | Microsoft Docs
description: The carbon footprint of a product with values in accordance with the Pathfinder Framework.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/1/2024
ms.author: cdmditeam
---

# Product footprint in Cloud for Sustainability carbon data model(ProductFootprint)

The carbon footprint of a product with values in accordance with the Pathfinder Framework.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProductFootprint/(resolvedAttributes)/sustainabilityproductfootprintId](#sustainabilityproductfootprintId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProductFootprint/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/Sustainability<br>/CloudforSustainabilityCarbonDataModel<br>/ProductFootprint.cdm.json/ProductFootprint<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The carbon footprint of a product with values in accordance with the Pathfinder Framework.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product footprint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_sustainabilityproductfootprint"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[sustainabilityproductfootprintId](#sustainabilityproductfootprintId)|Unique identifier for entity instances.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[statecode](#statecode)|Status of the Sustainability product footprint|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[statuscode](#statuscode)|Reason for the status of the Sustainability product footprint|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[name](#name)|The name of the custom entity.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[comment](#comment)|Information which helps interpret, audit, or verify the product footprint, or which describes its calculation.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[company](#company)|The company that is the data owner.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[companyType](#companyType)|The company that is the data owner.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[specversion](#specversion)|The version of the Pathfinder Framework data specification being used.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[footprintstatus](#footprintstatus)|The default status of a product footprint is Active. A product footprint with status Inactive shouldn't be used, for example, product footprint calculations by data recipients.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[statuscomment](#statuscomment)|If defined, the value should be a message explaining the reason for the current status.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[sustainabilityproduct](#sustainabilityproduct)|The product this footprint is for. (Deprecated)|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[sustainabilityproductcarbonfootprint](#sustainabilityproductcarbonfootprint)|The carbon footprint of the given product. (Deprecated)|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[validityperiodend](#validityperiodend)|The end (exclusive) of the valid period of the PCF. Reference the description of validity period start and the Pathfinder Framework for further details.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[validityperiodstart](#validityperiodstart)|The start of the validity period, which is the interval during which the PCF is declared as valid for use by a data recipient. Reference the Pathfinder Framework for further details. |<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[version](#version)|The version of the product footprint with value an integer in the inclusive range of 0 to (2\^31)-1.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[origincorrelationid](#origincorrelationid)|An optional identifier to correlate record with data origin.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[countryregioncode](#countryregioncode)|Lookup field for Country/region.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[geographycountry](#geographycountry)|If present, the value must conform to an ISO 3166-2 alpha-2 code.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[geographycountrysubdivision](#geographycountrysubdivision)|If present, an ISO 3166-2 subdivision code.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[geographyregionorsubregion](#geographyregionorsubregion)|If present, the value must conform to data type RegionOrSubregion, as specified by the Pathfinder Framework.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[aircraftghgemissions](#aircraftghgemissions)|The GHG emissions resulting from aircraft engine usage for the transport of the product. Must be calculated with unit kgCO2e per declared unit and non-negative.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[allocationrulesdescription](#allocationrulesdescription)|If present, a description of any allocation rules applied and the rationale explaining how the selected approach aligns with Pathfinder Framework rules.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[biogenicaccountingmethodology](#biogenicaccountingmethodology)|The standard followed to account for biogenic emissions and removals.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[biogeniccarboncontent](#biogeniccarboncontent)|The biogenic carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[biogeniccarbonwithdrawal](#biogeniccarbonwithdrawal)|If present, the biogenic carbon content in the product converted to CO2e. The value must be calculated per declared unit with unit kg expressed as a decimal equal to or greater than zero.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[boundaryprocessesdescription](#boundaryprocessesdescription)|If present, the processes attributable to each lifecycle stage. If no such description is available or otherwise provided, then this field must be empty.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[characterizationfactors](#characterizationfactors)|The IPCC Assessment Report used in the calculation of the PCF.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[completenessdqr](#completenessdqr)|DQR based on data quality matrix, scoring completeness of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[coveragepercent](#coveragepercent)|Percentage of PCF included in the data quality assessment based on the >5% emissions threshold.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[crosssectoralstandardsused1](#crosssectoralstandardsused1)|The cross-sectoral standards applied for calculating or allocating GHG emissions.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[crosssectoralstandardsused2](#crosssectoralstandardsused2)|The cross-sectoral standards applied for calculating or allocating GHG emissions.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[crosssectoralstandardsused3](#crosssectoralstandardsused3)|The cross-sectoral standards applied for calculating or allocating GHG emissions.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[declaredunit](#declaredunit)|The unit of analysis of the product.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[dlucghgemissions](#dlucghgemissions)|Emissions from recent carbon stock loss from land conversion on land in consideration. Must include dLUC if available, else sLUC can be used. Unit kgCO2e per declared unit and must be >= 0. |<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[exemptedemissionsdescription](#exemptedemissionsdescription)|Rationale behind exclusion of specific PCF emissions, can have no data if no emissions were excluded.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[exemptedemissionspercent](#exemptedemissionspercent)|The percentage of emissions excluded from PCF, expressed as a decimal number from 0.0 to 5, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[fossilcarboncontent](#fossilcarboncontent)|The fossil carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. |<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[fossilghgemissions](#fossilghgemissions)|The emissions from the combustion of fossil sources. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[geographicaldqr](#geographicaldqr)|DQR based on data quality matrix, scoring geographical representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[ilucghgemissions](#ilucghgemissions)|Emissions from recent carbon stock loss from land conversion on land outside control of company or its supply chain, induced by demand change. Unit kgCO2e per declared unit and must be >= 0. |<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[landmanagementghgemissions](#landmanagementghgemissions)|GHG emissions and removals associated with land management-related changes, including non-CO2 sources. Must be calculated with unit kgCO2e per declared unit and non-negative.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[otherbiogenicghgemissions](#otherbiogenicghgemissions)|All other biogenic GHG emissions associated with product manufacturing and transport that are not included in dLUC, iLUC, and land management. Unit kgCO2e per declared unit and must be >= 0.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[packagingemissionsincluded](#packagingemissionsincluded)|A boolean flag indicating whether packaging emissions are included in the PCF.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[packagingghgemissions](#packagingghgemissions)|Emissions from the packaging of the product. Must be calculated with unit kgCO2e per declared unit and non-negative. The field must be empty if packaging emissions included is false.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[pcfexcludingbiogenic](#pcfexcludingbiogenic)|The PCF of the product excluding biogenic emissions. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. |<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[pcfincludingbiogenic](#pcfincludingbiogenic)|The PCF of the product including biogenic emissions. The value must be calculated with unit kgCO2e per declared unit. This column can be less than 0.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[primarydatashare](#primarydatashare)|The share of primary data in percent. For recommended business logic, see the Pathfinder Framework.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[productfootprintassurance](#productfootprintassurance)|Assurance information in accordance with the Pathfinder Framework.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[referenceperiodend](#referenceperiodend)|The end of the time boundary for which the PCF value is considered to be representative.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[referenceperiodstart](#referenceperiodstart)|The start of the time boundary for which the PCF value is considered to be representative.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[reliabilitydqr](#reliabilitydqr)|DQR based on data quality matrix, scoring reliability of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[secondaryemissionfactorsources](#secondaryemissionfactorsources)|If secondary data was used to calculate the PCF, then it must include this field with value the emission factors used for the PCF calculation. Otherwise, this property must be undefined.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[technologicaldqr](#technologicaldqr)|DQR based on data quality matrix, scoring technological representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[temporaldqr](#temporaldqr)|DQR based on data quality matrix, scoring temporal representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[uncertaintyassessmentdescription](#uncertaintyassessmentdescription)|If present, the results, key drivers, and a short qualitative description of the uncertainty assessment.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[unitaryproductamount](#unitaryproductamount)|The amount of declared units contained within the product to which the PCF is referring. The value must be strictly greater than 0.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|
|[sustainabilityproductitem](#sustainabilityproductitem)|The product or item this footprint is for.|<a href="ProductFootprint.md" target="_blank">Sustainability\CloudforSustainabilityCarbonDataModel/ProductFootprint</a>|

### <a href=#sustainabilityproductfootprintId name="sustainabilityproductfootprintId">sustainabilityproductfootprintId</a>

Unique identifier for entity instances.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sustainability product footprint</td></tr><tr><td>description</td><td>Unique identifier for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msdyn_sustainabilityproductfootprintid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sustainabilityproductfootprintId attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.identifiedBy*  
  names a specific identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProductFootprint/(resolvedAttributes)/sustainabilityproductfootprintId](#sustainabilityproductfootprintId)</td><td>attribute</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sustainability product footprint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_sustainabilityproductfootprintid"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.dataFormat.time*  
  *means.measurement.time*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.time*  
  *is.dataFormat.date*  
  </details>

### <a href=#statecode name="statecode">statecode</a>

Status of the Sustainability product footprint  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Sustainability product footprint</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statecode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*means.entityState*  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProductFootprint/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Sustainability product footprint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"25"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#statuscode name="statuscode">statuscode</a>

Reason for the status of the Sustainability product footprint  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Sustainability product footprint</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statuscode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.correlatedWith*  
  the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"statecode"</td><td>attributeName</td><td></td></tr></table>

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Sustainability product footprint</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"27"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the custom entity.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_name"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#comment name="comment">comment</a>

Information which helps interpret, audit, or verify the product footprint, or which describes its calculation.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Additional information</td></tr><tr><td>description</td><td>Information which helps interpret, audit, or verify the product footprint, or which describes its calculation.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_comment</td></tr></table>

#### Traits

<details>
<summary>List of traits for the comment attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information which helps interpret, audit, or verify the product footprint, or which describes its calculation.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Additional information</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_comment"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"35"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#company name="company">company</a>

The company that is the data owner.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company</td></tr><tr><td>description</td><td>The company that is the data owner.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the company attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/Account.md" target="_blank">/SustainabilityShared/Account.cdm.json/Account</a></td><td><a href="../SustainabilityShared/Account.md#accountId" target="_blank">accountId</a></td></tr><tr><td><a href="../SustainabilityShared/OrganizationalUnit.md" target="_blank">/SustainabilityShared/OrganizationalUnit.cdm.json/OrganizationalUnit</a></td><td><a href="../SustainabilityShared/OrganizationalUnit.md#sustainabilityorganizationalunitId" target="_blank">sustainabilityorganizationalunitId</a></td></tr><tr><td><a href="../SustainabilityShared/ValueChainPartner.md" target="_blank">/SustainabilityShared/ValueChainPartner.cdm.json/ValueChainPartner</a></td><td><a href="../SustainabilityShared/ValueChainPartner.md#valuechainpartnerId" target="_blank">valuechainpartnerId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The company that is the data owner.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#companyType name="companyType">companyType</a>

The company that is the data owner.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company</td></tr><tr><td>description</td><td>The company that is the data owner.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companyType attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*means.entityName*  
  a string value is the name of a CDM entity.  

*is.linkedEntity.name*  
  Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The company that is the data owner.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#specversion name="specversion">specversion</a>

The version of the Pathfinder Framework data specification being used.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Spec version</td></tr><tr><td>description</td><td>The version of the Pathfinder Framework data specification being used.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_specversion</td></tr></table>

#### Traits

<details>
<summary>List of traits for the specversion attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The version of the Pathfinder Framework data specification being used.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Spec version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"250"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_specversion"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"37"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#footprintstatus name="footprintstatus">footprintstatus</a>

The default status of a product footprint is Active. A product footprint with status Inactive shouldn't be used, for example, product footprint calculations by data recipients.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product footprint status</td></tr><tr><td>description</td><td>The default status of a product footprint is Active. A product footprint with status Inactive shouldn't be used, for example, product footprint calculations by data recipients.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_footprintstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>700610000</td></tr><tr><td>en</td><td>Inactive</td><td>700610001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the footprintstatus attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>700610000</td></tr><tr><td>en</td><td>Inactive</td><td>700610001</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The default status of a product footprint is Active. A product footprint with status Inactive shouldn't be used, for example, product footprint calculations by data recipients.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product footprint status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_footprintstatus"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#statuscomment name="statuscomment">statuscomment</a>

If defined, the value should be a message explaining the reason for the current status.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status explanation</td></tr><tr><td>description</td><td>If defined, the value should be a message explaining the reason for the current status.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_statuscomment</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statuscomment attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If defined, the value should be a message explaining the reason for the current status.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status explanation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_statuscomment"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"40"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#sustainabilityproduct name="sustainabilityproduct">sustainabilityproduct</a>

The product this footprint is for. (Deprecated)  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product (sustainability) (Deprecated)</td></tr><tr><td>description</td><td>The product this footprint is for. (Deprecated)</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sustainabilityproduct attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The product this footprint is for. (Deprecated)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product (sustainability) (Deprecated)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/ProductSustainability.md" target="_blank">/SustainabilityShared/ProductSustainability.cdm.json/ProductSustainability</a></td><td><a href="../SustainabilityShared/ProductSustainability.md#sustainabilityproductId" target="_blank">sustainabilityproductId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#sustainabilityproductcarbonfootprint name="sustainabilityproductcarbonfootprint">sustainabilityproductcarbonfootprint</a>

The carbon footprint of the given product. (Deprecated)  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product carbon footprint (Deprecated)</td></tr><tr><td>description</td><td>The carbon footprint of the given product. (Deprecated)</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sustainabilityproductcarbonfootprint attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The carbon footprint of the given product. (Deprecated)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product carbon footprint (Deprecated)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="DeprecatedProductCarbonFootprint.md" target="_blank">DeprecatedProductCarbonFootprint.cdm.json/DeprecatedProductCarbonFootprint</a></td><td><a href="DeprecatedProductCarbonFootprint.md#sustainabilityproductcarbonfootprintId" target="_blank">sustainabilityproductcarbonfootprintId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#validityperiodend name="validityperiodend">validityperiodend</a>

The end (exclusive) of the valid period of the PCF. Reference the description of validity period start and the Pathfinder Framework for further details.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validity period end</td></tr><tr><td>description</td><td>The end (exclusive) of the valid period of the PCF. Reference the description of validity period start and the Pathfinder Framework for further details.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_validityperiodend</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validityperiodend attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The end (exclusive) of the valid period of the PCF. Reference the description of validity period start and the Pathfinder Framework for further details.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validity period end</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_validityperiodend"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"43"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#validityperiodstart name="validityperiodstart">validityperiodstart</a>

The start of the validity period, which is the interval during which the PCF is declared as valid for use by a data recipient. Reference the Pathfinder Framework for further details.   
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validity period start</td></tr><tr><td>description</td><td>The start of the validity period, which is the interval during which the PCF is declared as valid for use by a data recipient. Reference the Pathfinder Framework for further details. </td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_validityperiodstart</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validityperiodstart attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The start of the validity period, which is the interval during which the PCF is declared as valid for use by a data recipient. Reference the Pathfinder Framework for further details. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validity period start</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_validityperiodstart"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"44"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#version name="version">version</a>

The version of the product footprint with value an integer in the inclusive range of 0 to (2\^31)-1.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version</td></tr><tr><td>description</td><td>The version of the product footprint with value an integer in the inclusive range of 0 to (2^31)-1.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_version</td></tr></table>

#### Traits

<details>
<summary>List of traits for the version attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The version of the product footprint with value an integer in the inclusive range of 0 to (2^31)-1.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_version"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"45"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#origincorrelationid name="origincorrelationid">origincorrelationid</a>

An optional identifier to correlate record with data origin.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin correlation ID</td></tr><tr><td>description</td><td>An optional identifier to correlate record with data origin.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_origincorrelationid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the origincorrelationid attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>An optional identifier to correlate record with data origin.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Origin correlation ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_origincorrelationid"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"46"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#countryregioncode name="countryregioncode">countryregioncode</a>

Lookup field for Country/region.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/region</td></tr><tr><td>description</td><td>Lookup field for Country/region.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countryregioncode attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lookup field for Country/region.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/CountryRegion.md" target="_blank">/SustainabilityShared/CountryRegion.cdm.json/CountryRegion</a></td><td><a href="../SustainabilityShared/CountryRegion.md#countryregionId" target="_blank">countryregionId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#geographycountry name="geographycountry">geographycountry</a>

If present, the value must conform to an ISO 3166-2 alpha-2 code.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/region (Deprecated)</td></tr><tr><td>description</td><td>If present, the value must conform to an ISO 3166-2 alpha-2 code.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geographycountry</td></tr></table>

#### Traits

<details>
<summary>List of traits for the geographycountry attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, the value must conform to an ISO 3166-2 alpha-2 code.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/region (Deprecated)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_geographycountry"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"48"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#geographycountrysubdivision name="geographycountrysubdivision">geographycountrysubdivision</a>

If present, an ISO 3166-2 subdivision code.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/region subdivision</td></tr><tr><td>description</td><td>If present, an ISO 3166-2 subdivision code.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geographycountrysubdivision</td></tr></table>

#### Traits

<details>
<summary>List of traits for the geographycountrysubdivision attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, an ISO 3166-2 subdivision code.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/region subdivision</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_geographycountrysubdivision"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"49"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#geographyregionorsubregion name="geographyregionorsubregion">geographyregionorsubregion</a>

If present, the value must conform to data type RegionOrSubregion, as specified by the Pathfinder Framework.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Region or subregion</td></tr><tr><td>description</td><td>If present, the value must conform to data type RegionOrSubregion, as specified by the Pathfinder Framework.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geographyregionorsubregion</td></tr></table>

#### Traits

<details>
<summary>List of traits for the geographyregionorsubregion attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, the value must conform to data type RegionOrSubregion, as specified by the Pathfinder Framework.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Region or subregion</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_geographyregionorsubregion"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"50"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#aircraftghgemissions name="aircraftghgemissions">aircraftghgemissions</a>

The GHG emissions resulting from aircraft engine usage for the transport of the product. Must be calculated with unit kgCO2e per declared unit and non-negative.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aircraft GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>The GHG emissions resulting from aircraft engine usage for the transport of the product. Must be calculated with unit kgCO2e per declared unit and non-negative.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_aircraftghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aircraftghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The GHG emissions resulting from aircraft engine usage for the transport of the product. Must be calculated with unit kgCO2e per declared unit and non-negative.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aircraft GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_aircraftghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"51"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#allocationrulesdescription name="allocationrulesdescription">allocationrulesdescription</a>

If present, a description of any allocation rules applied and the rationale explaining how the selected approach aligns with Pathfinder Framework rules.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allocation rules description</td></tr><tr><td>description</td><td>If present, a description of any allocation rules applied and the rationale explaining how the selected approach aligns with Pathfinder Framework rules.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_allocationrulesdescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allocationrulesdescription attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, a description of any allocation rules applied and the rationale explaining how the selected approach aligns with Pathfinder Framework rules.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allocation rules description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_allocationrulesdescription"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"52"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#biogenicaccountingmethodology name="biogenicaccountingmethodology">biogenicaccountingmethodology</a>

The standard followed to account for biogenic emissions and removals.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Biogenic accounting methodology</td></tr><tr><td>description</td><td>The standard followed to account for biogenic emissions and removals.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_biogenicaccountingmethodology</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PEF</td><td>700610000</td></tr><tr><td>en</td><td>ISO</td><td>700610001</td></tr><tr><td>en</td><td>GHGP</td><td>700610002</td></tr><tr><td>en</td><td>Quantis</td><td>700610003</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the biogenicaccountingmethodology attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PEF</td><td>700610000</td></tr><tr><td>en</td><td>ISO</td><td>700610001</td></tr><tr><td>en</td><td>GHGP</td><td>700610002</td></tr><tr><td>en</td><td>Quantis</td><td>700610003</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The standard followed to account for biogenic emissions and removals.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Biogenic accounting methodology</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_biogenicaccountingmethodology"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"53"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#biogeniccarboncontent name="biogeniccarboncontent">biogeniccarboncontent</a>

The biogenic carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Biogenic carbon content (kgCO2e)</td></tr><tr><td>description</td><td>The biogenic carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_biogeniccarboncontent</td></tr></table>

#### Traits

<details>
<summary>List of traits for the biogeniccarboncontent attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The biogenic carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Biogenic carbon content (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_biogeniccarboncontent"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"55"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#biogeniccarbonwithdrawal name="biogeniccarbonwithdrawal">biogeniccarbonwithdrawal</a>

If present, the biogenic carbon content in the product converted to CO2e. The value must be calculated per declared unit with unit kg expressed as a decimal equal to or greater than zero.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Biogenic carbon withdrawal (kgCO2e)</td></tr><tr><td>description</td><td>If present, the biogenic carbon content in the product converted to CO2e. The value must be calculated per declared unit with unit kg expressed as a decimal equal to or greater than zero.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_biogeniccarbonwithdrawal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the biogeniccarbonwithdrawal attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, the biogenic carbon content in the product converted to CO2e. The value must be calculated per declared unit with unit kg expressed as a decimal equal to or greater than zero.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Biogenic carbon withdrawal (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_biogeniccarbonwithdrawal"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"56"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#boundaryprocessesdescription name="boundaryprocessesdescription">boundaryprocessesdescription</a>

If present, the processes attributable to each lifecycle stage. If no such description is available or otherwise provided, then this field must be empty.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Boundary processes description</td></tr><tr><td>description</td><td>If present, the processes attributable to each lifecycle stage. If no such description is available or otherwise provided, then this field must be empty.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_boundaryprocessesdescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the boundaryprocessesdescription attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, the processes attributable to each lifecycle stage. If no such description is available or otherwise provided, then this field must be empty.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Boundary processes description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_boundaryprocessesdescription"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"57"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#characterizationfactors name="characterizationfactors">characterizationfactors</a>

The IPCC Assessment Report used in the calculation of the PCF.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Characterization factors</td></tr><tr><td>description</td><td>The IPCC Assessment Report used in the calculation of the PCF.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_characterizationfactors</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Custom</td><td>700610000</td></tr><tr><td>en</td><td>AR4</td><td>700610004</td></tr><tr><td>en</td><td>AR5</td><td>700610005</td></tr><tr><td>en</td><td>AR6</td><td>700610006</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the characterizationfactors attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Custom</td><td>700610000</td></tr><tr><td>en</td><td>AR4</td><td>700610004</td></tr><tr><td>en</td><td>AR5</td><td>700610005</td></tr><tr><td>en</td><td>AR6</td><td>700610006</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The IPCC Assessment Report used in the calculation of the PCF.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Characterization factors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_characterizationfactors"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"58"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#completenessdqr name="completenessdqr">completenessdqr</a>

DQR based on data quality matrix, scoring completeness of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Completeness DQR</td></tr><tr><td>description</td><td>DQR based on data quality matrix, scoring completeness of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_completenessdqr</td></tr></table>

#### Traits

<details>
<summary>List of traits for the completenessdqr attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DQR based on data quality matrix, scoring completeness of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Completeness DQR</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"3"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_completenessdqr"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"60"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#coveragepercent name="coveragepercent">coveragepercent</a>

Percentage of PCF included in the data quality assessment based on the >5% emissions threshold.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Coverage percent</td></tr><tr><td>description</td><td>Percentage of PCF included in the data quality assessment based on the >5% emissions threshold.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_coveragepercent</td></tr></table>

#### Traits

<details>
<summary>List of traits for the coveragepercent attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percentage of PCF included in the data quality assessment based on the >5% emissions threshold.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Coverage percent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_coveragepercent"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"61"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#crosssectoralstandardsused1 name="crosssectoralstandardsused1">crosssectoralstandardsused1</a>

The cross-sectoral standards applied for calculating or allocating GHG emissions.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cross-sectoral standards used 1</td></tr><tr><td>description</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_crosssectoralstandardsused1</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the crosssectoralstandardsused1 attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cross-sectoral standards used 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_crosssectoralstandardsused1"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"64"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#crosssectoralstandardsused2 name="crosssectoralstandardsused2">crosssectoralstandardsused2</a>

The cross-sectoral standards applied for calculating or allocating GHG emissions.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cross-sectoral standards used 2</td></tr><tr><td>description</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_crosssectoralstandardsused2</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the crosssectoralstandardsused2 attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cross-sectoral standards used 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_crosssectoralstandardsused2"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"66"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#crosssectoralstandardsused3 name="crosssectoralstandardsused3">crosssectoralstandardsused3</a>

The cross-sectoral standards applied for calculating or allocating GHG emissions.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cross-sectoral standards used 3</td></tr><tr><td>description</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_crosssectoralstandardsused3</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the crosssectoralstandardsused3 attribute are listed below.</summary>

*is.dataFormat.integer*  
  *is.dataFormat.signed*  
  indicates the capability to represent values less than zero.  

*is.dataFormat.numeric*  
  *does.haveDefault*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>GHG Protocol Product standard</td><td>700610000</td></tr><tr><td>en</td><td>ISO Standard 14067</td><td>700610001</td></tr><tr><td>en</td><td>ISO Standard 14044</td><td>700610002</td></tr></table></td><td>any</td><td></td></tr></table>

*is.constrainedList*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The cross-sectoral standards applied for calculating or allocating GHG emissions.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cross-sectoral standards used 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_crosssectoralstandardsused3"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"68"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.integer*  
  </details>

### <a href=#declaredunit name="declaredunit">declaredunit</a>

The unit of analysis of the product.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>The unit of analysis of the product.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the declaredunit attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The unit of analysis of the product.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/Unit.md" target="_blank">/SustainabilityShared/Unit.cdm.json/Unit</a></td><td><a href="../SustainabilityShared/Unit.md#unitId" target="_blank">unitId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#dlucghgemissions name="dlucghgemissions">dlucghgemissions</a>

Emissions from recent carbon stock loss from land conversion on land in consideration. Must include dLUC if available, else sLUC can be used. Unit kgCO2e per declared unit and must be >= 0.   
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>dLUC GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>Emissions from recent carbon stock loss from land conversion on land in consideration. Must include dLUC if available, else sLUC can be used. Unit kgCO2e per declared unit and must be >= 0. </td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_dlucghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dlucghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Emissions from recent carbon stock loss from land conversion on land in consideration. Must include dLUC if available, else sLUC can be used. Unit kgCO2e per declared unit and must be >= 0. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>dLUC GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_dlucghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"71"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#exemptedemissionsdescription name="exemptedemissionsdescription">exemptedemissionsdescription</a>

Rationale behind exclusion of specific PCF emissions, can have no data if no emissions were excluded.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exempted emissions description</td></tr><tr><td>description</td><td>Rationale behind exclusion of specific PCF emissions, can have no data if no emissions were excluded.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exemptedemissionsdescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the exemptedemissionsdescription attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rationale behind exclusion of specific PCF emissions, can have no data if no emissions were excluded.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exempted emissions description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_exemptedemissionsdescription"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"72"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#exemptedemissionspercent name="exemptedemissionspercent">exemptedemissionspercent</a>

The percentage of emissions excluded from PCF, expressed as a decimal number from 0.0 to 5, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exempted emissions percent</td></tr><tr><td>description</td><td>The percentage of emissions excluded from PCF, expressed as a decimal number from 0.0 to 5, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>5</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exemptedemissionspercent</td></tr></table>

#### Traits

<details>
<summary>List of traits for the exemptedemissionspercent attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The percentage of emissions excluded from PCF, expressed as a decimal number from 0.0 to 5, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exempted emissions percent</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"5"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_exemptedemissionspercent"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"73"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#fossilcarboncontent name="fossilcarboncontent">fossilcarboncontent</a>

The fossil carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.   
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fossil carbon content (kgCO2e)</td></tr><tr><td>description</td><td>The fossil carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. </td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fossilcarboncontent</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fossilcarboncontent attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The fossil carbon amount embodied in the product. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fossil carbon content (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_fossilcarboncontent"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"74"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#fossilghgemissions name="fossilghgemissions">fossilghgemissions</a>

The emissions from the combustion of fossil sources. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fossil GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>The emissions from the combustion of fossil sources. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fossilghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fossilghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The emissions from the combustion of fossil sources. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fossil GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_fossilghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"75"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#geographicaldqr name="geographicaldqr">geographicaldqr</a>

DQR based on data quality matrix, scoring geographical representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Geographical DQR</td></tr><tr><td>description</td><td>DQR based on data quality matrix, scoring geographical representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geographicaldqr</td></tr></table>

#### Traits

<details>
<summary>List of traits for the geographicaldqr attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DQR based on data quality matrix, scoring geographical representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Geographical DQR</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"3"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_geographicaldqr"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"76"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#ilucghgemissions name="ilucghgemissions">ilucghgemissions</a>

Emissions from recent carbon stock loss from land conversion on land outside control of company or its supply chain, induced by demand change. Unit kgCO2e per declared unit and must be >= 0.   
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>iLUC GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>Emissions from recent carbon stock loss from land conversion on land outside control of company or its supply chain, induced by demand change. Unit kgCO2e per declared unit and must be >= 0. </td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ilucghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ilucghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Emissions from recent carbon stock loss from land conversion on land outside control of company or its supply chain, induced by demand change. Unit kgCO2e per declared unit and must be >= 0. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>iLUC GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_ilucghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"77"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#landmanagementghgemissions name="landmanagementghgemissions">landmanagementghgemissions</a>

GHG emissions and removals associated with land management-related changes, including non-CO2 sources. Must be calculated with unit kgCO2e per declared unit and non-negative.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land management GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>GHG emissions and removals associated with land management-related changes, including non-CO2 sources. Must be calculated with unit kgCO2e per declared unit and non-negative.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_landmanagementghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the landmanagementghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GHG emissions and removals associated with land management-related changes, including non-CO2 sources. Must be calculated with unit kgCO2e per declared unit and non-negative.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land management GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_landmanagementghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"78"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#otherbiogenicghgemissions name="otherbiogenicghgemissions">otherbiogenicghgemissions</a>

All other biogenic GHG emissions associated with product manufacturing and transport that are not included in dLUC, iLUC, and land management. Unit kgCO2e per declared unit and must be >= 0.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other biogenic GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>All other biogenic GHG emissions associated with product manufacturing and transport that are not included in dLUC, iLUC, and land management. Unit kgCO2e per declared unit and must be >= 0.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_otherbiogenicghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the otherbiogenicghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>All other biogenic GHG emissions associated with product manufacturing and transport that are not included in dLUC, iLUC, and land management. Unit kgCO2e per declared unit and must be >= 0.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other biogenic GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_otherbiogenicghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"79"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#packagingemissionsincluded name="packagingemissionsincluded">packagingemissionsincluded</a>

A boolean flag indicating whether packaging emissions are included in the PCF.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packaging emissions included</td></tr><tr><td>description</td><td>A boolean flag indicating whether packaging emissions are included in the PCF.</td></tr><tr><td>dataFormat</td><td>boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_packagingemissionsincluded</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packagingemissionsincluded attribute are listed below.</summary>

*is.dataFormat.boolean*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A boolean flag indicating whether packaging emissions are included in the PCF.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packaging emissions included</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_packagingemissionsincluded"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"80"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.boolean*  
  </details>

### <a href=#packagingghgemissions name="packagingghgemissions">packagingghgemissions</a>

Emissions from the packaging of the product. Must be calculated with unit kgCO2e per declared unit and non-negative. The field must be empty if packaging emissions included is false.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packaging GHG emissions (kgCO2e)</td></tr><tr><td>description</td><td>Emissions from the packaging of the product. Must be calculated with unit kgCO2e per declared unit and non-negative. The field must be empty if packaging emissions included is false.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_packagingghgemissions</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packagingghgemissions attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Emissions from the packaging of the product. Must be calculated with unit kgCO2e per declared unit and non-negative. The field must be empty if packaging emissions included is false.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packaging GHG emissions (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_packagingghgemissions"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"82"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#pcfexcludingbiogenic name="pcfexcludingbiogenic">pcfexcludingbiogenic</a>

The PCF of the product excluding biogenic emissions. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero.   
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PCF excluding biogenic (kgCO2e)</td></tr><tr><td>description</td><td>The PCF of the product excluding biogenic emissions. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. </td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pcfexcludingbiogenic</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pcfexcludingbiogenic attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The PCF of the product excluding biogenic emissions. The value must be calculated with unit kgCO2e per declared unit, expressed as a decimal equal to or greater than zero. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>PCF excluding biogenic (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_pcfexcludingbiogenic"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"83"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#pcfincludingbiogenic name="pcfincludingbiogenic">pcfincludingbiogenic</a>

The PCF of the product including biogenic emissions. The value must be calculated with unit kgCO2e per declared unit. This column can be less than 0.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PCF including biogenic (kgCO2e)</td></tr><tr><td>description</td><td>The PCF of the product including biogenic emissions. The value must be calculated with unit kgCO2e per declared unit. This column can be less than 0.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pcfincludingbiogenic</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pcfincludingbiogenic attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The PCF of the product including biogenic emissions. The value must be calculated with unit kgCO2e per declared unit. This column can be less than 0.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>PCF including biogenic (kgCO2e)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_pcfincludingbiogenic"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"84"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#primarydatashare name="primarydatashare">primarydatashare</a>

The share of primary data in percent. For recommended business logic, see the Pathfinder Framework.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary data share</td></tr><tr><td>description</td><td>The share of primary data in percent. For recommended business logic, see the Pathfinder Framework.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_primarydatashare</td></tr></table>

#### Traits

<details>
<summary>List of traits for the primarydatashare attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The share of primary data in percent. For recommended business logic, see the Pathfinder Framework.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary data share</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_primarydatashare"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"85"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#productfootprintassurance name="productfootprintassurance">productfootprintassurance</a>

Assurance information in accordance with the Pathfinder Framework.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product footprint audit</td></tr><tr><td>description</td><td>Assurance information in accordance with the Pathfinder Framework.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the productfootprintassurance attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Assurance information in accordance with the Pathfinder Framework.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product footprint audit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="ProductFootprintAudit.md" target="_blank">ProductFootprintAudit.cdm.json/ProductFootprintAudit</a></td><td><a href="ProductFootprintAudit.md#productcarbonfootprintassuranceId" target="_blank">productcarbonfootprintassuranceId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#referenceperiodend name="referenceperiodend">referenceperiodend</a>

The end of the time boundary for which the PCF value is considered to be representative.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference period end</td></tr><tr><td>description</td><td>The end of the time boundary for which the PCF value is considered to be representative.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_referenceperiodend</td></tr></table>

#### Traits

<details>
<summary>List of traits for the referenceperiodend attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The end of the time boundary for which the PCF value is considered to be representative.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference period end</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_referenceperiodend"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"87"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#referenceperiodstart name="referenceperiodstart">referenceperiodstart</a>

The start of the time boundary for which the PCF value is considered to be representative.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference period start</td></tr><tr><td>description</td><td>The start of the time boundary for which the PCF value is considered to be representative.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_referenceperiodstart</td></tr></table>

#### Traits

<details>
<summary>List of traits for the referenceperiodstart attribute are listed below.</summary>

*is.dataFormat.date*  
  *means.measurement.date*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The start of the time boundary for which the PCF value is considered to be representative.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference period start</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_referenceperiodstart"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"88"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.date*  
  </details>

### <a href=#reliabilitydqr name="reliabilitydqr">reliabilitydqr</a>

DQR based on data quality matrix, scoring reliability of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reliability DQR</td></tr><tr><td>description</td><td>DQR based on data quality matrix, scoring reliability of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_reliabilitydqr</td></tr></table>

#### Traits

<details>
<summary>List of traits for the reliabilitydqr attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DQR based on data quality matrix, scoring reliability of data collected for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reliability DQR</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"3"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_reliabilitydqr"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"89"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#secondaryemissionfactorsources name="secondaryemissionfactorsources">secondaryemissionfactorsources</a>

If secondary data was used to calculate the PCF, then it must include this field with value the emission factors used for the PCF calculation. Otherwise, this property must be undefined.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Secondary emission factor sources</td></tr><tr><td>description</td><td>If secondary data was used to calculate the PCF, then it must include this field with value the emission factors used for the PCF calculation. Otherwise, this property must be undefined.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_secondaryemissionfactorsources</td></tr></table>

#### Traits

<details>
<summary>List of traits for the secondaryemissionfactorsources attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If secondary data was used to calculate the PCF, then it must include this field with value the emission factors used for the PCF calculation. Otherwise, this property must be undefined.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Secondary emission factor sources</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_secondaryemissionfactorsources"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"90"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#technologicaldqr name="technologicaldqr">technologicaldqr</a>

DQR based on data quality matrix, scoring technological representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Technological DQR</td></tr><tr><td>description</td><td>DQR based on data quality matrix, scoring technological representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_technologicaldqr</td></tr></table>

#### Traits

<details>
<summary>List of traits for the technologicaldqr attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DQR based on data quality matrix, scoring technological representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Technological DQR</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"3"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_technologicaldqr"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"91"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#temporaldqr name="temporaldqr">temporaldqr</a>

DQR based on data quality matrix, scoring temporal representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Temporal DQR</td></tr><tr><td>description</td><td>DQR based on data quality matrix, scoring temporal representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>3</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_temporaldqr</td></tr></table>

#### Traits

<details>
<summary>List of traits for the temporaldqr attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DQR based on data quality matrix, scoring temporal representativeness of sources used for PCF from weighted average of all inputs >5% of PCF emissions. Must be from 1 to 3, inclusive.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Temporal DQR</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"3"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_temporaldqr"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"92"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#uncertaintyassessmentdescription name="uncertaintyassessmentdescription">uncertaintyassessmentdescription</a>

If present, the results, key drivers, and a short qualitative description of the uncertainty assessment.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Uncertainty assessment description</td></tr><tr><td>description</td><td>If present, the results, key drivers, and a short qualitative description of the uncertainty assessment.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_uncertaintyassessmentdescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the uncertaintyassessmentdescription attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>If present, the results, key drivers, and a short qualitative description of the uncertainty assessment.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Uncertainty assessment description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_uncertaintyassessmentdescription"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"93"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#unitaryproductamount name="unitaryproductamount">unitaryproductamount</a>

The amount of declared units contained within the product to which the PCF is referring. The value must be strictly greater than 0.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity represented</td></tr><tr><td>description</td><td>The amount of declared units contained within the product to which the PCF is referring. The value must be strictly greater than 0.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0.0000000001</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitaryproductamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the unitaryproductamount attribute are listed below.</summary>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

*is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The amount of declared units contained within the product to which the PCF is referring. The value must be strictly greater than 0.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity represented</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.constrained*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"0.0000000001"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

*is.nullable*  
  The attribute value may be set to NULL.  

*is.CDS.sourceNamed*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msdyn_unitaryproductamount"</td><td>string</td><td></td></tr></table>

*is.CDS.ordered*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"94"</td><td>integer</td><td></td></tr></table>

*is.dataFormat.numeric.shaped*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#sustainabilityproductitem name="sustainabilityproductitem">sustainabilityproductitem</a>

The product or item this footprint is for.  
First included in: Sustainability/SustainabilityCarbon/ProductFootprint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product or item</td></tr><tr><td>description</td><td>The product or item this footprint is for.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sustainabilityproductitem attribute are listed below.</summary>

*is.dataFormat.character*  
  *is.dataFormat.big*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

*is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

*is.dataFormat.guid*  
  *means.identity.entityId*  
  *is.requiredAtLevel*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

*is.localized.describedAs*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The product or item this footprint is for.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.localized.displayedAs*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product or item</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

*is.CDS.lookup*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

*is.linkedEntity.identifier*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="../SustainabilityShared/ProductSustainability.md" target="_blank">/SustainabilityShared/ProductSustainability.cdm.json/ProductSustainability</a></td><td><a href="../SustainabilityShared/ProductSustainability.md#sustainabilityproductId" target="_blank">sustainabilityproductId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

*is.dataFormat.guid*  
  *is.dataFormat.character*  
  *is.dataFormat.array*  
  indicates a contiguous sequence of fundamental units that should be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>
