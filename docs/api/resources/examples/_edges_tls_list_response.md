<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-01T10:07:28Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2wURDm6zlFt77bLv00qxcuxafuc",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wURDm6zlFt77bLv00qxcuxafuc"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2wURCOedG7jGMA9TmMceqyncTdn",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2wURCOedG7jGMA9TmMceqyncTdn"
        },
        "enabled": true
      },
      "created_at": "2025-05-01T10:07:17Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2wURCR5g4djML8W0zJXSnHGm63f",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wURCR5g4djML8W0zJXSnHGm63f"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
