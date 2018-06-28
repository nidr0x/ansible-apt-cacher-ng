# Ansible Role: ansible-apt-cacher-ng

This role installs apt-cacher-ng (apt proxy) to cache the downloaded packages locally and serve to a local network or on the internet.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-role-apt-cacher-ng
```

## License

MIT / BSD


