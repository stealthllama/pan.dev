Returns the global settings for image, host, container, and registry scanning.

## cURL Request

Refer to the following example cURL request:

```bash
$ curl -k \
  -u <USER> \
  -H 'Content-Type: application/json' \
  -X GET \
  "https://<CONSOLE>/api/v<VERSION>/settings/scan"
```
