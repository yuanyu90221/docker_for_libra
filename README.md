# libra_ubuntu_18.04_container_env

# introduction 

  a docker-compose setup for build dev env for [libra](https://developers.libra.org/)

# Pre-install

  [docker](https://docs.docker.com/ee/)

  [docker-compose](https://docs.docker.com/compose/install/)

# how-to-use

## 1. create build env

```
  docker-compose up -d
```

## 2. connect to container shell
```
  docker exec -it ubuntu-docker-libra /bin/bash
```
## 3. build with init script

```
  cd /home/ubuntu/libra && ./scripts/dev_setup.sh
```

## 4. build with libra default setup

```
  cd /home/ubuntu/libra && ./scripts/cli/start_cli_testnet.sh
```


