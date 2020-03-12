# ./Models.LogsArithmeticProcessor
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expression** | [**String**][1] | Arithmetic operation between one or more log attributes. | [default to null]
**isUnderscorereplaceUnderscoremissing** | [**Boolean**][2] | If &#x60;true&#x60;, it replaces all missing attributes of expression by &#x60;0&#x60;, &#x60;false&#x60; skip the operation if an attribute is missing. | [optional] [default to false]
**target** | [**String**][1] | Name of the attribute that contains the result of the arithmetic operation. | [default to null]
**type** | [**String**][1] | Type of processor | [optional] [default to arithmetic-processor]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: string.md
[2]: boolean.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
