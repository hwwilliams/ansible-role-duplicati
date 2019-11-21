# Ansible Role: Duplicati

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-duplicati.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-duplicati)

Installs [Duplicati](https://www.duplicati.com/) on Debian/Ubuntu and CentOS/Redhat based Linux systems.

This role installs and configures the latest version of Duplicati from the offical [Duplicati](https://github.com/duplicati/duplicati) Github repo.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/duplicati).

## Requirements

Recent version of Mono, I haven't included this in the role yet but will provide an option in the future. CentOS 7 was the only host so far I've found that had issues with its default version of Mono.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## License

MIT
