# zeek-ansible

[zeek IDS](https://github.com/zeek/zeek) on Debian 12.

This project is laid out to be used with my own [ansible-mock](https://signal.nih.earth/posts/ansible-mock/) and git submodule workflow.

To bring into a project:

```
git -C roles/ submodule add git@github.com:nihr43/zeek-ansible.git
```

To update:

```
git submodule update --recursive --remote
```

Required vars:

- zeek_interface
