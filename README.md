Overview
========

This is a simple [Vagrant](https://www.vagrantup.com/) deployment for a basic Ubuntu (vivid64) image. It also includes several ansible roles and ansible playbooks to quickly provision a few environments I may work with.

All these ansible roles are intended to be used on a vagrant image and are not ready for production.

It includes a small provisioning script using[ansible](http://www.ansible.com/home) and includes a useful script BAT file for windows users that allows the image to build itself from an ansible script even on windows. Credit to GitHub user geerlingguy for[JJG-Ansible-Windows](https://github.com/geerlingguy/JJG-Ansible-Windows)

Usage
=====

Once you have Vagrant installed just check this project out and run

`Vagrant up`

If you need to reprovision just

`Vagrant provision`
