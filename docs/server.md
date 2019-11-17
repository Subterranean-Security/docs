# The Server

## Geolocation Services
Sandpolis is able to get its location information from several sources. The server can only use one service at a time. To choose a service, set the following system properties:

| Property   | Description |
|------------|-------------|
| server.geolocation.service | The name of the geolocation service to use. Valid values are found in the table below. Defaults to `ip-api.com`. |
| server.geolocation.key | The API key to use |
| server.geolocation.expiration | The cache timeout in hours. Default is `240`. |

| Service    | Additional |
|------------|------------|
| <a href="https://ip-api.com" target="_blank">ip-api.com</a> | `ip-api.com` |
| <a href="https://tools.keycdn.com/geo" target="_blank">tools.keycdn.com</a> | `keycdn.com` |