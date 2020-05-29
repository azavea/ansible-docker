# ansible-docker

An Ansible role for installing Docker.

## Role Variables

- `docker_repository_arch` - Architecture for Docker package repository (default: `amd64`)
- `docker_packages` - Names of Docker packages (default: `docker-ce=docker_version`, `docker-ce-cli=docker_version`, `containerd.io=docker_containerd_version`)
- `docker_version` - Docker version (default `5:19.*`)
- `docker_containerd_version`: Containerd version (default: `1.2.*`)
- `docker_options` - Options passed to the Docker daemon

## Example Playbook

See the [examples](./examples/) directory.
