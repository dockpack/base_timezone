Role Name
========

base_timezone

Role Variables
--------------

```

# Default timezone.  Must be a valid tz database time zone.
timezone: UTC

```

Example Playbook
-------------------------

```

---
- name: Set timezone
  hosts: all
  become: true
  vars:
   timezone: America/New_York

  roles:
    - dockpack.base_timezone


```

License
-------

Apache 2.0

Author Information
------------------

Ryan Yates & Bas Meijer
