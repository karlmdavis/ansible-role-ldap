# Ansible LDAP Modules

![Travis CI Build Status](https://travis-ci.org/karlmdavis/ansible-role-ldap.svg)

This project provides a pair of [Ansible](http://www.ansible.com) modules for manipulating an LDAP directory. The [`ldap_entry`](./ldap-entry) module can be used to create/delete LDAP entries and the [`ldap_attr`](./ldap_attr) module can then be used to manage those entries' attributes.

Unless/until these modules makes their way upstream into Ansible, the documentation for them is only available embedded in their code (see the link for each, above).

These modules are published on [Ansible Galaxy](https://galaxy.ansible.com) here: TODO. They can be installed from there by TODO.

Requirements
------------

This role supports Ansible 2 and later. For the specific versions that it's tested against, see the values for "`ANSIBLE_VERSION`" towards the top of [.travis.yml](./.travis.yml).

License
-------

[BSD](./LICENSE) and public domain (as the changes exclusive to this fork were written by US federal government employees, partially during work hours).

Author Information
------------------

This fork was authored by Karl M. Davis (https://justdavis.com/karl/), but the vast bulk of the work originally came from [ansible-ldap](https://bitbucket.org/psagers/ansible-ldap) by Peter Sagerson.

