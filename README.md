Kibana
=========

Simple download binaries from official website and install Kibana.

Role Variables
--------------
There is only two variables that you can redefine in your playbook.
```yaml
kibana_version: "7.10.1" # Use for download only this version of Kibana
kibana_home: "/opt/kibana/{{ kibana_version }}" # Use for unpackage distro and create ES_HOME variable
kibana_package: "kibana-7.10.1-linux-x86_64.tar.gz" # Use for set local package name
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  roles:
      - kibana
```

License
-------

BSD

Author Information
------------------

Netology Students
