---
title: InsuredHomeAsset in PropertyandCasualtyDataModel - Common Data Model | Microsoft Docs
description: Information of an Insured Home.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/5/2023
ms.author: cdmditeam
---

# Insured home asset in PropertyandCasualtyDataModel(InsuredHomeAsset)

Information of an Insured Home\.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/FinancialServices/PropertyandCasualtyDataModel/InsuredHomeAsset.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InsuredHomeAsset/(resolvedAttributes)/insuredhomeassetId](#insuredhomeassetId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InsuredHomeAsset/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/FinancialServices/PropertyandCasualtyDataModel<br>/InsuredHomeAsset.cdm.json/InsuredHomeAsset<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information of an Insured Home.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insured home asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_insuredhomeasset"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[insuredhomeassetId](#insuredhomeassetId)|Unique identifier for entity instances\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[createdOn](#createdOn)|Date and time when the record was created\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[statecode](#statecode)|Status of the Insured home|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[statuscode](#statuscode)|Reason for the status of the Insured home|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[name](#name)|Required name field\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[areausagetype](#areausagetype)|Area usage type, for example primary dwelling or commercial\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[assetdescription](#assetdescription)|The description of the asset insured under the Policy\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[city](#city)|City of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[countryregion](#countryregion)|Country of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[coverage](#coverage)|Reference to Coverage for Home insurance\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[description](#description)|Location description of the property insured under this Policy\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[fairmarketvalue](#fairmarketvalue)|The estimated current value of the asset when the Policy was issued\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[fairmarketvalue_Base](#fairmarketvalue_Base)|Value of the fair market value in base currency\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[landareausacres](#landareausacres)|The size of the piece of land, which can be a lot or the land on which the property is on \(in acres\)\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[lienholders](#lienholders)|The lienholder who has ownership rights on the asset\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[numberoffloors](#numberoffloors)|Number of floors of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[numberofgaragespaces](#numberofgaragespaces)|The number of parking spaces at the property\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[numberofrooms](#numberofrooms)|Number of rooms of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[numberofstructures](#numberofstructures)|The total number of other structures being insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[postalcode](#postalcode)|Zip/Postal Code of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[primaryowner](#primaryowner)|Primary owner of the asset\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[primaryownerType](#primaryownerType)|Primary owner of the asset\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[propertyimprovements](#propertyimprovements)|Description of any property improvements\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[propertyownership](#propertyownership)|Indication of whether the insured property is owned or mortgaged\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[propertyrating](#propertyrating)|The condition rating of the insured property\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[propertyusage](#propertyusage)|The manner the property is used by the Policy holder such as owner or rented out\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[purchaseamount](#purchaseamount)|The price paid by the customer for the Insured Asset\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[purchaseamount_Base](#purchaseamount_Base)|Value of the purchase amount in base currency\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[purchasedate](#purchasedate)|The date on which the asset was purchased\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[registrationtype](#registrationtype)|The purpose of the insured such as rental, recreational, or personal use\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[state](#state)|State of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[streetaddress](#streetaddress)|Street address of the property insured\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[totalsquarefeet](#totalsquarefeet)|The total square footage of the area usage type\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[typeofproperty](#typeofproperty)|Type of property insured such as a building or office\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|
|[yearbuilt](#yearbuilt)|The year in which the property was built\.|<a href="InsuredHomeAsset.md" target="_blank">PropertyandCasualtyDataModel/InsuredHomeAsset</a>|

### <a href=#insuredhomeassetId name="insuredhomeassetId">insuredhomeassetId</a>

Unique identifier for entity instances\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Insured home asset</td></tr><tr><td>description</td><td>Unique identifier for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msfsi_insuredhomeassetid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the insuredhomeassetId attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.identifiedBy\*\*  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InsuredHomeAsset/(resolvedAttributes)/insuredhomeassetId](#insuredhomeassetId)</td><td>attribute</td><td></td></tr></table>

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insured home asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_insuredhomeassetid"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

\*\*is\.dataFormat\.date\*\*  
  \*\*means\.measurement\.date\*\*  
  \*\*is\.dataFormat\.time\*\*  
  \*\*means\.measurement\.time\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.time\*\*  
  \*\*is\.dataFormat\.date\*\*  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

\*\*is\.dataFormat\.date\*\*  
  \*\*means\.measurement\.date\*\*  
  \*\*is\.dataFormat\.time\*\*  
  \*\*means\.measurement\.time\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.time\*\*  
  \*\*is\.dataFormat\.date\*\*  
  </details>

### <a href=#statecode name="statecode">statecode</a>

Status of the Insured home  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Insured home</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statecode attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*means\.entityState\*\*  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InsuredHomeAsset/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the Insured home</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"25"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#statuscode name="statuscode">statuscode</a>

Reason for the status of the Insured home  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Insured home</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statuscode attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.correlatedWith\*\*  
  the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"statecode"</td><td>attributeName</td><td></td></tr></table>

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the Insured home</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"27"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

\*\*is\.dataFormat\.date\*\*  
  \*\*means\.measurement\.date\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.date\*\*  
  </details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#name name="name">name</a>

Required name field\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Required name field.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Required name field.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_name"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#areausagetype name="areausagetype">areausagetype</a>

Area usage type, for example primary dwelling or commercial\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Area usage type</td></tr><tr><td>description</td><td>Area usage type, for example primary dwelling or commercial.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_areausagetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Dwelling</td><td>104800000</td></tr><tr><td>en</td><td>Commercial</td><td>104800001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the areausagetype attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Dwelling</td><td>104800000</td></tr><tr><td>en</td><td>Commercial</td><td>104800001</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Area usage type, for example primary dwelling or commercial.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Area usage type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_areausagetype"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"35"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#assetdescription name="assetdescription">assetdescription</a>

The description of the asset insured under the Policy\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Asset description</td></tr><tr><td>description</td><td>The description of the asset insured under the Policy.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_assetdescription</td></tr></table>

#### Traits

<details>
<summary>List of traits for the assetdescription attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The description of the asset insured under the Policy.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_assetdescription"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"37"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#city name="city">city</a>

City of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City of the property insured.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_city</td></tr></table>

#### Traits

<details>
<summary>List of traits for the city attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>City of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>City</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_city"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"38"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#countryregion name="countryregion">countryregion</a>

Country of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country of the property insured.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_countryregion</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countryregion attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/Region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_countryregion"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"39"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#coverage name="coverage">coverage</a>

Reference to Coverage for Home insurance\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Coverage</td></tr><tr><td>description</td><td>Reference to Coverage for Home insurance.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the coverage attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference to Coverage for Home insurance.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Coverage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.CDS\.lookup\*\*  
  The attribute represents a style of lookup in CDS for Applications  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>style</td><td>"single"</td><td>string</td><td></td></tr></table>

\*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Coverage.md" target="_blank">Coverage.cdm.json/Coverage</a></td><td><a href="Coverage.md#coverageId" target="_blank">coverageId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#description name="description">description</a>

Location description of the property insured under this Policy\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Location description of the property insured under this Policy.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_description</td></tr></table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Location description of the property insured under this Policy.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_description"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"41"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#fairmarketvalue name="fairmarketvalue">fairmarketvalue</a>

The estimated current value of the asset when the Policy was issued\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fair market value</td></tr><tr><td>description</td><td>The estimated current value of the asset when the Policy was issued.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_fairmarketvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fairmarketvalue attribute are listed below.</summary>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means\.measurement\.currency\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The estimated current value of the asset when the Policy was issued.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fair market value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_fairmarketvalue"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"42"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#fairmarketvalue_Base name="fairmarketvalue_Base">fairmarketvalue_Base</a>

Value of the fair market value in base currency\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fair market value (base)</td></tr><tr><td>description</td><td>Value of the fair market value in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_fairmarketvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fairmarketvalue_Base attribute are listed below.</summary>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means\.measurement\.currency\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the fair market value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fair market value (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_fairmarketvalue_base"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"46"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#landareausacres name="landareausacres">landareausacres</a>

The size of the piece of land, which can be a lot or the land on which the property is on \(in acres\)\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Land area US acres</td></tr><tr><td>description</td><td>The size of the piece of land, which can be a lot or the land on which the property is on (in acres).</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_landareausacres</td></tr></table>

#### Traits

<details>
<summary>List of traits for the landareausacres attribute are listed below.</summary>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The size of the piece of land, which can be a lot or the land on which the property is on (in acres).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Land area US acres</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_landareausacres"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"47"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#lienholders name="lienholders">lienholders</a>

The lienholder who has ownership rights on the asset\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lienholders</td></tr><tr><td>description</td><td>The lienholder who has ownership rights on the asset.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_lienholders</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lienholders attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The lienholder who has ownership rights on the asset.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lienholders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"2000"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_lienholders"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"48"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#numberoffloors name="numberoffloors">numberoffloors</a>

Number of floors of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of floors</td></tr><tr><td>description</td><td>Number of floors of the property insured.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_numberoffloors</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberoffloors attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of floors of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of floors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_numberoffloors"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"49"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#numberofgaragespaces name="numberofgaragespaces">numberofgaragespaces</a>

The number of parking spaces at the property\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of garage spaces</td></tr><tr><td>description</td><td>The number of parking spaces at the property.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_numberofgaragespaces</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberofgaragespaces attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The number of parking spaces at the property.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of garage spaces</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_numberofgaragespaces"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"50"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#numberofrooms name="numberofrooms">numberofrooms</a>

Number of rooms of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms</td></tr><tr><td>description</td><td>Number of rooms of the property insured.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_numberofrooms</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberofrooms attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of rooms of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of rooms</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_numberofrooms"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"51"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#numberofstructures name="numberofstructures">numberofstructures</a>

The total number of other structures being insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of structures</td></tr><tr><td>description</td><td>The total number of other structures being insured.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_numberofstructures</td></tr></table>

#### Traits

<details>
<summary>List of traits for the numberofstructures attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The total number of other structures being insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of structures</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_numberofstructures"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"52"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#postalcode name="postalcode">postalcode</a>

Zip/Postal Code of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Zip/Postal Code of the property insured.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_postalcode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postalcode attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Zip/Postal Code of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Postal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_postalcode"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"53"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#primaryowner name="primaryowner">primaryowner</a>

Primary owner of the asset\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary owner</td></tr><tr><td>description</td><td>Primary owner of the asset.</td></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the primaryowner attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.dataFormat\.guid\*\*  
  \*\*means\.identity\.entityId\*\*  
  \*\*is\.linkedEntity\.identifier\*\*  
  Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th><th>relationshipName</th></tr><tr><td><a href="Account.md" target="_blank">Account.cdm.json/Account</a></td><td><a href="Account.md#accountId" target="_blank">accountId</a></td></tr><tr><td><a href="Contact.md" target="_blank">Contact.cdm.json/Contact</a></td><td><a href="Contact.md#contactId" target="_blank">contactId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary owner of the asset.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.guid\*\*  
  \*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#primaryownerType name="primaryownerType">primaryownerType</a>

Primary owner of the asset\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary owner</td></tr><tr><td>description</td><td>Primary owner of the asset.</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the primaryownerType attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*means\.entityName\*\*  
  a string value is the name of a CDM entity.  

\*\*is\.linkedEntity\.name\*\*  
  Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.  

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary owner of the asset.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary owner</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#propertyimprovements name="propertyimprovements">propertyimprovements</a>

Description of any property improvements\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property improvements</td></tr><tr><td>description</td><td>Description of any property improvements.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_propertyimprovements</td></tr></table>

#### Traits

<details>
<summary>List of traits for the propertyimprovements attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description of any property improvements.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Property improvements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_propertyimprovements"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"55"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#propertyownership name="propertyownership">propertyownership</a>

Indication of whether the insured property is owned or mortgaged\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property ownership</td></tr><tr><td>description</td><td>Indication of whether the insured property is owned or mortgaged.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_propertyownership</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Owned</td><td>104800000</td></tr><tr><td>en</td><td>Mortgaged</td><td>104800001</td></tr><tr><td>en</td><td>Leased</td><td>104800002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the propertyownership attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Owned</td><td>104800000</td></tr><tr><td>en</td><td>Mortgaged</td><td>104800001</td></tr><tr><td>en</td><td>Leased</td><td>104800002</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indication of whether the insured property is owned or mortgaged.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Property ownership</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_propertyownership"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"56"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#propertyrating name="propertyrating">propertyrating</a>

The condition rating of the insured property\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property rating</td></tr><tr><td>description</td><td>The condition rating of the insured property.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_propertyrating</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>104800000</td></tr><tr><td>en</td><td>Medium</td><td>104800001</td></tr><tr><td>en</td><td>High</td><td>104800002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the propertyrating attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>104800000</td></tr><tr><td>en</td><td>Medium</td><td>104800001</td></tr><tr><td>en</td><td>High</td><td>104800002</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The condition rating of the insured property.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Property rating</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_propertyrating"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"58"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#propertyusage name="propertyusage">propertyusage</a>

The manner the property is used by the Policy holder such as owner or rented out\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property usage</td></tr><tr><td>description</td><td>The manner the property is used by the Policy holder such as owner or rented out.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_propertyusage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Owned</td><td>104800000</td></tr><tr><td>en</td><td>Rented</td><td>104800001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the propertyusage attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Owned</td><td>104800000</td></tr><tr><td>en</td><td>Rented</td><td>104800001</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The manner the property is used by the Policy holder such as owner or rented out.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Property usage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_propertyusage"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"60"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#purchaseamount name="purchaseamount">purchaseamount</a>

The price paid by the customer for the Insured Asset\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase amount</td></tr><tr><td>description</td><td>The price paid by the customer for the Insured Asset.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_purchaseamount</td></tr></table>

#### Traits

<details>
<summary>List of traits for the purchaseamount attribute are listed below.</summary>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means\.measurement\.currency\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The price paid by the customer for the Insured Asset.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_purchaseamount"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"62"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#purchaseamount_Base name="purchaseamount_Base">purchaseamount_Base</a>

Value of the purchase amount in base currency\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase amount (base)</td></tr><tr><td>description</td><td>Value of the purchase amount in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_purchaseamount_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the purchaseamount_Base attribute are listed below.</summary>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means\.measurement\.currency\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the purchase amount in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase amount (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_purchaseamount_base"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"63"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.numeric\.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#purchasedate name="purchasedate">purchasedate</a>

The date on which the asset was purchased\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase date</td></tr><tr><td>description</td><td>The date on which the asset was purchased.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_purchasedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the purchasedate attribute are listed below.</summary>

\*\*is\.dataFormat\.date\*\*  
  \*\*means\.measurement\.date\*\*  
  \*\*is\.dataFormat\.time\*\*  
  \*\*means\.measurement\.time\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the asset was purchased.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_purchasedate"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"64"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.time\*\*  
  \*\*is\.dataFormat\.date\*\*  
  </details>

### <a href=#registrationtype name="registrationtype">registrationtype</a>

The purpose of the insured such as rental, recreational, or personal use\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration type</td></tr><tr><td>description</td><td>The purpose of the insured such as rental, recreational, or personal use.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_registrationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Rental</td><td>104800000</td></tr><tr><td>en</td><td>Recreational</td><td>104800001</td></tr><tr><td>en</td><td>Personal use</td><td>104800002</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the registrationtype attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Rental</td><td>104800000</td></tr><tr><td>en</td><td>Recreational</td><td>104800001</td></tr><tr><td>en</td><td>Personal use</td><td>104800002</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The purpose of the insured such as rental, recreational, or personal use.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_registrationtype"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"65"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#state name="state">state</a>

State of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State of the property insured.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_state</td></tr></table>

#### Traits

<details>
<summary>List of traits for the state attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_state"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"67"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#streetaddress name="streetaddress">streetaddress</a>

Street address of the property insured\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street address</td></tr><tr><td>description</td><td>Street address of the property insured.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_streetaddress</td></tr></table>

#### Traits

<details>
<summary>List of traits for the streetaddress attribute are listed below.</summary>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Street address of the property insured.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Street address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_streetaddress"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"68"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.character\*\*  
  \*\*is\.dataFormat\.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#totalsquarefeet name="totalsquarefeet">totalsquarefeet</a>

The total square footage of the area usage type\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total square feet</td></tr><tr><td>description</td><td>The total square footage of the area usage type.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_totalsquarefeet</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalsquarefeet attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The total square footage of the area usage type.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total square feet</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_totalsquarefeet"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"69"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#typeofproperty name="typeofproperty">typeofproperty</a>

Type of property insured such as a building or office\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type of property</td></tr><tr><td>description</td><td>Type of property insured such as a building or office.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_typeofproperty</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Building</td><td>104800000</td></tr><tr><td>en</td><td>Office</td><td>104800001</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the typeofproperty attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*does\.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Building</td><td>104800000</td></tr><tr><td>en</td><td>Office</td><td>104800001</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is\.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of property insured such as a building or office.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of property</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_typeofproperty"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"70"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>

### <a href=#yearbuilt name="yearbuilt">yearbuilt</a>

The year in which the property was built\.  
First included in: PropertyandCasualtyDataModel/InsuredHomeAsset \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year built</td></tr><tr><td>description</td><td>The year in which the property was built.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_yearbuilt</td></tr></table>

#### Traits

<details>
<summary>List of traits for the yearbuilt attribute are listed below.</summary>

\*\*is\.dataFormat\.integer\*\*  
  \*\*is\.dataFormat\.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is\.dataFormat\.numeric\*\*  
  \*\*is\.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is\.localized\.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The year in which the property was built.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.localized\.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year built</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is\.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is\.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is\.CDS\.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_yearbuilt"</td><td>string</td><td></td></tr></table>

\*\*is\.CDS\.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"72"</td><td>integer</td><td></td></tr></table>

\*\*is\.dataFormat\.integer\*\*  
  </details>
