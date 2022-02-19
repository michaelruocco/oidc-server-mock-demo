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