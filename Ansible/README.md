# Ansible

## What is Ansible?
Ansible is an open-source automation tool for configuration management, application deployment, and task automation.

## Architecture
- Controller Node: Runs Ansible commands and playbooks.
- Managed Nodes: Target systems managed over SSH.
- Inventory: List of managed nodes.
- Modules: Units of work for tasks.

## Example Playbook
```yaml
- name: Install Nginx
  hosts: webservers
  become: yes
  tasks:
    - name: Install nginx
      apt:
        name: nginx
        state: present
```
