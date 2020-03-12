# ./Models.WidgetDefinition
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alertUnderscoreid** | [**String**][1] | ID of the alert to use in the widget | [default to null]
**time** | [**WidgetTime**][2] |  | [optional] [default to null]
**title** | [**String**][1] | Title of your widget. | [optional] [default to null]
**titleUnderscorealign** | [**WidgetTextAlign**][3] |  | [optional] [default to null]
**titleUnderscoresize** | [**String**][1] | Size of the title | [optional] [default to null]
**type** | [**String**][1] | Type of the widget | [default to toplist]
**vizUnderscoretype** | [**WidgetVizType**][4] |  | [default to null]
**precision** | [**Long**][5] | Number of decimals to show. If not defined, the widget uses the raw value. | [optional] [default to null]
**textUnderscorealign** | [**WidgetTextAlign**][3] |  | [optional] [default to null]
**unit** | [**String**][1] | Unit to display with the value | [optional] [default to null]
**requests** | [**List**][6] |  | [default to null]
**check** | [**String**][1] | Name of the check to use in the widget | [default to null]
**group** | [**List**][1] | List of tag prefixes to group by. | [optional] [default to null]
**groupUnderscoreby** | [**List**][1] | List of tag prefixes to group by in the case of a cluster check | [optional] [default to null]
**grouping** | [**WidgetGrouping**][7] |  | [default to null]
**tags** | [**List**][1] | List of tags used to filter the groups reporting a cluster check | [optional] [default to null]
**legendUnderscoresize** | [**WidgetLegendSize**][8] |  | [optional] [default to null]
**showUnderscorelegend** | [**Boolean**][9] | (screenboard only) Show the legend for this widget | [optional] [default to null]
**eventUnderscoresize** | [**WidgetEventSize**][10] |  | [optional] [default to null]
**query** | [**String**][1] | Query to filter the monitors with | [default to null]
**tagsUnderscoreexecution** | [**String**][1] | The execution method for multi-value filters. Can be either and or or | [optional] [default to null]
**color** | [**String**][1] | Color of the text | [optional] [default to null]
**fontUnderscoresize** | [**String**][1] | Size of the text | [optional] [default to null]
**text** | [**String**][1] | Text to display | [default to null]
**layoutUnderscoretype** | [**WidgetLayoutType**][11] |  | [default to null]
**widgets** | [**List**][12] |  | [default to null]
**events** | [**List**][13] |  | [optional] [default to null]
**yaxis** | [**WidgetAxis**][14] |  | [optional] [default to null]
**noUnderscoregroupUnderscorehosts** | [**Boolean**][9] | Whether to show the hosts that don’t fit in a group. | [optional] [default to null]
**noUnderscoremetricUnderscorehosts** | [**Boolean**][9] | Whether to show the hosts with no metrics. | [optional] [default to null]
**nodeUnderscoretype** | [**WidgetNodeType**][15] |  | [optional] [default to null]
**notes** | [**String**][1] |  | [optional] [default to null]
**scope** | [**List**][1] | List of tags used to filter the map. | [optional] [default to null]
**style** | [**HostMapWidgetDefinition_style**][16] |  | [optional] [default to null]
**url** | [**String**][1] | URL of the image | [default to null]
**margin** | [**WidgetMargin**][17] |  | [optional] [default to null]
**sizing** | [**WidgetImageSizing**][18] |  | [optional] [default to null]
**columns** | [**List**][1] | Which columns to display on the widget | [optional] [default to null]
**indexes** | [**List**][1] | An array of index names to query in the stream. | [optional] [default to null]
**colorUnderscorepreference** | [**WidgetColorPreference**][19] |  | [optional] [default to null]
**displayUnderscoreformat** | [**WidgetServiceSummaryDisplayFormat**][20] |  | [optional] [default to null]
**hideUnderscorezeroUnderscorecounts** | [**Boolean**][9] | Whether to show counts of 0 or not | [optional] [default to null]
**showUnderscorelastUnderscoretriggered** | [**Boolean**][9] | Whether to show the time that has elapsed since the monitor/group triggered | [optional] [default to null]
**sort** | [**WidgetSort**][21] |  | [optional] [default to null]
**summaryUnderscoretype** | [**WidgetSummaryType**][22] |  | [optional] [default to null]
**backgroundUnderscorecolor** | [**String**][1] | Background color of the note | [optional] [default to null]
**content** | [**String**][1] | Content of the note | [default to null]
**showUnderscoretick** | [**Boolean**][9] | Whether to show a tick or not | [optional] [default to null]
**tickUnderscoreedge** | [**WidgetTickEdge**][23] |  | [optional] [default to null]
**tickUnderscorepos** | [**String**][1] | Where to position the tick on an edge | [optional] [default to null]
**autoscale** | [**Boolean**][9] | Whether to use autoscaling or not. | [optional] [default to null]
**customUnderscoreunit** | [**String**][1] | Display a unit of your choice on the widget. | [optional] [default to null]
**colorUnderscorebyUnderscoregroups** | [**List**][1] | List of groups used for colors. | [optional] [default to null]
**xaxis** | [**WidgetAxis**][14] |  | [optional] [default to null]
**showUnderscoreerrorUnderscorebudget** | [**Boolean**][9] |  | [optional] [default to null]
**sloUnderscoreid** | [**String**][1] |  | [optional] [default to null]
**timeUnderscorewindows** | [**List**][24] |  | [optional] [default to null]
**viewUnderscoremode** | [**WidgetViewMode**][25] |  | [optional] [default to null]
**viewUnderscoretype** | [**String**][1] |  | [default to detail]
**filters** | [**List**][1] | Your env and primary tag (or * if enabled for your account). | [default to null]
**service** | [**String**][1] | APM service | [default to null]
**env** | [**String**][1] | APM environment | [default to null]
**showUnderscorebreakdown** | [**Boolean**][9] | Whether to show the latency breakdown or not | [optional] [default to null]
**showUnderscoredistribution** | [**Boolean**][9] | Whether to show the latency distribution or not | [optional] [default to null]
**showUnderscoreerrors** | [**Boolean**][9] | Whether to show the error metrics or not | [optional] [default to null]
**showUnderscorehits** | [**Boolean**][9] | Whether to show the hits metrics or not | [optional] [default to null]
**showUnderscorelatency** | [**Boolean**][9] | Whether to show the latency metrics or not | [optional] [default to null]
**showUnderscoreresourceUnderscorelist** | [**Boolean**][9] | Whether to show the resource list or not | [optional] [default to null]
**sizeUnderscoreformat** | [**WidgetSizeFormat**][26] |  | [optional] [default to null]
**spanUnderscorename** | [**String**][1] | APM span name | [default to null]
**markers** | [**List**][27] |  | [optional] [default to null]

[[Back to Model list]][28] [[Back to API list]][29] [[Back to README]][30]

[1]: string.md
[2]: WidgetTime.md
[3]: WidgetTextAlign.md
[4]: WidgetVizType.md
[5]: long.md
[6]: ToplistWidgetRequest.md
[7]: WidgetGrouping.md
[8]: WidgetLegendSize.md
[9]: boolean.md
[10]: WidgetEventSize.md
[11]: WidgetLayoutType.md
[12]: Widget.md
[13]: WidgetEvent.md
[14]: WidgetAxis.md
[15]: WidgetNodeType.md
[16]: HostMapWidgetDefinition_style.md
[17]: WidgetMargin.md
[18]: WidgetImageSizing.md
[19]: WidgetColorPreference.md
[20]: WidgetServiceSummaryDisplayFormat.md
[21]: WidgetSort.md
[22]: WidgetSummaryType.md
[23]: WidgetTickEdge.md
[24]: WidgetTimeWindows.md
[25]: WidgetViewMode.md
[26]: WidgetSizeFormat.md
[27]: WidgetMarker.md
[28]: ../README.md#documentation-for-models
[29]: ../README.md#documentation-for-api-endpoints
[30]: ../README.md
