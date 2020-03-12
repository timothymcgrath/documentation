# ./Models.SLOThreshold
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target** | [**Double**][1] | The target value for the service level indicator within the corresponding timeframe. | [default to null]
**targetUnderscoredisplay** | [**String**][2] | A string representation of the target that indicates its precision (e.g. \&quot;99.9\&quot;). It uses trailing zeros to show significant decimal places (e.g. \&quot;98.00\&quot;). Always included in service level objective responses. Ignored in create/update requests. | [optional] [default to null]
**timeframe** | [**SLOTimeframe**][3] |  | [default to null]
**warning** | [**Double**][1] |  | [optional] [default to null]
**warningUnderscoredisplay** | [**String**][2] | A string representation of the warning target (see the description of the \&quot;target_display\&quot; field for details). Included in service level objective responses if a warning target exists. Ignored in create/update requests. | [optional] [default to null]

[[Back to Model list]][4] [[Back to API list]][5] [[Back to README]][6]

[1]: double.md
[2]: string.md
[3]: SLOTimeframe.md
[4]: ../README.md#documentation-for-models
[5]: ../README.md#documentation-for-api-endpoints
[6]: ../README.md
