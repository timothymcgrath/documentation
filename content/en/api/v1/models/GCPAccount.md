# ./Models.GCPAccount
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**authUnderscoreproviderUnderscorex509UnderscorecertUnderscoreurl** | [**String**][1] | Should be https://www.googleapis.com/oauth2/v1/certs. | [optional] [default to null]
**authUnderscoreuri** | [**String**][1] | Should be https://accounts.google.com/o/oauth2/auth. | [optional] [default to null]
**automute** | [**Boolean**][2] | Silence monitors for expected GCE instance shutdowns. | [optional] [default to null]
**clientUnderscoreemail** | [**String**][1] | Your email found in your JSON service account key. | [optional] [default to null]
**clientUnderscoreid** | [**String**][1] | Your ID found in your JSON service account key. | [optional] [default to null]
**clientUnderscorex509UnderscorecertUnderscoreurl** | [**String**][1] | Should be https://www.googleapis.com/robot/v1/metadata/x509/&lt;CLIENT_EMAIL&gt; where &lt;CLIENT_EMAIL&gt; is the email found in your JSON service account key. | [optional] [default to null]
**errors** | [**List**][1] |  | [optional] [default to null]
**hostUnderscorefilters** | [**String**][1] | Limit the GCE instances that are pulled into Datadog by using tags. Only hosts that match one of the defined tags are imported into Datadog. | [optional] [default to null]
**privateUnderscorekey** | [**String**][1] | Your private key name found in your JSON service account key. | [optional] [default to null]
**privateUnderscorekeyUnderscoreid** | [**String**][1] | Your private key ID found in your JSON service account key. | [optional] [default to null]
**projectUnderscoreid** | [**String**][1] | Your Google Cloud project ID found in your JSON service account key. | [optional] [default to null]
**tokenUnderscoreuri** | [**String**][1] | Should be https://accounts.google.com/o/oauth2/token. | [optional] [default to null]
**type** | [**String**][1] | The value for service_account found in your JSON service account key. | [optional] [default to null]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: string.md
[2]: boolean.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
