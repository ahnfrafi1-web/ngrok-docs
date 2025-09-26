<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_33ETTlxM2qsKO0xpv6ObeU9DGxJ",
        "uri": "https://api.ngrok.com/tls_certificates/cert_33ETTlxM2qsKO0xpv6ObeU9DGxJ"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.kjvjhdxmsjopg1pl.local-ngrok-cname.com",
      "created_at": "2025-09-26T10:07:21Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33ETTyB5FAmxlX4rngiM36QO1Ir",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33ETTyB5FAmxlX4rngiM36QO1Ir"
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
          "started_at": "2025-09-26T10:07:22Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.kjvjhdxmsjopg1pl.local-ngrok-cname.com",
      "created_at": "2025-09-26T10:07:22Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33ETTrneuCKZQUol4v19cAm7dOd",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33ETTrneuCKZQUol4v19cAm7dOd"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-26T10:06:51Z",
      "description": "Your dev domain",
      "domain": "unsaccharine-breanne-mechanomorphically.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33ETQ22DRsJu4q8VB5mBb5wANDL",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33ETQ22DRsJu4q8VB5mBb5wANDL"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
