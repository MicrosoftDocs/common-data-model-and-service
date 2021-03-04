---
title: Resolution guidance
description: Clarify and illustrate the process that resolves logical entities into a concrete attribute list.
author: msftman
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 02/24/2021
ms.author: Deonhe
---

# Resolution guidance (Deprecated)

> **__Note:__** Resolution guidance has pre-configured and sometimes obscure behavior that varies depending on the directives provided which could cause the definitions to be resolved into a shape different than expected if not properly configured. This feature is now deprecated in favor of the [Projections feature](convert-logical-entities-resolved-entities.md#projection-overview) which removes all the implict behavior and has more power than resolution guidance.

To further clarify and illustrate the process that resolves logical entities into a concrete attribute list, consider this example schema:

<!-- image26 -->
![Resolution guidance](../media/sdk/convert-logical-entities-resolved-entities/resolution-guidance.png) 

Holding in mind the **shipTo** entity attribute defined in the Customer entity above, consider this pipeline of operations that's performed on the set of attributes that result from the Addresses entity. (Note that for explanatory purposes, this list describes every possible stage even though, in reality, not all of them apply in all situations.) 

| Stage                         | Does                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Example                                                                                                                                                                                                                                  |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| all source attributes         | Takes all attributes in the natural order from the source entity.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | The Addresses entity combines the Residential and Business Address entities into this list of attributes: [addressId, line1, city, ST, postalCode, careOf, line2]                                                                        |
| polymorphic factoring         | When a source entity is a combination of many other entities, the attributes of those entities will be combined and merged. The default meaning of the combination is AND; that is, the data values for one row of data are assumed to be from a combination of the domains of the sub-entities. In the case where an OR should be considered—that is, the data values for one row should be assumed to be from just one of the sub-entities at a time—this stage will mark the set appropriately.                                   | The schema will be written in a way to indicate that per record, one should expect values in either the attributes [addressId, line1, city, ST, postalCode] OR in the attributes [addressId, careOf, line1, line2, city, ST, postalCode] |
| take only an ordered set      | Selects out only attributes mentioned in a given list. Also, the input attributes are reordered to match the order in the list.                                                                                                                                                                                                                                                                                                                                                                                                      | Take (addressId, postalCode, line1, line2, poBox, careOf) produces [addressId, postalCode, line1, line2, careOf]                                                                                                                         |
| remove from a set             | Removes the listed attributes from the input set. All others pass through in their original order.                                                                                                                                                                                                                                                                                                                                                                                                                                   | Remove (line2, firstName, careOf) produces [addressId, postalCode, line1]                                                                                                                                                                |
| augment with supporting       | Adds a provided attribute to the set and adds a trait to the attribute indicating it was addedInSupportOf(input attribute).                                                                                                                                                                                                                                                                                                                                                                                                          | (breaking from the example for just this stage) Input attribute (statusCode) augment with supporting {statusCode_display} produces [statusCode, statusCode_display with addedInSupportOf(statusCode)]                                    |
| foreign key replacement       | Replace all input attributes with the provided attribute, and mark that new attribute as a link to the source entity.                                                                                                                                                                                                                                                                                                                                                                                                                | (back to the example set) Replace with foreignKey {addId} produces [addId with is.Linked.Identifier (Addresses on addressId, because of the polymorphic stage, this actually gets two links, one to each sub-entity) ]                   |
| indicate poly type            | For the case from stage 2 where a polymorphic OR is needed, this stage adds a specified attribute that's used to indicate the per-record type that matches one of the source entities.                                                                                                                                                                                                                                                                                                                                               | Indicate type with {‘addType’} results in [addId, addType with is.entity.type trait} ] this addType attribute's data values should indicate the kind of record to consider.                                                              |
| duplicate for array expansion | Makes *n* copies of every input attribute, and marks each temporarily with an ordinal.                                                                                                                                                                                                                                                                                                                                                                                                                                               | Copy from one to three results in [addId(1), addType(1), addId(2), addType(2), addId(3), addType(3)]                                                                                                                                     |
| Indicate count                | Adds a provided attribute to the set and marks it with a trait indicating that for each record, this attribute holds the count of array members that should be expected to contain data values.                                                                                                                                                                                                                                                                                                                                      | Indicate count with {addCount} results in [addId(1), addType(1), addId(2), addType(2), addId(3), addType(3), addCount with trait indicating it holds a count]                                                                            |
| Rename with format            | Renames each attribute in the input set by applying a provided format string. The format string can contain one instance each of the replacement indicators ('{a}' or '{A}') for the (lowercase or uppercase first character) name of the containing attribute name (in our example, 'shipTo'), ('{m}' or '{M}') for the (lowercase or uppercase first character) name of the set member (like 'line1' or 'addId' and '{o}' for the held ordinal of the attribute in the set. Examples are "{m}AsPartOf{A}", "{a}{M}" or "{a}{M}{o}" | Rename with "{a}_{m}_{o}" produces [ shipTo_addId_1, shipTo_addType_1, shipTo_addId_2, shipTo_addType_2, shipTo_addId_3, shipTo_addType_3, shipTo_addCount]                                                                              |
| merge results                 | Any attributes in the set with identical names will be merged together; that is, one attribute will result with traits of all source attributes combined into one uniquely named set. Then, any resulting attributes from this pipeline will be merged in the same way into the final set of attributes for the outer entity that's being defined.                                                                                                                                                                                   | [ customerId, shipTo_addId_1, shipTo_addType_1, shipTo_addId_2, shipTo_addType_2, shipTo_addId_3, shipTo_addType_3, shipTo_addCount]                                                                                                     |

The example above was contrived to demonstrate each stage, but in most situations these stages won't all occur. For a given attribute or base entity, the settings in the associated resolution guidance structure—along with any resolution directives that are supplied at resolution time—will interact with, and trigger, stages.

| Stage                         | When applied                                                                                                                                                                                            | Reason/notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| all source attributes         | Always                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| polymorphic factoring         | SelectsSubAttributes.selects = "one"                                                                                                                                                                    | The referenced entity should be a container of other entity typed attributes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| take only an ordered set      | SelectsSubAttributes.selects = "some"                                                                                                                                                                   | If set, the list of attribute names in the SelectsSubAttributes. SelectsSomeTakeNames array will be used to filter in and reorder the source attributes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| remove from a set             | SelectsSubAttributes.selects = "some"                                                                                                                                                                   | If set, the list of attribute names in the SelectsSubAttributes. SelectesSomeAvoidNames array will be used to filter out attributes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| augment with supporting       | An attribute definition in the addSupportingAttribute property will be added and will indicate that it supports the one other attribute in the set.                                                     | This stage is only applied to a single dataType attribute, not a set from an entity.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| foreign key replacement       | If EntityByReference.AllowReference = true AND (the "ByReference" directive is applied OR the depth of entities traversed in resolving the top entity is \> EntityByReference. ReferenceOnlyAfterDepth) | The default resolution guidance allows references and sets a maximum depth of five. The attribute definition stored in **EntityByReference. ForeignKeyAttribute** will be added in place of the input set. If none is specified, a default attribute named **id** is used.                                                                                                                                                                                                                                                                                                                                                                                   |
| indicate poly type            | SelectsSubAttributes.selects = "one"                                                                                                                                                                    | The attribute definition stored in the SelectsSubAttributes. SelectedTypeAttribute will be added to the set. If not set, a default attribute named “type” will be used.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| duplicate for array expansion | Cardinality="many" and the structured directive isn't set, or the normalized directive is set                                                                                                           | The **StartingOrdinal** and **MaximumExpansion** properties in the Expansion structure control the number and ordinals or repeats. A structured directive builds a description that assumes array indicators are built into the storage system (like JSON doc or Parquet), so expanding the array isn't done. Note: The normalized directive assumes that entity-to-entity relationships are only modeled from the "many" side; that is, the referencing side of a relationship that points at one instance of another entity. For this reason, if normalized is the directive, the array expansion stage will instead *remove* all attributes from the set. |
| Indicate count                | If the duplicate for array stage is triggered                                                                                                                                                           | The attribute definition in the **Expansion.CountAttribute** property is added to the set.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Rename with format            | Structured directive isn't given and a format is set in the **renameFormat** property.                                                                                                                  | Structured output creates groups for entity attributes, so renaming isn't needed to prevent name conflicts                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| merge results                 | Always                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

## The ResolutionGuidance structure in detail

- bool removeAttribute

    If true, this attribute definition will be removed from the entity's final resolved attribute list. This functionality has been moved to the 'selectsSomeAvoidList' property.

- List\<string\> imposedDirectives

    A list of strings, one for each 'directive' that should be always imposed at this attribute definition.

- List\<string\> removedDirectives

    A list of strings, one for each 'directive' that should be removed if it was previously imposed.

- Common Data ModelTypeAttributeDefinition addSupportingAttribute

    A guidance that this attribute definition should be added to the final set of attributes and should be marked as 'supporting' the attribute that has the guidance set on it.

- string cardinality

    If 'one', a single instance of the attribute or entity has been used. If 'many', multiple instances have been used, in which case the 'expansion' properties will describe the array enumeration to use when needed.

- string renameFormat

    Format specifier for generated attribute names. Might contain a single occurrence of ('{a} or 'A'), ('{m}' or '{M}'), and '{o}', for the base (a/A)ttribute name, any (m/M)ember attributes from entities and array (o)rdinal. Examples: '{a}{o}.{m}' could produce 'address2.city', '{a}{o}' gives 'city1'. Using '{A}' or '{M}' will uppercase the first letter of the name portions.

## Expansion

Parameters that control array expansion if inline repeating of attributes is needed.

- int startingOrdinal

    The index to start counting from when an array is being expanded for a repeating set of attributes.

- int maximumExpansion

    The maximum number of times that the attribute pattern should be repeated.

- Common Data ModelTypeAttributeDefinition countAttribute

    The supplied attribute definition will be added to the entity to represent the total number of instances found in the data.

## EntityByReference

Parameters that control the use of foreign keys to reference entity instances instead of embedding the entity in a nested way.

- bool allowReference

    Whether a reference to an entity is allowed through the use of a foreign key to the entity.

- bool alwaysIncludeForeignKey

    If true, a foreign key attribute will be added to the entity even when the entity attribute is embedded in a nested way.

- int referenceOnlyAfterDepth

    After a given depth of non-reference nesting by using entity attributes, the 'referenceOnly' directive will be imposed.

- Common Data ModelTypeAttributeDefinition foreignKeyAttribute

    The supplied attribute definition will be added to the entity to hold a foreign key value for the referenced entity.

    Used to indicate that this attribute selects either 'one' or 'all' of the sub-attributes from an entity. If the 'structured' directive is set, this trait causes resolved attributes to end up in groups rather than a flattened list.

## SelectsSubAttribute

- string selects

    Used to indicate either 'one' or 'all' sub-attributes selected.

- Common Data ModelTypeAttributeDefinition selectedTypeAttribute

    The supplied attribute definition will be added to the entity to hold a description of the single attribute that was selected from the sub-entity when 'one' is selected.

- List\<string\> selectsSomeTakeNames

    The list of sub-attributes from an entity that should be added.

- List\<string\> selectsSomeAvoidNames

    The list of sub-attributes from an entity that shouldn't be added.

## Revisiting the three examples

Recall this diagram of our simple logical entities:

<!-- image27 -->
![Simple logical entities](../media/sdk/convert-logical-entities-resolved-entities/simple-logical-entities.png) 

By using the Common Data Model JSON grammar, these logical entities are expressed like this:

<!-- image28 -->
![Image showing how logical entities are expressed](../media/sdk/convert-logical-entities-resolved-entities/simple-logical-entities-2.png) 

To resolve the SmallBusiness entity into this shape:

<!-- image29 -->
![The smallbusiness entity shape](../media/sdk/convert-logical-entities-resolved-entities/small-business-entity-shape.png) 

We can restate the SmallBusiness entity with some attribute guidance. This creates a new entity that extends SmallBusiness. For clarity, we'll also give it a new name.

<!-- image30 -->
![The smallbusiness entity shape with a new name](../media/sdk/convert-logical-entities-resolved-entities/small-business-entity-shape-new-name.png) 

To resolve the SmallBusiness entity into this shape:

<!-- image31 -->
![The resolved SmallBusiness entity shape](../media/sdk/convert-logical-entities-resolved-entities/small-business-entity-shape-resolved.png) 

We can restate the SmallBusiness entity with some attribute guidance.

 <!-- image32 -->
![Image showing how to restate the SmallBusiness entity](../media/sdk/convert-logical-entities-resolved-entities/small-business-entity-shape-resolved-2.png) 

To resolve the SmallBusiness entity into this shape:

 <!-- image33 -->
![Image showing the resolved SmallBusiness entity](../media/sdk/convert-logical-entities-resolved-entities/small-business-entity-shape-resolved2.png) 

We can simply resolve the logical entity with no added guidance, and use the structured directive.

## The attribute promise

There are places in a Common Data Model entity or manifest document where one must make a reference to an attribute from another entity. Examples include describing one-to-many relationships in the manifest. Because the final set of attributes for a logical entity can come from base entities or from embedded entities, these references use a special path syntax called an attribute promise. The promise takes the form:

[normal path up to the entity name]/(resolvedAttributes)/[expectedAttributeName]

When the object model is used to get a reference to one of these attribute objects, the entity containing the attribute will be resolved by using the current set of directives and the attribute will be located in the final resolved set.
