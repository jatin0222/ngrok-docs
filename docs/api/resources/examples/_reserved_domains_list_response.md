<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2wURAMn8shA1fLJ3F7P7tKCOD4E",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2wURAMn8shA1fLJ3F7P7tKCOD4E"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5mdv3rjv4cbfaemwr.local-ngrok-cname.com",
      "created_at": "2025-05-01T10:07:01Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wURAYjRK1VJqRs4qPjNqIn2zMi",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wURAYjRK1VJqRs4qPjNqIn2zMi"
    },
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
          "started_at": "2025-05-01T10:07:02Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5mdv3rjv4cbfaemwr.local-ngrok-cname.com",
      "created_at": "2025-05-01T10:07:02Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wURAY3ASXtZwsTGxd9IG0Egk2v",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wURAY3ASXtZwsTGxd9IG0Egk2v"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
