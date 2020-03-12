# ./Models.UsageSummaryResponse
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agentUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all agent hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**apmUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all distinct APM hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**awsUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all AWS hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**awsUnderscorelambdaUnderscorefuncUnderscorecount** | [**Long**][1] | Shows the average of the number of functions that executed 1 or more times each hour in the current month(s) for all orgs. | [optional] [default to null]
**awsUnderscorelambdaUnderscoreinvocationsUnderscoresum** | [**Long**][1] | Shows the sum of all AWS Labmda invocations over all hours in the current month(s) for all orgs. | [optional] [default to null]
**azureUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all Azure hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**billableUnderscoreingestedUnderscorebytesUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all log bytes ingested over all hours in the current month(s) for all orgs. | [optional] [default to null]
**containerUnderscoreavgUnderscoresum** | [**Long**][1] | Shows the average of all distinct containers over all hours in the current month(s) for all orgs. | [optional] [default to null]
**containerUnderscorehwmUnderscoresum** | [**Long**][1] | Shows the high watermark of all distinct containers over all hours in the current month(s) for all orgs. | [optional] [default to null]
**customUnderscoretsUnderscoresum** | [**Long**][1] | Shows the average number of distinct custom metrics over all hours in the current month(s) for all orgs. | [optional] [default to null]
**endUnderscoredate** | [**date**][2] | Shows the last date of usage in the current month(s) for all orgs. | [optional] [default to null]
**fargateUnderscoretasksUnderscorecountUnderscoreavgUnderscoresum** | [**Long**][1] | Shows the average of all Fargate tasks over all hours in the current month(s) for all orgs. | [optional] [default to null]
**fargateUnderscoretasksUnderscorecountUnderscorehwmUnderscoresum** | [**Long**][1] | Shows the high watermark of all Fargate tasks over all hours in the current month(s) for all orgs. | [optional] [default to null]
**gcpUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all GCP hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**indexedUnderscoreeventsUnderscorecountUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all log events indexed over all hours in the current month(s) for all orgs. | [optional] [default to null]
**infraUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all distinct infrastructure hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**ingestedUnderscoreeventsUnderscorebytesUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all log bytes ingested over all hours in the current month(s) for all orgs. | [optional] [default to null]
**lastUnderscoreupdated** | [**Date**][3] | Shows the the most recent hour in the current month(s) for all orgs for which all usages were calculated. | [optional] [default to null]
**netflowUnderscoreindexedUnderscoreeventsUnderscorecountUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all Network flows indexed over all hours in the current month(s) for all orgs. | [optional] [default to null]
**npmUnderscorehostUnderscoretop99pUnderscoresum** | [**Long**][1] | Shows the 99th percentile of all distinct Networks hosts over all hours in the current month(s) for all orgs. | [optional] [default to null]
**startUnderscoredate** | [**date**][2] | Shows the first date of usage in the current month(s) for all orgs. | [optional] [default to null]
**syntheticsUnderscorebrowserUnderscorecheckUnderscorecallsUnderscorecountUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all Synthetic browser tests over all hours in the current month(s) for all orgs. | [optional] [default to null]
**syntheticsUnderscorecheckUnderscorecallsUnderscorecountUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all Synthetic API tests over all hours in the current month(s) for all orgs. | [optional] [default to null]
**traceUnderscoresearchUnderscoreindexedUnderscoreeventsUnderscorecountUnderscoreaggUnderscoresum** | [**Long**][1] | Shows the sum of all analyzed spans indexed over all hours in the current month(s) for all orgs. | [optional] [default to null]
**usage** | [**List**][4] |  | [optional] [default to null]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: long.md
[2]: date.md
[3]: DateTime.md
[4]: UsageSummaryDate.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
