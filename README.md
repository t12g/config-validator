# Forseti Config Validator

This is a Golang library which provides functionality to evaluate
GCP resources against Rego-based policies. It can be used to add
config policy support to new projects without having to integrate
Rego parsing directly.

## Development
### Available Commands

```sh
make proto     rebuilt protobuf library
make test      run unit tests
make build     rebuilt and reformat
make release   build binaries
make clear     delete binaries
make format    reformat code
```

## Disclaimer
This is not an officially supported Google product.
