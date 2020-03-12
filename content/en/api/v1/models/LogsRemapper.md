# ./Models.LogsRemapper
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**overrideUnderscoreonUnderscoreconflict** | [**Boolean**][1] | Override or not the target element if already set | [optional] [default to false]
**preserveUnderscoresource** | [**Boolean**][1] | Remove or preserve the remapped source element | [optional] [default to false]
**sourceUnderscoretype** | [**String**][2] | Defines if the sources are from log &#x60;attribute&#x60; or &#x60;tag&#x60; | [optional] [default to attribute]
**sources** | [**List**][2] | Array of source attributes. | [default to null]
**target** | [**String**][2] | Final attribute or tag name to remap the sources to. | [default to null]
**targetUnderscoretype** | [**String**][2] | Defines if the sources are from log &#x60;attribute&#x60; or &#x60;tag&#x60; | [optional] [default to attribute]
**type** | [**String**][2] | Type of processor | [optional] [default to attribute-remapper]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: boolean.md
[2]: string.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
