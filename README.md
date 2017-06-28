# Ansible Role: Fedora Firewall

An Ansible role that ensures that firewall on Fedora is installed, running and accepts only SSH traffic.

## Compatibility

This playbook has been tested against Fedora 25.

## Installation 

    ansible-galaxy install hekonsek:fedora-firewall,0.5

## Example Playbook

    - hosts: localhost
      roles:
        - { role: hekonsek.fedora-firewall,0.5 }

## License

Apache 2.0