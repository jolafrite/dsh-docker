# DSH Docker

DSH running in a container. The host volume holds only durable user state;

## Getting started

```bash
make start   # build + start all services
make url     # print the GUI URL
```

## Maintenance

```bash
make restart     # restart the container (ephemeral data is lost)
make wipe-cache  # same as restart, with a clearer name
make clean-all   # remove container, images, and named volumes
```
