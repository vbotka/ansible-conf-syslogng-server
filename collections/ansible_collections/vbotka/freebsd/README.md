# Ansible collection vbotka.freebsd (limited)

[![license](https://img.shields.io/badge/license-BSD-red.svg)](https://www.freebsd.org/doc/en/articles/bsdl-gpl/article.html)
[![GitHub tag](https://img.shields.io/github/v/tag/vbotka/ansible-collection-freebsd)](https://github.com/vbotka/ansible-collection-freebsd/tags)


## Supported ansible-pull repos

This limited collection supports:

* [ansible-conf-syslogng-client](https://github.com/vbotka/ansible-conf-syslogng-client)
* [ansible-conf-syslogng-server](https://github.com/vbotka/ansible-conf-syslogng-server)


## Included content

This collection is shipped with

plugins:

* [module vbotka.freebsd.service](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/module/service/) - Control or list system services.
* [inventory vbotka.freebsd.iocage](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/inventory/iocage/) - iocage inventory source.
* [filter vbotka.freebsd.iocage](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/filter/iocage/) - Parse iocage lists.
* [connection vbotka.freebsd.jailexec](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/connection/jailexec/) - Connect jails without SSH.

roles:

* [role vbotka.freebsd.lib](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/role/lib/) - Library of tasks.
* [role vbotka.freebsd.postinstall](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd/content/role/postinstall/) - Postinstall configuration.

various playbooks.


## Documentation of the full version

[ansible-collection-freebsd.readthedocs.io](https://ansible-collection-freebsd.readthedocs.io)


## Release Notes

See [changelog](https://github.com/vbotka/ansible-collection-freebsd/blob/master/changelogs/CHANGELOG.md).


## License

* This collection is primarily licensed and distributed as a whole under

  **BSD 2-Clause "Simplified" License**

  SPDX-License-Identifier: [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)

* The inventory plugin vbotka.freebsd.iocage is licensed and distributed as

  **GNU General Public License v3.0 or later**

  SPDX-License-Identifier: [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)


## Author

[Vladimir Botka](https://botka.info)
