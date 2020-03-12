# ./Models.Series
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**host** | [**String**][1] | The name of the host that produced the metric. | [optional] [default to null]
**interval** | [**Long**][2] | If the type of the metric is rate or count, define the corresponding interval. | [optional] [default to null]
**metric** | [**String**][1] | The name of the timeseries | [default to null]
**points** | [**List**][3] |  | [default to null]
**tags** | [**List**][1] | A list of tags associated with the metric. | [optional] [default to null]
**type** | [**String**][1] |  | [optional] [default to gauge]

[[Back to Model list]][4] [[Back to API list]][5] [[Back to README]][6]

[1]: string.md
[2]: long.md
[3]: array.md
[4]: ../README.md#documentation-for-models
[5]: ../README.md#documentation-for-api-endpoints
[6]: ../README.md
