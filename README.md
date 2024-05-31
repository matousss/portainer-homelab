# Portainer - Homelab

This repository holds deployment configuration (`docker-compose.yml` files) for my homelab server(s).
Services are accessed throught traefic reverse proxy. For *.lan hostnames I am using custom DNS.

Each directory represents portainer stack except *portainer* and *traefik* (unsurprisingly).

Stacks are configured using env variables, you can explore `template.env` files in each directory, which can be imported in portainer interface.
