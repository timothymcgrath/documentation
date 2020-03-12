# ./Models.LogsListRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | [**String**][1] | For multi-index organizations, the log index in which the request is performed. | [optional] [default to null]
**limit** | [**Integer**][2] | Number of logs return in the response. | [optional] [default to null]
**query** | [**String**][1] | The search query - following the Log search syntax. | [default to null]
**sort** | [**LogsSort**][3] |  | [optional] [default to null]
**startAt** | [**String**][1] | Hash identifier of the first log to return in the list, available in a log &#x60;id&#x60; attribute. This parameter is used for the pagination feature. **Note**: this parameter is ignored if the corresponding log is out of the scope of the specified time window. | [optional] [default to null]
**time** | [**LogsListRequest_time**][4] |  | [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: string.md
[2]: integer.md
[3]: LogsSort.md
[4]: LogsListRequest_time.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
