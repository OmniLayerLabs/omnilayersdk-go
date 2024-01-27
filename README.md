![Unit Tests](https://github.com/Layr-Labs/eigensdk-go/actions/workflows/unit-tests.yml/badge.svg)
![Linter](https://github.com/Layr-Labs/eigensdk-go/actions/workflows/golangci-lint.yml/badge.svg)
![Go Coverage](https://github.com/Layr-Labs/eigensdk-go/wiki/coverage.svg)

<p align="center"><b>
🚧 Under active development. OMNILAYERSDK-GO is rapidly being upgraded, features are being added, interfaces will have breaking changes 🚧
</b><p>

**Do not use it in Production, testnet only.**

## EigenSDK
This SDK provides a set of primitive Go modules for developing AVSs used in OmniLayer

## Installation
```
go get github.com/Layr-Labs/omnilayersdk-go
```

## Modules
We support following modules right now. 
> **_NOTE:_** All modules are in active development and interfaces might change. 
* [Logging](./logging/README.md)
* [Signer](./signer/README.md)
* [ChainIO](./chainio/README.md)
* [Services](./services/README.md)

## Development
Clone the repo
```
git clone https://github.com/Layr-Labs/omnilayersdk-go.git
```
Initialize git submodules
```
git submodule update --init
```

Follow the [contribution guidelines](CONTRIBUTING.md) to contribute to omnilayersdk-go

## Security Bugs
Please report security vulnerabilities to security@omnilayerlabs.org. Do NOT report security bugs via Github Issues.
