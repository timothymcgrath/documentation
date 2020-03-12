# ./Models.LogsGeoIPParser
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sources** | [**List**][1] | Array of source attributes | [default to ["network.client.ip"]]
**target** | [**String**][1] | Name of the parent attribute that contains all the extracted details from the &#x60;sources&#x60; | [default to network.client.geoip]
**type** | [**String**][1] | Type of processor | [optional] [default to geo-ip-parser]

[[Back to Model list]][2] [[Back to API list]][3] [[Back to README]][4]

[1]: string.md
[2]: ../README.md#documentation-for-models
[3]: ../README.md#documentation-for-api-endpoints
[4]: ../README.md
