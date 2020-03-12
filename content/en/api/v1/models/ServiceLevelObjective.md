# ./Models.ServiceLevelObjective
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**createdUnderscoreat** | [**Long**][1] | Creation timestamp (unix time in seconds) Always included in service level objective responses. | [optional] [default to null]
**creator** | [**Creator**][2] |  | [optional] [default to null]
**description** | [**String**][3] | A user-defined description of the service level objective. Always included in service level objective responses (but may be null). Optional in create/update requests. | [optional] [default to null]
**groups** | [**List**][3] | A list of (up to 20) monitor groups (e.g. [\&quot;env:prod,role:mysql\&quot;]) that narrows the scope of a monitor service level objective. Included in service level objective responses if it is nonempty. Optional in create/update requests for monitor service level objectives, but may only be used when then length of the \&quot;monitor_ids\&quot; field is one. | [optional] [default to null]
**id** | [**String**][3] | A unique identifier for the service level objective object. Always included in service level objective responses. Required for update requests. | [optional] [default to null]
**modifiedUnderscoreat** | [**Long**][1] | Modification timestamp (unix time in seconds) Always included in service level objective responses. | [optional] [default to null]
**monitorUnderscoreids** | [**List**][1] | A list of monitor ids that defines the scope of a monitor service level objective. Required if type is \&quot;monitor\&quot;. | [optional] [default to null]
**monitorUnderscoretags** | [**List**][3] | The union of monitor tags for all monitors referenced by the \&quot;monitor_ids\&quot; field. Always included in service level objective responses for monitor service level objectives (but may be empty). Ignored in create/update requests. Does not affect which monitors are included in the service level objective (that is determined entirely by the monitor_ids field). | [optional] [default to null]
**name** | [**String**][3] | The name of the service level objective object. | [default to null]
**query** | [**ServiceLevelObjective_query**][4] |  | [optional] [default to null]
**tags** | [**List**][3] | A list of tags (e.g. \&quot;env:prod\&quot;) associated with this service level objective. Always included in service level objective responses (but may be empty). Optional in create/update requests. | [optional] [default to null]
**thresholds** | [**List**][5] | The thresholds (timeframes and associated targets) for this service level objective object. | [default to null]
**type** | [**ServiceLevelObjectiveType**][6] |  | [default to null]
**typeUnderscoreid** | [**ServiceLevelObjectiveTypeNumeric**][7] |  | [optional] [default to null]

[[Back to Model list]][8] [[Back to API list]][9] [[Back to README]][10]

[1]: long.md
[2]: Creator.md
[3]: string.md
[4]: ServiceLevelObjective_query.md
[5]: SLOThreshold.md
[6]: ServiceLevelObjectiveType.md
[7]: ServiceLevelObjectiveTypeNumeric.md
[8]: ../README.md#documentation-for-models
[9]: ../README.md#documentation-for-api-endpoints
[10]: ../README.md
