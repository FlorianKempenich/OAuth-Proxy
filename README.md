# Oauth Proxy

Enabling OAuth for CLI apps WITHOUT having exposing the `client_secret` to the end user (of the CLI app).

The proxy takes care of encapsulating the `client_secret`, and requests the access token without the intervention of the end user. Step 4 of [Introduction to Oauth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
