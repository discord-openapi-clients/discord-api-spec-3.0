# Introduction
This repository uses Github Actions to automatically pull the latest [Discord OpenAPI specification](https://github.com/discord/discord-api-spec) and convert it from the OpenAPI 3.1 schema to the OpenAPI 3.0 schema, using [openapi-down-convert](https://github.com/apiture/openapi-down-convert). This is needed, as many tools do not support the v3.1 schema yet.

The schema file can be fouynd [here](./openapi-3.0.yaml).

# Clients
We provide some clients that are automatically kept up to date with the specification, generated using [openapi-generator](https://github.com/OpenAPITools/openapi-generator). However, you can use the schema file to use your preferred generator of choice locally.

- Go: [https://github.com/discord-openapi-clients/go]