<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-04-09T10:07:45Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2vUIWubr0f84tixJyiUmKAm1UBX",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vUIWubr0f84tixJyiUmKAm1UBX"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vUIXTcaDT8cwlOGTq4HjnhapTI",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-04-09T10:07:45Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2vUIXTcaDT8cwlOGTq4HjnhapTI",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-09T10:07:43Z",
			"hostport": "2781c8b021cf.ngrok.paid:443",
			"id": "ep_2vUIXE4jUa5yZhZAsPf244IRxG7",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2vUIUqEgjFpBnB6waOSrrluz9ib",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://2781c8b021cf.ngrok.paid",
			"tunnel": {
				"id": "tn_2vUIXE4jUa5yZhZAsPf244IRxG7",
				"uri": "https://api.ngrok.com/tunnels/tn_2vUIXE4jUa5yZhZAsPf244IRxG7"
			},
			"tunnel_session": {
				"id": "ts_2vUIXF0qSuSAOgDtAD0p8l3U88F",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2vUIXF0qSuSAOgDtAD0p8l3U88F"
			},
			"type": "ephemeral",
			"updated_at": "2025-04-09T10:07:43Z",
			"upstream_url": "http://localhost:80",
			"url": "https://2781c8b021cf.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-09T10:07:41Z",
			"domain": {
				"id": "rd_2vUIWubr0f84tixJyiUmKAm1UBX",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vUIWubr0f84tixJyiUmKAm1UBX"
			},
			"edge": {
				"id": "edgtls_2vUIWvPibGnbW5kgZIKPXKAIs2Y",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2vUIWvPibGnbW5kgZIKPXKAIs2Y"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vUIWvI61ROCfOJyLoV80tUWlLs",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-04-09T10:07:41Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
