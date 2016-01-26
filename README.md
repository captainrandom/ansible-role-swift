# ansible-role-swift
Ansible role to install Swift programming language in Ubuntu

[![Build Status](https://travis-ci.org/alexcoppe/ansible-role-swift.svg?branch=master)](https://travis-ci.org/alexcoppe/ansible-role-swift)


## Requirements

None


## Role Variables

The directory where files  are downloaded and temporary files are generated:

    swift_tmp_directory: /tmp

The directory in which swift will be intalled:

    swift_install_directory: ~/local


## Dependencies

None


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: alexcoppe.swift }


## License

WTFPL
