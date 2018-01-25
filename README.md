willwh.goldfish
=========

A role to deploy [Caiyeon/goldfish](https://github.com/Caiyeon/goldfish) as a service using systemd.

Requirements
------------

You must have the following installed on the target hosts:

 - [Go](https://golang.org/doc/install)

Role Variables
--------------

See `defaults/main.yml`


Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: willwh.goldfish }
```

License
-------

BSD
