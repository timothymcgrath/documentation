# ./Models.UsageHostHour
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agentUnderscorehostUnderscorecount** | [**Long**][1] | Contains the total number of infrastructure hosts reporting during a given hour that were running the Datadog Agent. | [optional] [default to null]
**apmUnderscorehostUnderscorecount** | [**Long**][1] | Shows the total number of hosts using APM during the hour, these are counted as billable (except during trial periods). | [optional] [default to null]
**awsUnderscorehostUnderscorecount** | [**Long**][1] | Contains the total number of hosts that reported via the AWS integration (and were NOT running the Datadog Agent). When AWS or GCP hosts are also running the Datadog Agent, they are counted as Agent hosts, NOT as AWS or GCP. | [optional] [default to null]
**containerUnderscorecount** | [**Long**][1] | Contains the total number of billable infrastructure hosts reporting during a given hour. This is the sum of &#x60;agent_host_count&#x60;, &#x60;aws_host_count&#x60;, and &#x60;gcp_host_count&#x60;. | [optional] [default to null]
**gcpUnderscorehostUnderscorecount** | [**Long**][1] | Contains the total number of hosts that reported via the Google Cloud integration (and were NOT running the Datadog Agent). | [optional] [default to null]
**hostUnderscorecount** | [**Long**][1] | Shows the total number of containers reporting via the Docker integration during the hour. | [optional] [default to null]
**hour** | [**Date**][2] | The hour for the usage. | [optional] [default to null]

[[Back to Model list]][3] [[Back to API list]][4] [[Back to README]][5]

[1]: long.md
[2]: DateTime.md
[3]: ../README.md#documentation-for-models
[4]: ../README.md#documentation-for-api-endpoints
[5]: ../README.md
