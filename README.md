# Docker Bitcore

This is a working docker image of Bitcore. Inspired by this repository: https://github.com/WooGenius/bitcore-docker

## Run

    sudo docker run -d -p 3001:3001 -p 8333:8333 -v bitcore:/bitcore/data berndinox/docker-bitcore

## Volumes

- `bitcore:/bitcore/data` - this is the storage for blockchain data
