# Ansible Role: fail2ban

[![Lint](https://github.com/dcjulian29/ansible-role-fail2ban/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-fail2ban/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-fail2ban.svg)](https://github.com/dcjulian29/ansible-role-fail2ban/issues)

This an Ansible role to install and configure fail2ban.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.fail2ban
  src: https://github.com/dcjulian29/ansible-role-fail2ban.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
