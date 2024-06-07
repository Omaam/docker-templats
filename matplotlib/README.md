# Ubuntu with matplotlib

Matplotlib の docker image and container.


## Install

```shell
mkdir -p $HOME/tmp
cd $HOME/tmp
git clone https://github.com/Omaam/docker-templats.git
cd docker-templats/matplotlib
docker compose build
docker compose up -d
docker compose exec work /bin/bash
```
