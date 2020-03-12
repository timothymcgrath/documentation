# ./Models.LogsIndex
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dailyUnderscorelimit** | [**Long**][1] | The number of log-events you can send in this index per day before you are rate-limited. | [optional] [default to null]
**exclusionUnderscorefilters** | [**List**][2] | An array of exclusion objects. The logs are tested against the query of each filter, following the order of the array. Only the first matching active exclusion matters, others (if any) are ignored. | [optional] [default to null]
**filter** | [**LogsFilter**][3] |  | [default to null]
**isUnderscorerateUnderscorelimited** | [**Boolean**][4] | A boolean stating if the index is rate limited, meaning more logs than the daily limit have been sent. Rate limit is reset every-day at 2pm UTC. | [optional] [default to null]
**name** | [**String**][5] | The name of the index. | [optional] [default to null]
**numUnderscoreretentionUnderscoredays** | [**Long**][1] | The number of days before logs are deleted from this index | [optional] [default to null]

[[Back to Model list]][6] [[Back to API list]][7] [[Back to README]][8]

[1]: long.md
[2]: LogsExclusion.md
[3]: LogsFilter.md
[4]: boolean.md
[5]: string.md
[6]: ../README.md#documentation-for-models
[7]: ../README.md#documentation-for-api-endpoints
[8]: ../README.md
