This repository is used to store the various playbooks and software bundles used for Platform Provisioning using Ansible Framework

Examples of Platforms Provisioned include
1. Drupal
2. WordPress
3. Apache + Tomcat + mod-jk
4. Apache + JBOSS + mod-jk

Ansible Tower was used to run the playbooks (jobs) - https://ansibletower.mycompanydomain.com

The repository structure is as below

<pre>
├── apache-mod-jk-jboss.yml
├── apache-mod-jk-tomcat.yml
├── apache-php.yml
├── apache.yml
├── defaults
│   └── main.yml
├── drupal.yml
├── group_vars
│   └── all
├── hosts
├── java.yml
├── jboss.yml
├── login_check.yml
├── memcache.yml
├── mod-jk.yml
├── mysql.yml
├── nginx.yml
├── oneclickinstall.yml
├── php.yml
├── README.md
├── roles
│   ├── apache
│   ├── cleanup
│   ├── drupal
│   ├── java
│   ├── jboss
│   ├── memcache
│   ├── mod-jk
│   ├── mysql
│   ├── nginx
│   ├── php
│   ├── rollback
│   ├── tomcat
│   └── virtualbox
├── rollback.yml
├── tomcat.yml
└── virtualbox.yml
</pre>
...
