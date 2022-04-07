# Simple standalone Wiremock

A simple docker compose file to start a standalone Wiremock by mounting the local *mappings* and *files* directories into the container.

## Start standalone Wiremock

    docker compose up --detach

## Port

Wiremock will start on port **8090**.

Port can be changed in the *docker-compose.yml*

## Getting all currently registered stub mappings

Visit to the following url to see all current mappings:

http://localhost:8090/__admin/mappings