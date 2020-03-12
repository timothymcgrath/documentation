# ./Models.TableWidgetRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**aggregator** | [**WidgetAggregator**][1] |  | [optional] [default to null]
**alias** | [**String**][2] | The column name (defaults to the metric name) | [optional] [default to null]
**apmUnderscorequery** | [**LogQueryDefinition**][3] |  | [optional] [default to null]
**conditionalUnderscoreformats** | [**List**][4] |  | [optional] [default to null]
**eventUnderscorequery** | [**EventQueryDefinition**][5] |  | [optional] [default to null]
**limit** | [**Long**][6] | For metric queries, the number of lines to show in the table. Only one request should have this property. | [optional] [default to null]
**logUnderscorequery** | [**LogQueryDefinition**][3] |  | [optional] [default to null]
**networkUnderscorequery** | [**LogQueryDefinition**][3] |  | [optional] [default to null]
**order** | [**WidgetSort**][7] |  | [optional] [default to null]
**processUnderscorequery** | [**ProcessQueryDefinition**][8] |  | [optional] [default to null]
**q** | [**String**][2] |  | [optional] [default to null]
**rumUnderscorequery** | [**LogQueryDefinition**][3] |  | [optional] [default to null]

[[Back to Model list]][9] [[Back to API list]][10] [[Back to README]][11]

[1]: WidgetAggregator.md
[2]: string.md
[3]: LogQueryDefinition.md
[4]: WidgetConditionalFormat.md
[5]: EventQueryDefinition.md
[6]: long.md
[7]: WidgetSort.md
[8]: ProcessQueryDefinition.md
[9]: ../README.md#documentation-for-models
[10]: ../README.md#documentation-for-api-endpoints
[11]: ../README.md
