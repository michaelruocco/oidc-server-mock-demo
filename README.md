# OIDC Server Mock Demo

This repo contains some example configuration for [OIDC Server Mock](https://github.com/Soluto/oidc-server-mock)
with an accompanying postman collection to show how to generate access tokens for some different
authorization flows.

## Starting the OIDC Server Mock

To run the OIDC Server Mock you can just run the following docker compose command:

```bash
docker-compose up -d
```

## Generating Access Tokens

Once the server is running, you can import the postman collection into postman, and then
try out generating an access token from the authorization tab for each of the different
examples.

## Stopping the OIDC Server Mock

Once you have finished running the examples you can stop the server again by running

```bash
docker-compose down
```

## Other useful links

[What the heck is oauth](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth)
[What is the oauth2 password grant](https://developer.okta.com/blog/2018/06/29/what-is-the-oauth2-password-grant)
[An illustrated guide to oauth and openid connect](https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc)