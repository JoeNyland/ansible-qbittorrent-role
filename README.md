joenyland.qbittorrent
=====================

[![CI](https://github.com/JoeNyland/ansible-qbittorrent-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-qbittorrent-role/actions/workflows/ci.yml)

Installs [qBittorrent](https://www.qbittorrent.org/).

Requirements
------------

None.

Role Variables
--------------

### `qbittorrent_service_enabled`

Should the qbittorrent service start at boot?

### `qbittorrent_service_state`

What state should the qbittorrent service be in? e.g. started/stopped

### `qbittorrent_users`

Which users should be added to the qBittorrent group (created by this role), allowing read/write access to the files qBittorrent downloads.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - joenyland.qbittorrent
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
