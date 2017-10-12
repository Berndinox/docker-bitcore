# Docker Bitcore

This is a docker image of Bitcore.

## Run

    sudo docker run -d -p 3001:3001 -p 8333:8333 -v bitcore:/bitcore/data andyceo/bitcore

## Volumes

- `bitcore:/bitcore/data:rw` - this is the storage for blockchain and wallet data.
