logwatch
========

Configures logwatch reports to be weekly and where to send them to.

Role Variables
--------------

| Name                    | Comment                                         | Default value |
|-------------------------|-------------------------------------------------|---------------|
| logwatch_report_address | The email address logwatch sends the reports to | ``            |

Example Playbook
----------------
```yaml
- name: Configure logwatch reports
  hosts: all
  collections:
    - oxivanisher.linux_base
  roles:
    - role: oxivanisher.linux_base.logwatch
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
