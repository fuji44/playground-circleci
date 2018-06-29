# Playground CircleCI

## Preparation

CircleCI Local CLI and Docker required

```sh
sudo snap install docker circleci
sudo snap connect circleci:docker docker
```

Install CircleCi Local CLI
https://circleci.com/docs/2.0/local-cli/#installing-the-circleci-local-cli-on-macos-and-linux-distros

docker-snap
https://github.com/docker/docker-snap

## Run

Run on project route

```sh
circleci build
# or
circleci build -c .circleci/config.yml
```