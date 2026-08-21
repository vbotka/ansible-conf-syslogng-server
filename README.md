# ansible-conf-syslogng-server

Ansible configuration for ansible-init

This repository is used by the service **ansible_init**

The content of the below files is sent to **/var/log/remote/${HOST}/${YEAR}_${MONTH}_${DAY}.log**

* /var/log/ansible.log
* /var/log/daemon.log
* /var/log/messages

The collection in this repo is limited to support this use case.

## See

* ansible collection [vbotka.freebsd](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd)
* example 526. [Log server and clients](https://ansible-collection-freebsd.readthedocs.io/en/latest/examples/526/example.html)
