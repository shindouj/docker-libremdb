# docker-libremdb

`docker pull ghcr.io/shindouj/libremdb:latest`

A [libremdb](https://github.com/zyachel/libremdb) image, forked from [PussTheCat](https://github.com/PussTheCat-org/docker-libremdb-quay).
Used for the [jeikobu.net](https://libremdb.jeikobu.net) instance. The main difference is creating images only when an actual change in code has occured.

## Usage:

- Download (or copy the content of) the `docker-compose.yml` to any folder you want
- (Optional) Customize the environment variable with the settings you want to apply
- `docker-compose up -d`
