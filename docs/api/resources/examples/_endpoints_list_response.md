<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-01T10:07:22Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2wURCSO84s1xv9Y0Bu04cQNtciU",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wURCSO84s1xv9Y0Bu04cQNtciU"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wURD0e2VWpAHAgqZjyaIF3QTuV",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-01T10:07:22Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2wURD0e2VWpAHAgqZjyaIF3QTuV",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-01T10:07:20Z",
      "hostport": "47f79e58f8db.ngrok.paid:443",
      "id": "ep_2wURCnr52nk99mDcyeO362mdCf7",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2wURAPFQxRZDYk38OaeZ4ARdoUv",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://47f79e58f8db.ngrok.paid",
      "tunnel": {
        "id": "tn_2wURCnr52nk99mDcyeO362mdCf7",
        "uri": "https://api.ngrok.com/tunnels/tn_2wURCnr52nk99mDcyeO362mdCf7"
      },
      "tunnel_session": {
        "id": "ts_2wURCoLRhVTMhgMYGIh2d0MK7jL",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2wURCoLRhVTMhgMYGIh2d0MK7jL"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-01T10:07:20Z",
      "upstream_url": "http://localhost:80",
      "url": "https://47f79e58f8db.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-01T10:07:18Z",
      "domain": {
        "id": "rd_2wURCSO84s1xv9Y0Bu04cQNtciU",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wURCSO84s1xv9Y0Bu04cQNtciU"
      },
      "edge": {
        "id": "edgtls_2wURCR5g4djML8W0zJXSnHGm63f",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2wURCR5g4djML8W0zJXSnHGm63f"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wURCRtdsKsTzlbA35xlZahgANu",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-01T10:07:18Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
