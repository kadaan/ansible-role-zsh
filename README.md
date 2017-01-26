# Ansible Role: Zsh

[![Build Status](https://travis-ci.org/kadaan/ansible-role-zsh.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-zsh)

Installs zsh and configures it as the default shell.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - `geerlingguy.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.zsh }

## License

Apache 2.0
