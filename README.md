# README.md
# Ansible Role: Neos

An Ansible role that installs and configure Neos CMS System not more!

> This role not ready to use . It is just a first Idee. 
> I didn't have technical details to fix some errors between Ansible and neos. 
> If anyone have a idee than fiel free too inform me.

## Requirements

If not Installed you need php cli and a MySQL or MariaDB Server.

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
