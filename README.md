# uni-resolver-driver-did-kscirc
Universal Resolver Driver for Kscirc DIDs

![logo-dif](https://github.com/user-attachments/assets/d13243e3-61f3-4886-a8a0-81ca59ad3d5a)

## Universal Resolver Driver: driver-did-kscirc

This is a [Universal Resolver](https://github.com/decentralized-identity/universal-resolver) driver for `did:kscirc` identifiers.

## Specifications

- [Decentralized Identifiers](https://www.w3.org/TR/did-core/)
- [KScirc DID Specification](https://tangy-gallium-b9b.notion.site/DID-Method-Specification-KSChain-7a77664f1eae47769692f4ff2d029fe0?pvs=74)

## Example DIDs

- `did:kscirc:k7745fAnbFGBeECS7xTDkowVXZZxEvMhpfbcQjaLYSiyed5du9MJ`

## Docker Images(latest version : v1.0.1)

- [k4security/kschain-resolver](https://hub.docker.com/r/k4security/kschain-resolver/tags)

## Build and Run (Docker Compose)

1. **Pull the Docker images**
   ```bash
   docker pull k4security/kschain-resolver:v1.0.1

2. **Run `kschain-resolver` using Docker**

   After pulling the `kschain-resolver` image from Docker Hub, you can run the container with the following command:

   ```bash
   docker run --rm -d -p 9800:9800 k4security/kschain-resolver:v1.0.1
