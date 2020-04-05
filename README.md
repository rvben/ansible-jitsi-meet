# ansible-jitsi-meet

Easy and Simple way to install Jitsi Meet on Ubuntu

This playbook is written to make setting up a Jitsi Meet server as simple as possible.
Using this playbook, Jitsi Meet is set up with Nginx and Let's Encrypt certificates.

## Prerequisites

- VM (Ubuntu 18.04)
- Public DNS record pointing to IP of VM

## Quick Start

1. Clone repository

```bash
\$ git clone https://github.com/rvben/ansible-jitsi-meet.git
\$ cd ansible-jitsi-meet
```

1. Define your host details in inventory.ini
1. Run playbook

```bash
\$ ansible-playbook -i inventory.ini main.yml
```
