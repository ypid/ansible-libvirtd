## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) libvirtd

[![Travis CI](http://img.shields.io/travis/debops/ansible-libvirtd.svg?style=flat)](http://travis-ci.org/debops/ansible-libvirtd) [![test-suite](http://img.shields.io/badge/test--suite-ansible--libvirtd-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-libvirtd/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.libvirtd-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/4548)

`debops.libvirtd` Ansible role manages the [libvirtd](http://libvirt.org/)
daemon on a virtualization host (server side). It will automatically
install QEMU KVM support on any host that is not a KVM guest, to allow for
easy deployment of KVM virtual machines.

Configuration of `libvirtd` instance (local or remote) can be performed using
`debops.libvirt` role, which uses `libvirt` API to manage the server.

### Installation

This role requires at least Ansible `v1.8.0`. To install it, run:

    ansible-galaxy install debops.libvirtd

### Documentation

More information about `debops.libvirtd` can be found in the
[official debops.libvirtd documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-libvirtd/docs/).


### Role dependencies

- `debops.ferm`
- `debops.apt_preferences`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`libvirtd` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
