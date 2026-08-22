# ansible-conf-syslogng-server

Second-stage Ansible configuration for FreeBSD ansible_init service.

Configure syslog-ng server. The content of the below files is sent to
**/var/log/remote/${HOST}/${YEAR}_${MONTH}_${DAY}.log**

* /var/log/ansible.log
* /var/log/daemon.log
* /var/log/messages

## See

* First-stage Ansible configuration for FreeBSD ansible_init service [ansible-conf-init](https://github.com/vbotka/ansible-conf-init/)
* Ansible collection [vbotka.freebsd](https://galaxy.ansible.com/ui/repo/published/vbotka/freebsd)
* Example 526. [Log server and clients (ansible_init)](https://ansible-collection-freebsd.readthedocs.io/en/latest/examples/526/example.html)
