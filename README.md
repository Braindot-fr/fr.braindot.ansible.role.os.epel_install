<!--
 File              : README.md
 License           : AGPL-3.0-or-later
 Author            : Pierre 'McFly' Marty <pmarty@linagora.com>
 Date              : 26.11.2024
 Last Modified Date: 26.11.2024
 Last Modified By  : Pierre 'McFly' Marty <pmarty@linagora.com>
-->

# EPEL Install

This role simply setup EPEL Repository following the official
[Fedora EPEL: Getting Started](https://docs.fedoraproject.org/en-US/epel/getting-started/)

## Usage

```yaml
- hosts: servers

  roles:
    - when: braindot_epel_installation_enabled | bool
      role: galaxy/fr.braindot.ansible.role.os.epel_install
```

## Support And Contributing

This role is open to contribution! Feel free to open any Issue or Merge Request!

## Authors and acknowledgment

### Maintainers

- Pierre 'McFly' Marty <paq.marty@gmail.com>

## License

    EPEL Install - A little Ansible role helper for EPEL installation
    Copyright (C) 2024  Pierre 'McFly' Marty <paq.marty@gmail.com>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.


<!-- vim: set ft=markdown fenc=utf-8 spell spl=en tw=80 cc=80 et ts=2: -->
