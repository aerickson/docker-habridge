[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?style=flat-square&color=E68523&label=Discord&logo=discord&logoColor=FFFFFF)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?style=flat-square&color=E68523&logo=discourse&logoColor=FFFFFF)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=GitHub&logo=github&logoColor=FFFFFF)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?style=flat-square&color=E68523&label=Supporters&logo=open%20collective&logoColor=FFFFFF)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

 * regular and timely application updates
 * easy user mappings (PGID, PUID)
 * custom base image with s6 overlay
 * weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
 * regular security updates

Find us at:
* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/habridge](https://github.com/linuxserver/docker-habridge)

[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-habridge.svg?style=flat-square&color=E68523&logo=github&logoColor=FFFFFF)](https://github.com/linuxserver/docker-habridge)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-habridge.svg?style=flat-square&color=E68523&logo=github&logoColor=FFFFFF)](https://github.com/linuxserver/docker-habridge/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=GitHub%20Package&logo=github&logoColor=FFFFFF)](https://github.com/linuxserver/docker-habridge/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab&logoColor=FFFFFF)](https://gitlab.com/Linuxserver.io/docker-habridge/container_registry)
[![Quay.io](https://img.shields.io/static/v1.svg?style=flat-square&color=E68523&label=linuxserver.io&message=Quay.io)](https://quay.io/repository/linuxserver.io/habridge)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/linuxserver/habridge.svg?style=flat-square&color=E68523)](https://microbadger.com/images/linuxserver/habridge "Get your own version badge on microbadger.com")
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/habridge.svg?style=flat-square&color=E68523&label=pulls&logo=docker&logoColor=FFFFFF)](https://hub.docker.com/r/linuxserver/habridge)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/habridge.svg?style=flat-square&color=E68523&label=stars&logo=docker&logoColor=FFFFFF)](https://hub.docker.com/r/linuxserver/habridge)
[![Build Status](https://ci.linuxserver.io/view/all/job/Docker-Pipeline-Builders/job/docker-habridge/job/master/badge/icon?style=flat-square)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-habridge/job/master/)
[![](https://lsio-ci.ams3.digitaloceanspaces.com/linuxserver/habridge/latest/badge.svg)](https://lsio-ci.ams3.digitaloceanspaces.com/linuxserver/habridge/latest/index.html)

[Habridge](http://bwssystems.com/#/habridge) emulates Philips Hue API to other home automation gateways such as an Amazon Echo/Dot Gen 1 (gen 2 has issues discovering ha-bridge) or other systems that support Philips Hue. The Bridge handles basic commands such as "On", "Off" and "brightness" commands of the hue protocol. This bridge can control most devices that have a distinct API.

In the cases of systems that require authorization and/or have APIs that cannot be handled in the current method, a module may need to be built. The Harmony Hub is such a module and so is the Nest module. The Bridge has helpers to build devices for the gateway for the Logitech Harmony Hub, Vera, Vera Lite or Vera Edge, Nest, Somfy Tahoma, Home Assistant, Domoticz, MQTT, HAL, Fibaro, HomeWizard, LIFX, OpenHAB, FHEM, Broadlink and the ability to proxy all of your real Hue bridges behind this bridge.

This bridge was built to help put the Internet of Things together.

For more information about how to use this software have a look at their Wiki [https://github.com/bwssytems/ha-bridge/wiki](https://github.com/bwssytems/ha-bridge/wiki)


[![habridge](https://raw.githubusercontent.com/bwssytems/ha-bridge/master/src/main/resources/public/img/favicon.ico)](http://bwssystems.com/#/habridge)

## Supported Architectures

Our images support multiple architectures such as `x86-64`, `arm64` and `armhf`. We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-2.md#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `linuxserver/habridge` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Tag |
| :----: | --- |
| x86-64 | amd64-latest |
| arm64 | arm64v8-latest |
| armhf | arm32v7-latest |


## Usage

Here are some example snippets to help you get started creating a container.

### docker

```
docker create \
  --name=habridge \
  -e PUID=1000 \
  -e PGID=1000 \
  -e SEC_KEY=<Your Key To Encrypt Security Data> \
  -e TZ=Europe/London \
  -p 8080:8080 \
  -p 50000:50000 \
  -v <path to data>:/config \
  --restart unless-stopped \
  linuxserver/habridge
```


### docker-compose

Compatible with docker-compose v2 schemas.

```
---
version: "2.1"
services:
  habridge:
    image: linuxserver/habridge
    container_name: habridge
    environment:
      - PUID=1000
      - PGID=1000
      - SEC_KEY=<Your Key To Encrypt Security Data>
      - TZ=Europe/London
    volumes:
      - <path to data>:/config
    ports:
      - 8080:8080
      - 50000:50000
    restart: unless-stopped
```

## Parameters

Container images are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 8080` | WebUI |
| `-p 50000` | HABridge communication port. |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e SEC_KEY=<Your Key To Encrypt Security Data>` | Key used to secure communication. |
| `-e TZ=Europe/London` | Specify a timezone to use EG Europe/London. |
| `-v /config` | Where HABridge stores config files and data. |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`. 

As an example:

```
-e FILE__PASSWORD=/run/secrets/mysecretpassword
```

Will set the environment variable `PASSWORD` based on the contents of the `/run/secrets/mysecretpassword` file.

## User / Group Identifiers

When using volumes (`-v` flags) permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id user` as below:

```
  $ id username
    uid=1000(dockeruser) gid=1000(dockergroup) groups=1000(dockergroup)
```


&nbsp;
## Application Setup

To set up the ha-bridge simply go to http://localhost:8080. Once you are in the webui you can add devices and configure ha-bridge to your liking.

For information on how to configure ha-bridge, go to their wiki at [https://github.com/bwssytems/ha-bridge/wiki](https://github.com/bwssytems/ha-bridge/wiki)


## Docker Mods
[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?style=for-the-badge&color=E68523&label=mods&query=%24.mods%5B%27habridge%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=habridge "view available mods for this container.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) can be accessed via the dynamic badge above.


## Support Info

* Shell access whilst the container is running: `docker exec -it habridge /bin/bash`
* To monitor the logs of the container in realtime: `docker logs -f habridge`
* container version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' habridge`
* image version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' linuxserver/habridge`

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (ie. nextcloud, plex), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Run/Create
* Update the image: `docker pull linuxserver/habridge`
* Stop the running container: `docker stop habridge`
* Delete the container: `docker rm habridge`
* Recreate a new container with the same docker create parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* Start the new container: `docker start habridge`
* You can also remove the old dangling images: `docker image prune`

### Via Docker Compose
* Update all images: `docker-compose pull`
  * or update a single image: `docker-compose pull habridge`
* Let compose update all containers as necessary: `docker-compose up -d`
  * or update a single container: `docker-compose up -d habridge`
* You can also remove the old dangling images: `docker image prune`

### Via Watchtower auto-updater (especially useful if you don't remember the original parameters)
* Pull the latest image at its tag and replace it with the same env variables in one run:
  ```
  docker run --rm \
  -v /var/run/docker.sock:/var/run/docker.sock \
  containrrr/watchtower \
  --run-once habridge
  ```

**Note:** We do not endorse the use of Watchtower as a solution to automated updates of existing Docker containers. In fact we generally discourage automated updates. However, this is a useful tool for one-time manual updates of containers where you have forgotten the original parameters. In the long term, we highly recommend using Docker Compose.

* You can also remove the old dangling images: `docker image prune`

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:
```
git clone https://github.com/linuxserver/docker-habridge.git
cd docker-habridge
docker build \
  --no-cache \
  --pull \
  -t linuxserver/habridge:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`
```
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **19.12.19:** - Rebasing to alpine 3.11.
* **28.06.19:** - Rebasing to alpine 3.10.
* **23.03.19:** - Switching to new Base images, shift to arm32v7 tag.
* **22.02.19:** - Rebasing to alpine 3.9.
* **11.02.19:** - Add pipeline logic and multi arch.
* **28.08.18:** - Rebase to alpine 3.8.
* **12.04.18:** - Add workaround to bind to port 80 if needed.
* **08.04.18:** - Initial Release.
