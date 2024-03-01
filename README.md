# wsl-ansible

Ansible configuration that can be used with Ubuntu on WSL.

## Complete Workstation Setup

### Ansible Commands

#### Run this once after installing the OS

    sudo apt update && sudo apt install -y git ansible

#### Run this to apply the config to your workstation

    sudo ansible-pull -U https://github.com/lab1702/wsl-ansible.git

## Python

To set up a data science Python virtual environment, see [mkvenv](https://github.com/lab1702/mkvenv) for scripts.
