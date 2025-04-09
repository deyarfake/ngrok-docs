<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-04-09T10:07:24Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.ktfqt863khupnchd.local-ngrok-cname.com",
			"created_at": "2025-04-09T10:07:24Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2vUIUsbtOr4xlDA2rXjU47i8Ut1",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2vUIUsbtOr4xlDA2rXjU47i8Ut1"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2vUIUvzfEWEq9IzyekJMsx3XHu6",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2vUIUvzfEWEq9IzyekJMsx3XHu6"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.ktfqt863khupnchd.local-ngrok-cname.com",
			"created_at": "2025-04-09T10:07:24Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2vUIUreSpLJgGse99ZX71QQIh1J",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2vUIUreSpLJgGse99ZX71QQIh1J"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
