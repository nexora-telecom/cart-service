# Cart Service (Nexora Telecom Platform)
Polyrepo microservice for shopping cart state management, backed by AWS ElastiCache for Redis with in-transit TLS.

# Cart Service

This service stores user shopping carts in Valkey.

## Local Build

Run `dotnet restore` and `dotnet build`.

## Docker Build

From the root directory of this repository, run:

```sh
docker compose build cart
```
