# Axum Server Generator Templates


You can test the template locally with the following command

```
openapi-generator-cli generate -i ../lottery.json -g rust-server -o lottery -c config.yaml
```

The Axum Generator templates use Mustache Partials.

The following tree shows which templates include which:

- `api_doc.mustache`
- `cargo-config`
- `Cargo.mustache`
- `context.mustache`
- `client-callbacks-mod.mustache`
  - `server-imports.mustache`
  - `server-make-service.mustache`
  - `server-service-footer.mustache`
  - `server-service-header.mustache`
  - `server-operation.mustache`
- `client-mod.mustache`
  - `client-imports.mustache`
  - `client-operation.mustache`
- `example-ca.pem`
- `example-client-main.mustache`
- `example-client-server.mustache`
- `example-server-chain.pem`
- `example-server-common.mustache`
- `example-server-key.pem`
- `example-server-main.mustache`
- `example-server-server.mustache`
  - `example-server-operation.mustache`
- `gitignore`
- `header.mustache`
- `lib.mustache`
  - `response.mustache`
- `model_doc.mustache`
- `models.mustache`
- `openapi.mustache`
- `README.mustache`
- `server-callbacks.mustache`
  - `client-imports.mustache`
  - `client-operation.mustache`
- `server-service-header.mustache`
- `server-mod.mustache`
  - `server-imports.mustache`
  - `server-make-service.mustache`
  - `server-service-footer.mustache`
  - `server-service-header.mustache`
  - `server-operation.mustache`
- `server-paths.mustache`
