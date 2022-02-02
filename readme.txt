readme

MySQL 5.7 on Amazon Linux 2

warning:

```
[DEPRECATION WARNING]: Invoking "yum" only once while using a loop via squash_actions is deprecated. Instead of using a loop to supply multiple items and
specifying `name: "{{item}}"`, please use `name: ['yum-utils', 'MySQL-python', 'mysql-community-server']` and remove the loop. This feature will be removed
from ansible-base in version 2.11. Deprecation warnings can be disabled by setting deprecation_warnings=False in ansible.cfg.
```

references:

http://www.wiivil.com/installing-mysql-on-centos-7-server-using-ansible/
https://titanwolf.org/Network/Articles/Article?AID=5ceea441-0736-4d74-b150-6b09cb5df9ea
https://github.com/inaro/ansible_lamp/blob/master/provision/mysql.yml
https://the-d2.com/install-mysql-5-7-on-centos-via-ansible-playbook-yml/
https://dev.mysql.com/doc/refman/5.7/en/linux-installation-yum-repo.html
https://tecadmin.net/install-mysql-5-7-centos-rhel/
https://github.com/geerlingguy/ansible-role-mysql/blob/86ffba892e1553b7e6f042ec007eef25daa8f5db/tasks/secure-installation.yml
https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html
https://docs.ansible.com/ansible/latest/collections/ansible/builtin/yum_module.html
