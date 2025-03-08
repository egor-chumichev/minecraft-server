# Minecraft Server

This repository contains a Minecraft server based on the Fabric engine. The application is fully dockerized, making deployment quick and easy.

## Deployment

To deploy the application, simply clone this repository to your server and run:

```sh
sudo docker compose -f ./docker/compose.yaml up -d
```

## Properties

By default, the server runs with a sample configuration located in the `./configuration/` directory.

## Author

Made by Egor Chumichev. Creeper? Oh, man.
