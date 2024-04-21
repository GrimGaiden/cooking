# cooking
Demo project with: MVC, Kafka, HATEOAS, OpenAPI, PostgreSQL, contract testing

## Testcontainers
### Podman configuration

To use TestContainers with Podman in linux the following environment variables must be created:
 - export DOCKER_HOST=unix://${XDG_RUNTIME_DIR}/podman/podman.sock
 - export DOCKER_CERT_PATH=${XDG_RUNTIME_DIR}/podman
 - export DOCKER_TLS_VERIFY=0

If running Podman in rootless mode:
 - export TESTCONTAINERS_RYUK_DISABLED=true
