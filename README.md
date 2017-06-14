# ansible-docker

An Ansible role for installing Docker.

## Role Variables

- `docker_version` - Docker version (default `17.*`)
- `docker_options` - Options passed to the Docker daemon
- `docker_key_url` - Docker APT repository keyserver to use.
- `docker_package_name` - Name of docker package (`docker-ce` or `docker-ee`, defaults to `docker-ce`
)

## Example Playbook

See the [examples](./examples/) directory.
