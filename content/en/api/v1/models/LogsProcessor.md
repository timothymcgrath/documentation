# ./Models.LogsProcessor
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**isUnderscoreenabled** | [**Boolean**][1] | Whether or not the processor is enabled | [optional] [default to false]
**name** | [**String**][2] | Name of the processor | [optional] [default to null]
**grok** | [**LogsGrokParserRules**][3] |  | [default to null]
**samples** | [**List**][2] | List of sample logs to test this grok parser | [optional] [default to null]
**source** | [**String**][2] | Source attribute used to perform the lookup. | [default to null]
**type** | [**String**][2] | Type of processor | [optional] [default to trace-id-remapper]
**sources** | [**List**][2] | Array of source attributes | [default to ["dd.trace_id"]]
**overrideUnderscoreonUnderscoreconflict** | [**Boolean**][1] | Override or not the target element if already set | [optional] [default to false]
**preserveUnderscoresource** | [**Boolean**][1] | Remove or preserve the remapped source element | [optional] [default to false]
**sourceUnderscoretype** | [**String**][2] | Defines if the sources are from log &#x60;attribute&#x60; or &#x60;tag&#x60; | [optional] [default to attribute]
**target** | [**String**][2] | Name of the attribute that contains the corresponding value in the mapping list or the &#x60;default_lookup&#x60; if not found in the mapping list. | [default to null]
**targetUnderscoretype** | [**String**][2] | Defines if the sources are from log &#x60;attribute&#x60; or &#x60;tag&#x60; | [optional] [default to attribute]
**isUnderscoreencoded** | [**Boolean**][1] | Define if the source attribute is url encoded or not | [optional] [default to false]
**categories** | [**List**][4] | Array of filters to match or not a log and their corresponding &#x60;name&#x60; to assign a custom value to the log. | [default to null]
**expression** | [**String**][2] | Arithmetic operation between one or more log attributes. | [default to null]
**isUnderscorereplaceUnderscoremissing** | [**Boolean**][1] | If true, it replaces all missing attributes of &#x60;template&#x60; by an empty string. If &#x60;false&#x60; (default), skips the operation for missing attributes. | [optional] [default to false]
**template** | [**String**][2] | A formula with one or more attributes and raw text. | [default to null]
**defaultUnderscorelookup** | [**String**][2] | Value to set the target attribute if the source value is not found in the list. | [optional] [default to null]
**lookupUnderscoretable** | [**List**][2] | Mapping table of values for the source attribute and their associated target attribute values, formatted as &#x60;[\&quot;source_key1,target_value1\&quot;, \&quot;source_key2,target_value2\&quot;]&#x60; | [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: boolean.md
[2]: string.md
[3]: LogsGrokParserRules.md
[4]: LogsCategoryProcessor_categories.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
