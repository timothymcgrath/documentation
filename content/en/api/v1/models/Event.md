# ./Models.Event
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**aggregationUnderscorekey** | [**String**][1] | An arbitrary string to use for aggregation. Limited to 100 characters. If you specify a key, all events using that key are grouped together in the Event Stream. | [optional] [default to null]
**alertUnderscoretype** | [**EventAlertType**][2] |  | [optional] [default to null]
**dateUnderscorehappened** | [**Long**][3] | POSIX timestamp of the event. Must be sent as an integer (i.e. no quotes). Limited to events no older than 1 year, 24 days (389 days) | [optional] [default to null]
**deviceUnderscorename** | [**List**][1] | A list of device names to post the event with. | [optional] [default to null]
**host** | [**String**][1] | Host name to associate with the event. Any tags associated with the host are also applied to this event. | [optional] [default to null]
**id** | [**Long**][3] |  | [optional] [default to null]
**payload** | [**String**][1] |  | [optional] [default to null]
**priority** | [**EventPriority**][4] |  | [optional] [default to null]
**relatedUnderscoreeventUnderscoreid** | [**Long**][3] | ID of the parent event. Must be sent as an integer (i.e. no quotes). | [optional] [default to null]
**sourceUnderscoretypeUnderscorename** | [**String**][1] | The type of event being posted. Options: nagios, hudson, jenkins, my_apps, chef, puppet, git, bitbucket, ... [Complete list of source attribute values][5] | [optional] [default to null]
**tags** | [**List**][1] | A list of tags to apply to the event. | [optional] [default to null]
**text** | [**String**][1] | The body of the event. Limited to 4000 characters. The text supports markdown. Use msg_text with the Datadog Ruby library | [default to null]
**title** | [**String**][1] | The event title. Limited to 100 characters. Use msg_title with the Datadog Ruby library. | [default to null]
**url** | [**String**][1] |  | [optional] [default to null]

[[Back to Model list]][6] [[Back to API list]][7] [[Back to README]][8]

[1]: string.md
[2]: EventAlertType.md
[3]: long.md
[4]: EventPriority.md
[5]: https://docs.datadoghq.com/integrations/faq/list-of-api-source-attribute-value
[6]: ../README.md#documentation-for-models
[7]: ../README.md#documentation-for-api-endpoints
[8]: ../README.md
