# HelixML Frontend API + OpenAPI Spec

This repo contains an unofficial swagger document of HelixML Frontend API (https://docs.helix.ml/). It is written to the OpenAPI 3 spec and tested to render correctly in swagger.io editor and builds with the openAPI generator (typescript-axios).

Note: This is not a 100% representation of the API Spec and updates are best effort. Please see KNOWN_ISSUES. Please refer to https://docs.helix.ml for the official API documentation.

Note: This document is not affliated with HelixML. Issues and/or support should relating to this library be directed to the project's issue tracker.

## Prerequistites

* Based on Helix (https://github.com/helixml/helix) v0.5.5. No guarantees for later versions.

## Usage
Best viewed in Swagger UI (https://swagger.io/tools/swagger-ui/). You should also be able to import this document where openAPI3 spec is supported.

To generate the API client, run the following commands. The default generator is https://openapi-generator.tech/docs/generators/typescript-axios/ but feel free to change this in the relevant package.json script.

```
yarn install
yarn lint
yarn generate
```

## License

MIT