# What is this?
[苦しんで覚えるC言語](https://9cguide.appspot.com/)のサンプルコードをDocker環境で試せるようにしたリポジトリです。

# Usage
## Preparation
Install [Docker](https://docs.docker.com/install/).

## For MacOS/Linux

1. Build Docker image

    `./setup.sh`

2. Start bash with Docker container

    `./run_bash.sh`

## Tips

### Go into the container which is already running.
Run `docker exec -it  clang bash` at another tab/window.
