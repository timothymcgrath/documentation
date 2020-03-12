# ./Models.LogsUserAgentParser
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**isUnderscoreencoded** | [**Boolean**][1] | Define if the source attribute is url encoded or not | [optional] [default to false]
**sources** | [**List**][2] | Array of source attributes | [default to ["http.useragent"]]
**target** | [**String**][2] | Name of the parent attribute that contains all the extracted details from the &#x60;sources&#x60; | [default to http.useragent_details]
**type** | [**String**][2] | Type of processor | [optional] [default to user-agent-parser]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: boolean.md
[2]: string.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
