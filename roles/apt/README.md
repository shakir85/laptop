# Role Name

This Ansible role automates the installation and configuration of APT packages on my Debian 12 based laptop.

## Requirements

On a fresh Debian 12 installation, the `add-apt-repository` command didn't work, showing a Python traceback. After some googling, I found that it needed the 'python3-launchpadlib' dependency. I included installing this dependency as the initial task in the role.

## Role Variables

Role variables include the names of packages, GPG key links, and application repositories.

## License

BSD
