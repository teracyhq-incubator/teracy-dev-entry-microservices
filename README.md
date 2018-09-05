# teracy-dev-entry for microservices platform

A convenient teracy-dev-entry with default extensions to setup a local microservices platform atop k8s cluster which works the same as in the cloud


## How to use

- Clone `teracy-dev` and init `teracy-dev-entry` to `vagrant up`:

```bash
$ cd ~/
$ git clone https://github.com/teracyhq/dev.git -b v0.6.0-a2 microservices-platform-dev
$ cd microservices-platform-dev
$ TERACY_DEV_ENTRY_LOCATION_GIT=https://github.com/teracyhq-incubator/teracy-dev-entry-microservices-platform.git \
  TERACY_DEV_ENTRY_LOCATION_BRANCH=develop TERACY_DEV_ENTRY_LOCATION_SYNC=true \
  vagrant up
```
