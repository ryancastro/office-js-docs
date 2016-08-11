# ConditionalFormatColorScaleRule Object (JavaScript API for Excel)

_Excel 2016, Excel Online, Excel for iPad, Excel for Mac_

Represents a ColorScale Rule for a conditional format, including the color for the rule.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|color|string|HTML color code representing the color of the border line, of the form #RRGGBB (e.g. "FFA500") or as a named HTML color (e.g. "orange").|1.3||
|formula|object|A number, a formula, or null (if Value is LowestValue, HighestValue, or Automatic).|1.3||
|type|string|What the color scale should be based on. Possible values are: LowestValue, HighestValue, Number, Percent, Formula, Percentile, Automatic.|1.3||

_See property access [examples.](#property-access-examples)_

## Relationships
None


## Methods

| Method		   | Return Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|[load(param: object)](#loadparam-object)|void|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|1.1|

## Method Details


### load(param: object)
Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.

#### Syntax
```js
object.load(param);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|:---|
|param|object|Optional. Accepts parameter and relationship names as delimited string or an array. Or, provide [loadOption](loadoption.md) object.|

#### Returns
void