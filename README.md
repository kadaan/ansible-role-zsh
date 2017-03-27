# Ansible Role: Zsh

[![Build Status](https://travis-ci.org/kadaan/ansible-role-zsh.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-zsh)

Installs zsh and configures it as the default shell.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - [kadaan.homebrew](https://galaxy.ansible.com/kadaan/homebrew/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.zsh, zsh_execute: true }

## License

Apache 2.0
