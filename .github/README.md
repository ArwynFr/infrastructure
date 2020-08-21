# infrastructure

[![GitHub Actions](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Farwynfr%2Finfrastructure%2Fbadge)](https://actions-badge.atrox.dev/arwynfr/infrastructure/goto)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f6e55299939544fd9350d06c96557d9b)](https://www.codacy.com/manual/ArwynFr/infrastructure?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ArwynFr/infrastructure&amp;utm_campaign=Badge_Grade)

## What is this repository about

This projects is the source my personal host server reverse proxy.

## Rules and standards

This project is licensed under [MIT License](/LICENSE)

## How it works

This project was a way for me to have all my infrastructure elements versionned on Github.

The reason why the `reverse` network must be created externally to the stack, is that otherwise you can't modify the reverse stack while any other stack is using the network. You would need to stop all services in order to update traefik or configuration files.

## How to contribute

This project is not expecting any external contributions.
