# ./Models.LogsLookupProcessor
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**defaultUnderscorelookup** | [**String**][1] | Value to set the target attribute if the source value is not found in the list. | [optional] [default to null]
**lookupUnderscoretable** | [**List**][1] | Mapping table of values for the source attribute and their associated target attribute values, formatted as &#x60;[\&quot;source_key1,target_value1\&quot;, \&quot;source_key2,target_value2\&quot;]&#x60; | [default to null]
**source** | [**String**][1] | Source attribute used to perform the lookup. | [default to null]
**target** | [**String**][1] | Name of the attribute that contains the corresponding value in the mapping list or the &#x60;default_lookup&#x60; if not found in the mapping list. | [default to null]
**type** | [**String**][1] | Type of processor | [optional] [default to lookup-processor]

[[Back to Model list]][2] [[Back to API list]][3] [[Back to README]][4]

[1]: string.md
[2]: ../README.md#documentation-for-models
[3]: ../README.md#documentation-for-api-endpoints
[4]: ../README.md
