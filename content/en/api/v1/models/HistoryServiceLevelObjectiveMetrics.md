# ./Models.HistoryServiceLevelObjectiveMetrics
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**denominator** | [**HistoryServiceLevelObjectiveMetricsSeries**][1] |  | [default to null]
**interval** | [**Long**][2] | The aggregated query interval for the series data. It&#39;s implicit based on the query time window. | [default to null]
**message** | [**String**][3] | Optional message if there are specific query issues/warnings. | [optional] [default to null]
**numerator** | [**HistoryServiceLevelObjectiveMetricsSeries**][1] |  | [default to null]
**query** | [**String**][3] | The combined numerator &amp;&amp; denominator query CSV. | [default to null]
**resUnderscoretype** | [**String**][3] | The series result type. This mimics &#x60;batch_query&#x60; response type | [default to null]
**respUnderscoreversion** | [**Long**][2] | The series response version type. This mimics &#x60;batch_query&#x60; response type | [default to null]
**times** | [**List**][4] | The query timestamps in epoch milliseconds | [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: HistoryServiceLevelObjectiveMetricsSeries.md
[2]: long.md
[3]: string.md
[4]: double.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
