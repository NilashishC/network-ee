[![Publish EE](https://github.com/NilashishC/network-ee/actions/workflows/publish.yml/badge.svg?branch=main&event=schedule)](https://github.com/NilashishC/network-ee/actions/workflows/publish.yml)
# network-ee

* A super unofficial take at building an Ansible Network specific upstream Execution Environment based on `community-minimal-ee`.
* The latest `ansible-core` available in `PyPI` is used.
* All networking collections are installed from source (and not galaxy), so you always have the latest and greatest.
* The image is built and published on a nightly basis.
* Get started with:

        podman pull ghcr.io/nilashishc/network-ee:latest
