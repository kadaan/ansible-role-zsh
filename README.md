# Ansible Role: Zsh

[![CI][badge-gh-actions]][link-gh-actions]

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

[badge-gh-actions]: https://github.com/kadaan/ansible-role-zsh/workflows/CI/badge.svg?event=push
[link-gh-actions]: https://github.com/kadaan/ansible-role-zsh/actions?query=workflow%3ACI