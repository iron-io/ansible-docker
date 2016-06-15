# ansible-docker
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

This role will install Docker on a VM.

# Tunables

- None

## Dependencies

- None

## Example Usage

To use in a playbook

```
- name: Install Docker
  hosts: all
  sudo: yes
  roles:
   - role: iron-io.docker
```

## Vagrant

To spin up a new Vagrant machine with docker installed for easy testing:

```
vagrant up
```
this will copy our microdockers repo from `files/dockers` onto the machine for use at `/files/dockers`.

## License

MIT

## Author

Ben Visser (ben@iron.io)
