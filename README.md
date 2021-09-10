# Cardano node setup playbooks

A list of playbooks required to setup a secure cardano node on Ubuntu 20.4 (LTS).

## How to setup

1. Make sure ansible is setup and your have your desired server(s) in the list of hosts
2. For each playbook, copy `vars/default-example.yml` to `vars/default.yml` and replace with your values (this file should be ignored by git)
3. Run playbooks