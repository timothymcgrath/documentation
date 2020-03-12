# ./Models.CheckStatusWidgetDefinition
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**check** | [**String**][1] | Name of the check to use in the widget | [default to null]
**group** | [**String**][1] | Group reporting a single check | [optional] [default to null]
**groupUnderscoreby** | [**List**][1] | List of tag prefixes to group by in the case of a cluster check | [optional] [default to null]
**grouping** | [**WidgetGrouping**][2] |  | [default to null]
**tags** | [**List**][1] | List of tags used to filter the groups reporting a cluster check | [optional] [default to null]
**time** | [**WidgetTime**][3] |  | [optional] [default to null]
**title** | [**String**][1] | Title of the widget | [optional] [default to null]
**titleUnderscorealign** | [**WidgetTextAlign**][4] |  | [optional] [default to null]
**titleUnderscoresize** | [**String**][1] | Size of the title | [optional] [default to null]
**type** | [**String**][1] | Type of the widget | [default to check_status]

[[Back to Model list]][5] [[Back to API list]][6] [[Back to README]][7]

[1]: string.md
[2]: WidgetGrouping.md
[3]: WidgetTime.md
[4]: WidgetTextAlign.md
[5]: ../README.md#documentation-for-models
[6]: ../README.md#documentation-for-api-endpoints
[7]: ../README.md
