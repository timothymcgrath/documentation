# ./Models.MetricsQueryResponseSeries
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**aggr** | [**String**][1] | Aggregation type | [optional] [default to null]
**displayUnderscorename** | [**String**][1] | Display name of the metric | [optional] [default to null]
**end** | [**Long**][2] | End of the time window, milliseconds since Unix epoch | [optional] [default to null]
**expression** | [**String**][1] | Metric expression | [optional] [default to null]
**interval** | [**Long**][2] | Number of seconds between data samples | [optional] [default to null]
**length** | [**Long**][2] | Number of data samples | [optional] [default to null]
**metric** | [**String**][1] | Metric name | [optional] [default to null]
**pointlist** | [**List**][3] | List of points of the time series | [optional] [default to null]
**scope** | [**String**][1] | Metric scope, comma separated list of tags | [optional] [default to null]
**start** | [**Long**][2] | Start of the time window, milliseconds since Unix epoch | [optional] [default to null]
**unit** | [**List**][4] | Detailed information about the metric unit. First element describes the \&quot;primary unit\&quot; (e.g. &#x60;bytes&#x60; in &#x60;bytes per second&#x60;), second describes the \&quot;per unit\&quot; (e.g. &#x60;second&#x60; in &#x60;bytes per second&#x60;) | [optional] [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: string.md
[2]: long.md
[3]: array.md
[4]: MetricsQueryResponse_unit.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
