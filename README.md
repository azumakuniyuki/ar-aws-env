Ansible Role: ar-aws-env
================================================================================

Install some packages and deploy some files on Amazon Linux 2

- Install aws-cli

Requirements
--------------------------------------------------------------------------------
No requiremetns.

Role Variables
--------------------------------------------------------------------------------
These variables are defined in `defaults/main.yml` file for being removed and
installed packages on each supported platform.

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - azumakuniyuki.ar-aws-env
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp/)
