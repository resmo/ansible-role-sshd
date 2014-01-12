# Ansible SSHd role
An ansible role for installing sshd.

[![Build Status](https://travis-ci.org/resmo/ansible-role-sshd.png?branch=master)](https://travis-ci.org/resmo/ansible-role-sshd)

## Usage

    ---
    # group_vars/all
    sshd_permit_root_login: without-password

Example playbook:

    - hosts: all
      remote_user: root
      roles:
      - resmo.sshd

## Homepage:

https://github.com/resmo/ansible-role-sshd
