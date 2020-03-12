# ./Models.HistoryServiceLevelObjectiveOverall
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**history** | [**List**][1] | For &#x60;monitor&#x60; based SLOs, this includes the aggregated history uptime time series. | [optional] [default to null]
**name** | [**String**][2] | For &#x60;monitor&#x60; based SLOs this represents the overall group. | [optional] [default to null]
**precision** | [**Map**][3] | A mapping of threshold &#x60;timeframe&#x60; to number of accurate decimals, regardless of the from &amp;&amp; to timestamp. | [optional] [default to null]
**preview** | [**Boolean**][4] | For &#x60;monitor&#x60; based SLOs when &#x60;true&#x60; this indicates that a replay is in progress to give an accurate uptime calculation. | [optional] [default to null]
**spanUnderscoreprecision** | [**Double**][3] | The amount of decimal places the uptime value is accurate to for the given from and to timestamp. | [optional] [default to null]
**uptime** | [**Double**][3] | The uptime value of the SLO history window. | [optional] [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: array.md
[2]: string.md
[3]: double.md
[4]: boolean.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
