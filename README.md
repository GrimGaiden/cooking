# cooking
Demo project with: MVC, Kafka, HATEOAS, OpenAPI, PostgreSQL, contract testing

## Testcontainers
### Podman configuration

To use TestContainers with Podman in linux the following environment variables must be created:
 - export DOCKER_HOST=unix:///run/user/$(id -u)/podman/podman.sock
 - export DOCKER_CERT_PATH=/run/user/$(id -u)/podman
 - export DOCKER_TLS_VERIFY=0
