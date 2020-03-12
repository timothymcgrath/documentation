# ./Models.HostMuteSettings
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**end** | [**Long**][1] | POSIX timestamp in seconds when the host is unmuted. If omitted, the host remains muted until explicitly unmuted. | [optional] [default to null]
**message** | [**String**][2] | Message to associate with the muting of this host. | [optional] [default to null]
**override** | [**Boolean**][3] | If true and the host is already muted, replaces existing host mute settings. | [optional] [default to null]

[[Back to Model list]][4] [[Back to API list]][5] [[Back to README]][6]

[1]: long.md
[2]: string.md
[3]: boolean.md
[4]: ../README.md#documentation-for-models
[5]: ../README.md#documentation-for-api-endpoints
[6]: ../README.md
