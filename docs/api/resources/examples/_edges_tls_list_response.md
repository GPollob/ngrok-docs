<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-28T10:19:32Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tfL2BLPovJldmlKDqkWNxeDXuc",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tfL2BLPovJldmlKDqkWNxeDXuc"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tfL0pUT6nyOqXQCbYMschE7u4V",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tfL0pUT6nyOqXQCbYMschE7u4V"
				},
				"enabled": true
			},
			"created_at": "2025-02-28T10:19:21Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tfL0qVXB0q5zSdam9rgB75EMSV",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tfL0qVXB0q5zSdam9rgB75EMSV"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
