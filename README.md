# terraform

[![CircleCI](https://circleci.com/gh/tmknom/terraform.svg?style=svg)](https://circleci.com/gh/tmknom/terraform)
[![Docker Build Status](https://img.shields.io/docker/build/tmknom/terraform.svg)](https://hub.docker.com/r/tmknom/terraform/builds/)
[![Docker Automated build](https://img.shields.io/docker/automated/tmknom/terraform.svg)](https://hub.docker.com/r/tmknom/terraform/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/tmknom/terraform.svg)](https://microbadger.com/images/tmknom/terraform)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/tmknom/terraform.svg)](https://microbadger.com/images/tmknom/terraform)
[![License](https://img.shields.io/github/license/tmknom/terraform.svg)](https://opensource.org/licenses/Apache-2.0)

Dockerfile template.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/terraform/master/install | sh -s example
cd example
```

## Makefile targets

```text
build                          Build docker image
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
```

## Development

### Installation

```shell
git clone git@github.com:tmknom/terraform.git
cd terraform
make install
```

### Deployment

Automatically deployed by "[DockerHub Automated Build](https://docs.docker.com/docker-hub/builds/)" after merge.

### Deployment Pipeline

1. GitHub - Version Control System
   - <https://github.com/tmknom/terraform>
2. CircleCI - Continuous Integration
   - <https://circleci.com/gh/tmknom/terraform>
3. Docker Hub - Docker Registry
   - <https://hub.docker.com/r/tmknom/terraform>
4. MicroBadger - Docker Inspection
   - <https://microbadger.com/images/tmknom/terraform>

## License

Apache 2 Licensed. See LICENSE for full details.
