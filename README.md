# Micronaut Testing – Keycloak

This app is just for testing the integration of Micronaut with Keycloak.

This app has just one endpoint on the root path (`/`) which returns just an `Hello World` in plain text. The endpoint is secured with the security rule `IS_AUTHENTICATED`.

Login mechanism:
- http://localhost:8080/oauth/login/
- http://localhost:8080/oauth/logout/
- http://x.x.x.x/auth/realms/dev-fr/protocol/openid-connect/logout?redirect_uri=http%3A%2F%2Flocalhost%3A8080%2F