# New Server

This role set up all administrations and security rules on new server joining the enveronment.

## Requirements

No requirements at time.

## Role Variables

Role variables are set in the `LAB-CHATGPT/roles/new-server/vars/main.yml` file.

- administrator_group_name : Enter the name of your administrator group in the server.

## Dependencies

No Dependencies at time.

## Example Playbook

- name: 01-add_new_server.yml
  hosts: all
  become: true
  gather_facts: true
  roles:
  - new-server

## License

No license.

## Author Information

Florian BOURDON - 2025
