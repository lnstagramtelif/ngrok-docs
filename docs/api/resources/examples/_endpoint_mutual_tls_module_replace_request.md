
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2GjEzNVr3z8IrQT7lhOAJjI9tfa"]}' \
https://api.ngrok.com/endpoint_configurations/ec_2GjEzJ2fskcBbTAjCRt6hDxAONG/mutual_tls
