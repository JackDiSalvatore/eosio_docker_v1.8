# eosio_docker_v1.8

eosio: v1.8

eosio.cdt: v1.6.3

eosio.contracts: 1.7.0 (not included)

```bash
docker build -t myeos -f Dockerfile.ubuntu .
```

NOTES:
```
RUN apt-get update && apt-get install -y --no-install-recommends libssl1.1 libcurl3-gnutls \
    libusb-1.0-0 git automake clang-8 curl make apt-transport-https ca-certificates gnupg \
    libtool software-properties-common wget llvm-4.0 openssl1.1 libssl-dev libgmp3-dev libicu60 \
    && rm -rf /var/lib/apt/lists/*

  llvm-4.0-runtime
  libclang-4.0-dev

  libllvm4.0
  llvm-4.0-dev
```