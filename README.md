# Ubuntu based image for Ansible CI testing.

[![Docker Automated build](https://img.shields.io/docker/cloud/build/jdubz/docker-ci-ubuntu.svg?maxAge=2592000)](https://hub.docker.com/r/jdubz/docker-ci-ubuntu/)
[![Docker pulls](https://img.shields.io/docker/pulls/jdubz/docker-ci-ubuntu.svg?maxAge=2592000)](https://hub.docker.com/r/jdubz/docker-ci-ubuntu/)

For testing Ansible playbooks and roles on Gitlab CI. Includes a functional
systemd for testing system service interaction.  Needs the following `tmpfs`
mounts:

* `/run`
* `/run/lock`
* `/tmp`

## Tags

- [`groovy`, `latest`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/groovy/Dockerfile)
- [`focal`, `stable`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/focal/Dockerfile)
- [`eoan`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/eoan/Dockerfile)
- [`bionic`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/bionic/Dockerfile)
- [`xenial`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/xenial/Dockerfile)
- [`trusty`](https://git.dubzland.net/jdubz/docker-ci-ubuntu/blob/trusty/Dockerfile)

## License

MIT

## Author

* [Josh Williams](https://dubzland.net)
