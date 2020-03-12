# ./Models.HistoryServiceLevelObjectiveResponseData
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fromUnderscorets** | [**Long**][1] | the &#x60;from&#x60; timestamp in epoch seconds | [optional] [default to null]
**groups** | [**HistoryServiceLevelObjectiveGroups**][2] |  | [optional] [default to null]
**overall** | [**HistoryServiceLevelObjectiveOverall**][3] |  | [optional] [default to null]
**series** | [**HistoryServiceLevelObjectiveMetrics**][4] |  | [optional] [default to null]
**thresholds** | [**Map**][5] | mapping of string timeframe to the SLO threshold. | [optional] [default to null]
**toUnderscorets** | [**Long**][1] | the &#x60;to&#x60; timestamp in epoch seconds | [optional] [default to null]
**type** | [**ServiceLevelObjectiveType**][6] |  | [optional] [default to null]
**typeUnderscoreid** | [**ServiceLevelObjectiveTypeNumeric**][7] |  | [optional] [default to null]

[[Back to Model list]][8] [[Back to API list]][9] [[Back to README]][10]

[1]: long.md
[2]: HistoryServiceLevelObjectiveGroups.md
[3]: HistoryServiceLevelObjectiveOverall.md
[4]: HistoryServiceLevelObjectiveMetrics.md
[5]: SLOThreshold.md
[6]: ServiceLevelObjectiveType.md
[7]: ServiceLevelObjectiveTypeNumeric.md
[8]: ../README.md#documentation-for-models
[9]: ../README.md#documentation-for-api-endpoints
[10]: ../README.md
