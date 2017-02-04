[![Build Status](https://travis-ci.org/wtanaka/ansible-role-hub.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-hub)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-hub.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-hub)

wtanaka.hub
===========

This ansible role installs hub, a command line wrapper for git with
integrations into the GitHub API

Example Playbook
----------------

    - hosts: all
      roles:
         - role: wtanaka.hub
           hub_version: "2.2.9"
           hub_bin_dir: /usr/local/bin

License
-------

GPLv2
