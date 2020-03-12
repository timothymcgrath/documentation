# ./Models.MetricMetadata
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | [**String**][1] | Metric description | [optional] [default to null]
**integration** | [**String**][1] | Name of the integration that sent the metric if applicable | [optional] [default to null]
**perUnderscoreunit** | [**String**][1] | Per unit of the metric such as &#x60;second&#x60; in &#x60;bytes per second&#x60; | [optional] [default to null]
**shortUnderscorename** | [**String**][1] | A more human-readable and abbreviated version of the metric name | [optional] [default to null]
**statsdUnderscoreinterval** | [**Long**][2] | Statsd flush interval of the metric in seconds if applicable | [optional] [default to null]
**type** | [**String**][1] | Metric type such as &#x60;gauge&#x60; or &#x60;rate&#x60; | [default to null]
**unit** | [**String**][1] | Primary unit of the metric such as &#x60;byte&#x60; or &#x60;operation&#x60; | [optional] [default to null]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: string.md
[2]: long.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
