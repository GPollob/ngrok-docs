<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-28T10:19:26Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tfL0rKOIC0FHEGZUnnSn0pGDfV",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tfL0rKOIC0FHEGZUnnSn0pGDfV"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tfL1VDxXC84duPRQEfHLAO7tuH",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-28T10:19:26Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tfL1VDxXC84duPRQEfHLAO7tuH",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-28T10:19:25Z",
			"hostport": "e99ff50e7f92.ngrok.paid:443",
			"id": "ep_2tfL1MgWYQh1ckDvUMPqnE2REXe",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tfKydwBIYFWzKDbJhzZuVWKEYF",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://e99ff50e7f92.ngrok.paid",
			"tunnel": {
				"id": "tn_2tfL1MgWYQh1ckDvUMPqnE2REXe",
				"uri": "https://api.ngrok.com/tunnels/tn_2tfL1MgWYQh1ckDvUMPqnE2REXe"
			},
			"tunnel_session": {
				"id": "ts_2tfL1NUgwrGefshqJcKy2dyN4fl",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tfL1NUgwrGefshqJcKy2dyN4fl"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-28T10:19:25Z",
			"upstream_url": "http://localhost:80",
			"url": "https://e99ff50e7f92.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-28T10:19:22Z",
			"domain": {
				"id": "rd_2tfL0rKOIC0FHEGZUnnSn0pGDfV",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tfL0rKOIC0FHEGZUnnSn0pGDfV"
			},
			"edge": {
				"id": "edgtls_2tfL0qVXB0q5zSdam9rgB75EMSV",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tfL0qVXB0q5zSdam9rgB75EMSV"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tfL0piZHpGUjoPejhvIOFTdkXM",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-28T10:19:22Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
