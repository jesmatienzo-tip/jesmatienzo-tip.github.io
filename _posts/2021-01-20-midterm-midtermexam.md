---
layout: post
categories: exam midterm
title: Midterm Exam
permalink: /midterm/midtermexam
---
# Midterm Exam

## Tasks
1.) Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2.) Clone your new repository in your VM https://github.com/< your username >/sysad2-12021.git

3.) Create a branch named "midterm-exam" and checkout in that branch. 

4.)  Create an Ansible playbook that does the following with an input of a config.yaml file and arranged Inventory file:

- Install and configure Elastic Stack in separate  hosts (Elastic Search, Kibana, Logstash)

- Install Nagios in one host

- Install Grafana,Prometheus and Influxdb in seperate hosts (Influxdb,Grafana,Prometheus)

- Install Lamp Stack in seperate hosts (Httpd + Php,Mariadb)

5.) push and commit your midterm-exam branch in the VM (no need for ansible.cfg upon pushing)

6.) request a pull request from that branch in GitHub

7.) For your midterm exam to be counted, please paste your repository link as an answer in this exam.

## Output
<p> <a href="https://github.com/jesmatienzo-tip/sysad2-12021/tree/midterm-exam"> Midterm Exam </a> </p>

```
midterm-exam
├── README.md
├── ansible.cfg
├── inventory
├── playbook_midterm.yaml
├── prometheus.service
└── roles
    ├── install_elasticsearch_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_grafana_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_httpd_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_kibana_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_logstash_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_mariadb_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_nagios_centos
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── install_prometheus_ubuntu
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    └── install_telegraf_ubuntu
        ├── README.md
        ├── defaults
        │   └── main.yml
        ├── files
        ├── handlers
        │   └── main.yml
        ├── meta
        │   └── main.yml
        ├── tasks
        │   └── main.yml
        ├── templates
        ├── tests
        │   ├── inventory
        │   └── test.yml
        └── vars
            └── main.yml

82 directories, 77 files
```




