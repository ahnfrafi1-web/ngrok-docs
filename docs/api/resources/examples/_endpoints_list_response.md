<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-26T10:07:43Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_33ETVm6RSKywsndxFOGWn5KD97r",
        "uri": "https://api.ngrok.com/reserved_domains/rd_33ETVm6RSKywsndxFOGWn5KD97r"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_33ETWVCdy5JEFt2HOuQyD9LTTCx",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-26T10:07:43Z",
      "uri": "https://api.ngrok.com/endpoints/ep_33ETWVCdy5JEFt2HOuQyD9LTTCx",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-26T10:07:40Z",
      "hostport": "0977d75c66ae.ngrok.paid:443",
      "id": "ep_33ETWC5pX5vDk4UsdfbQk0ElvQA",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_33ETPdSD5wuylay6KZ4lGl3bBND",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://0977d75c66ae.ngrok.paid",
      "tunnel": {
        "id": "tn_33ETWC5pX5vDk4UsdfbQk0ElvQA",
        "uri": "https://api.ngrok.com/tunnels/tn_33ETWC5pX5vDk4UsdfbQk0ElvQA"
      },
      "tunnel_session": {
        "id": "ts_33ETW7k96se7YOrC4cDCEX12hNX",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_33ETW7k96se7YOrC4cDCEX12hNX"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-26T10:07:40Z",
      "upstream_url": "http://localhost:80",
      "url": "https://0977d75c66ae.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-26T10:07:38Z",
      "domain": {
        "id": "rd_33ETVm6RSKywsndxFOGWn5KD97r",
        "uri": "https://api.ngrok.com/reserved_domains/rd_33ETVm6RSKywsndxFOGWn5KD97r"
      },
      "edge": {
        "id": "edgtls_33ETVrYNYyVExcEoQ1sIDMfYtxL",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_33ETVrYNYyVExcEoQ1sIDMfYtxL"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_33ETVu8M30LG4TIjCgEDrPpiPDS",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-26T10:07:38Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
