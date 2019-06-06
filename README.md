# ansible-docker

An Ansible role for installing Docker.

## Role Variables

- `docker_repository_arch` - Arch version of docker package (default `amd64`)
- `docker_package_name` - Name of docker package (`docker-ce` or `docker-ee`, defaults to `docker-ce`)
- `docker_version` - Docker version (default `17.*`)
- `docker_options` - Options passed to the Docker daemon

## Example Playbook

See the [examples](./examples/) directory.
