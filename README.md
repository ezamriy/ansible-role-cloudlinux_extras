# cloudlinux_extras

An Ansible role that installs CloudLinux Extras repository on EL 5/6/7.


## Role Variables

Available variables and their default values are listed below:

* `cloudlinux_extras_enabled: yes` - enable or disable CloudLinux Extras
  repository.


## Example Playbook

```yaml
    ---
    - hosts: all
      roles:
        - { role: ezamriy.cloudlinux_extras, cloudlinux_extras_enabled: no }
```

## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
