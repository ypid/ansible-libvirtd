Introduction
============

``debops.libvirtd`` Ansible role manages the `libvirtd`_ daemon on
a virtualization host (server side). It will automatically install QEMU KVM
support on any host that is not a KVM guest, to allow for easy deployment of
KVM virtual machines.

Configuration of ``libvirtd`` instance (local or remote) can be performed using
``debops.libvirt`` role, which uses ``libvirt`` API to manage the server.

.. _libvirtd: http://libvirt.org/

Installation
~~~~~~~~~~~~

This role requires at least Ansible ``v1.8.0``. To install it, run::

    ansible-galaxy install debops.libvirtd

..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:
