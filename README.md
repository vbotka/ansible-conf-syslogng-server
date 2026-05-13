# ansible-pull repo for syslog-ng server.

This repository is used by **ansible-pull** run from the script **post_install.sh** in the iocage plugin [ansible-pull-syslogng-server](https://github.com/vbotka/iocage-plugins).

The content of the below files is sent to **/var/log/remote/${HOST}/${YEAR}_${MONTH}_${DAY}.log**

* /var/log/ansible.log
* /var/log/daemon.log
* /var/log/messages

The collection in this repo is limited to support this use case.

## See

* iocage plugin [ansible-pull-syslogng-server](https://github.com/vbotka/iocage-plugins)
* example [Iocage plugins ansible-pull-syslogng-*](https://ansible-collection-freebsd.readthedocs.io/en/latest/examples/521/example.html)
* collection [vbotka.freebsd](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd)
