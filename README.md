# README.md
# Ansible Role: Neos 0.1.x

An Ansible role that installs Acme 0.1.x on Debian 8.x

## Requirements

If not Installed you need php cli .


## Role Variables

Available variables are listed below, along with default values:

    neos_listen_port: 80
    neos_listen_port_ssl: 443

## Dependencies

- username.iptables - configure the firewall and block all ports except those needed for the web server and ssh access.
- username.common - perform common server configuration

## Example Playbook

    - hosts: webservers
      roles:
        - { role: username.acme }

## License

MIT
