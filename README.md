# Ansible Role: NTP

[![Build Status](https://travis-ci.org/cecepm/ansible-role-ntp.svg?branch=master)](https://travis-ci.org/cecepm/ansible-role-ntp)

Set timezone, add time synchronization with ntp server.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    ntp_timezone: "Asia/Jakarta"

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
         - cecepm.ntp

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Cecep Mahbub](http://ngadimin.org/).
