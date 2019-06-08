# README.md
# Ansible Role: Neos

An Ansible role that installs Neos CMS System

## Requirements

If not Installed you need php cli .

## Role Variables

Available variables are listed below, along with default values:

    neos_listen_port: 80
    neos_listen_port_ssl: 443

## Dependencies

## Example Playbook

    - hosts: webservers
      roles:
        - { role: ansible-role-neos }

## License

MIT
