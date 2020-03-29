ansible-role-openwrt-base
=========================

Install basic OpenWrt packages useful for routine operations.

The packages installed are:

* bind-dig
* coreutils-base64
* coreutils-realpath
* coreutils-sha1sum
* openssh-sftp-server
* rsync

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

* `gekmihesg.openwrt`

Example Playbook
----------------

```yml
- hosts: openwrt
  remote_user: root
  gather_facts: no
  roles:
  - bit_kitchen.openwrt_base
```

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
