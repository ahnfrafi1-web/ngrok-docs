<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-26T10:07:49Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_33ETXFyGjmddjuZTLmXjW3Rv3fq",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_33ETXFyGjmddjuZTLmXjW3Rv3fq"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_33ETVs2wvEj4O0rXtizSo5khiTf",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_33ETVs2wvEj4O0rXtizSo5khiTf"
        },
        "enabled": true
      },
      "created_at": "2025-09-26T10:07:38Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_33ETVrYNYyVExcEoQ1sIDMfYtxL",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_33ETVrYNYyVExcEoQ1sIDMfYtxL"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
