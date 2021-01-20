---
layout: post
categories: activity midterm
title: Activity 6 - Install, configure, and manage enterprise services via Ansible
permalink: /midterm/activity6
---
# Activity 6 - Midterms

## Tasks
1.) Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2.) Clone your newly forked repository. 

3.) Make a new branch named "activity6" from master branch using git branch activity6 and git checkout activity6

4.) Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5.) Create a playbook that installs dhcpd, bind9, vsftpd, samba, httpd, mariadb in both Ubuntu and Centos (use Roles to optimize the playbook)

6.) Create different plays in installing per service and identify it as a group in Inventory file.

7.) add,commit and push it to your activity6 branch

8.) Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity6 branch of your forked repository.

## Output
<p> <a href="https://github.com/jesmatienzo-tip/sysad2-12021/tree/activity6"> Activity 6 - Implement Ansible roles in playbooks </a> </p>

```
activity 6
.
├── README.md
└── jesmatienzo-tip
    └── activity6
        ├── ansible.cfg
        ├── inventory
        ├── playbook_activity6.yaml
        └── roles
            ├── bind9_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── bind9_ubuntu_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── dhcpd_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── dhcpd_ubuntu_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── httpd_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── httpd_ubuntu_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── mariadb_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── mariadb_ubuntu_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── samba_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── samba_ubuntu_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            ├── vsftpd_centos_install
            │   ├── README.md
            │   ├── defaults
            │   │   └── main.yml
            │   ├── handlers
            │   │   └── main.yml
            │   ├── meta
            │   │   └── main.yml
            │   ├── tasks
            │   │   └── main.yml
            │   ├── tests
            │   │   ├── inventory
            │   │   └── test.yml
            │   └── vars
            │       └── main.yml
            └── vsftpd_ubuntu_install
                ├── README.md
                ├── defaults
                │   └── main.yml
                ├── handlers
                │   └── main.yml
                ├── meta
                │   └── main.yml
                ├── tasks
                │   └── main.yml
                ├── tests
                │   ├── inventory
                │   └── test.yml
                └── vars
                    └── main.yml

87 directories, 100 files
```




