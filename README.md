Sudo
====

An ansible role to configure sudo.

NOTE: this role does NOT install sudo.

Requirements
------------

None

Role Variables
--------------

  - `sudo_defaults` (default: `[]`)
  - `sudo_sudoers` (default: `[]`)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: dochang.sudo
          sudo_sudoers:
            - '%sudo	ALL=(ALL:ALL) ALL'

License
-------

[MIT](https://dochang.mit-license.org/)

Author Information
------------------

Desmond O. Chang <dochang@gmail.com>
