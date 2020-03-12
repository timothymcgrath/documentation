# ./Models.MetricsQueryResponse
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**error** | [**String**][1] | Message indicating the errors if status is not &#x60;ok&#x60; | [optional] [default to null]
**fromUnderscoredate** | [**Long**][2] | Start of requested time window, milliseconds since Unix epoch | [optional] [default to null]
**groupUnderscoreby** | [**List**][1] | List of tag keys on which to group | [optional] [default to null]
**message** | [**String**][1] | Message indicating &#x60;success&#x60; if status is &#x60;ok&#x60; | [optional] [default to null]
**query** | [**String**][1] | Query string | [optional] [default to null]
**resUnderscoretype** | [**String**][1] | Type of response | [optional] [default to null]
**series** | [**List**][3] | List of timeseries queried | [optional] [default to null]
**status** | [**String**][1] | Status of the query | [optional] [default to null]
**toUnderscoredate** | [**Long**][2] | End of requested time window, milliseconds since Unix epoch | [optional] [default to null]

[[Back to Model list]][4] [[Back to API list]][5] [[Back to README]][6]

[1]: string.md
[2]: long.md
[3]: MetricsQueryResponse_series.md
[4]: ../README.md#documentation-for-models
[5]: ../README.md#documentation-for-api-endpoints
[6]: ../README.md
