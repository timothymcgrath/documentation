# ./Models.Dashboard
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**authorUnderscorehandle** | [**String**][1] |  | [optional] [default to null]
**createdUnderscoreat** | [**Date**][2] |  | [optional] [default to null]
**description** | [**String**][1] | Description of the dashboard | [optional] [default to null]
**id** | [**String**][1] | ID of the dashboard | [optional] [default to null]
**isUnderscorereadUnderscoreonly** | [**Boolean**][3] | Whether this dashboard is read-only. If True, only the author and admins can make changes to it. | [optional] [default to false]
**layoutUnderscoretype** | [**DashboardLayoutType**][4] |  | [default to null]
**modifiedUnderscoreat** | [**Date**][2] |  | [optional] [default to null]
**notifyUnderscorelist** | [**List**][1] | List of handles of users to notify when changes are made to this dashboard. | [optional] [default to null]
**templateUnderscorevariableUnderscorepresets** | [**List**][5] |  | [optional] [default to null]
**templateUnderscorevariables** | [**List**][6] |  | [optional] [default to null]
**title** | [**String**][1] | Title of the dashboard | [default to null]
**url** | [**String**][1] |  | [optional] [default to null]
**widgets** | [**List**][7] | List of widgets to display on the dashboard | [default to null]

[[Back to Model list]][8] [[Back to API list]][9] [[Back to README]][10]

[1]: string.md
[2]: DateTime.md
[3]: boolean.md
[4]: DashboardLayoutType.md
[5]: DashboardTemplateVariablePreset.md
[6]: Dashboard_template_variables.md
[7]: Widget.md
[8]: ../README.md#documentation-for-models
[9]: ../README.md#documentation-for-api-endpoints
[10]: ../README.md
