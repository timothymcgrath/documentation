# ./Models.UsageSummaryDateOrg
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agentUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all agent hosts over all hours in the current date for the given org. | [optional] [default to null]
**apmUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all distinct APM hosts over all hours in the current date for the given org. | [optional] [default to null]
**awsUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all AWS hosts over all hours in the current date for the given org. | [optional] [default to null]
**awsUnderscorelambdaUnderscorefuncUnderscorecount** | [**Long**][1] | Shows the sum of all AWS Labmda invocations over all hours in the current date for the given org. | [optional] [default to null]
**awsUnderscorelambdaUnderscoreinvocationsUnderscoresum** | [**Long**][1] | Shows the sum of all AWS Labmda invocations over all hours in the current date for the given org. | [optional] [default to null]
**billableUnderscoreingestedUnderscorebytesUnderscoresum** | [**Long**][1] | Shows the sum of all log bytes ingested over all hours in the current date for the given org. | [optional] [default to null]
**containerUnderscoreavg** | [**Long**][1] | Shows the average of all distinct containers over all hours in the current date for the given org. | [optional] [default to null]
**containerUnderscorehwm** | [**Long**][1] | Shows the high watermark of all distinct containers over all hours in the current date for the given org. | [optional] [default to null]
**customUnderscoretsUnderscoreavg** | [**Long**][1] | Shows the average number of distinct custom metrics over all hours in the current date for the given org. | [optional] [default to null]
**fargateUnderscoretasksUnderscorecountUnderscoreavg** | [**Long**][1] |  | [optional] [default to null]
**fargateUnderscoretasksUnderscorecountUnderscorehwm** | [**Long**][1] | Shows the high watermark of all Fargate tasks over all hours in the current date for the given org. | [optional] [default to null]
**gcpUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all GCP hosts over all hours in the current date for the given org. | [optional] [default to null]
**id** | [**String**][2] | The organization id. | [optional] [default to null]
**indexedUnderscoreeventsUnderscorecountUnderscoresum** | [**Long**][1] | Shows the sum of all log events indexed over all hours in the current date for the given org. | [optional] [default to null]
**infraUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all distinct infrastructure hosts over all hours in the current date for the given org. | [optional] [default to null]
**ingestedUnderscoreeventsUnderscorebytesUnderscoresum** | [**Long**][1] | Shows the sum of all log bytes ingested over all hours in the current date for the given org. | [optional] [default to null]
**name** | [**String**][2] | The organization name. | [optional] [default to null]
**netflowUnderscoreindexedUnderscoreeventsUnderscorecountUnderscoresum** | [**Long**][1] | Shows the sum of all Network flows indexed over all hours in the current date for the given org. | [optional] [default to null]
**npmUnderscorehostUnderscoretop99p** | [**Long**][1] | Shows the 99th percentile of all distinct Networks hosts over all hours in the current date for the given org. | [optional] [default to null]
**publicUnderscoreid** | [**String**][2] | The organization public id. | [optional] [default to null]
**syntheticsUnderscorebrowserUnderscorecheckUnderscorecallsUnderscorecountUnderscoresum** | [**Long**][1] | Shows the sum of all Synthetic browser tests over all hours in the current date for the given org. | [optional] [default to null]
**syntheticsUnderscorecheckUnderscorecallsUnderscorecountUnderscoresum** | [**Long**][1] | Shows the sum of all Synthetic API tests over all hours in the current date for the given org. | [optional] [default to null]
**traceUnderscoresearchUnderscoreindexedUnderscoreeventsUnderscorecountUnderscoresum** | [**Long**][1] | Shows the sum of all analyzed spans indexed over all hours in the current date for the given org. | [optional] [default to null]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: long.md
[2]: string.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
