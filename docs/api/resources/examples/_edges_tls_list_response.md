<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-04-09T10:07:50Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2vUIYA4evBzb9ORqwXGEZMBj5Aw",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vUIYA4evBzb9ORqwXGEZMBj5Aw"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2vUIWsmWeCNl1AB3RvsCMscidNL",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vUIWsmWeCNl1AB3RvsCMscidNL"
				},
				"enabled": true
			},
			"created_at": "2025-04-09T10:07:40Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2vUIWvPibGnbW5kgZIKPXKAIs2Y",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vUIWvPibGnbW5kgZIKPXKAIs2Y"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
