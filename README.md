﻿# proteus-docker

This repo contains some `docker-compose` setups for [PROtEUS](https://github.com/IoTUDresden/proteus).
You may have to download the OpenHAB 2.2 Addons from [Releases](https://github.com/IoTUDresden/proteus-docker/releases) and put it in the `openhab/openhab_addons` folder.

## usage

* Type `docker-compose -f filename.yml up`.


### all

This setup contains all services needed for a complete superpeer setup in the lab.

### fbs

Only [Feedback-Service](https://github.com/IoTUDresden/feedback-service).

### proteus

Only [PROtEUS](https://github.com/IoTUDresden/proteus).

### openhab

Only [OpenHAB](https://github.com/IoTUDresden/openhab-distro) with the lab setup (configuration folders are under the directory `openhab`).

