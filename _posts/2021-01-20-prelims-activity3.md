---
layout: post
categories: activity prelim
title: Activity 3 - Ansible Basics
permalink: /prelim/activity3
---
# Activity 3 - Prelims

## Tasks
1.) Fork the instructor repository and clone the repository.

2.) Create a new branch called "activity3" and checkout in that branch.

3.) Create a directory with your username as its name and go inside of it, and create a directory called "activity3" and go inside it.

4.) Install Ansible via apk in your Alpine VM.

5.) To check if you installed Ansible correctly check the python version it in Ansible version command would reflect python 3.

6.) First, create a configuration file named "ansible.cfg", Ansible checks per-directory thus you can have multiple configurations in a system depending on your configuration file in the current directory.

7.) Next, populate the ansible.cfg file with basic information such as inventory, host verification, and your default remote user.

8.) Next, create your first inventory file with Ubuntu IP on it.

9.) Then try to connect using "ping" module via adhoc command

10.) Now use "shell" module to check the user via bash commands. (check for the user, hostname, and id)

11.) And we can use the "copy" module to create a file with a certain file with the content or copy from your local VM to your remote VM.

12.) For more modules, you can check this link of the module index.

13.) You can also check the description of the module using ansible-doc 

14.) Also, you can group your inventory via the grouping feature of Ansible.

15.) Add commit push and create a PR.


## Output
<p> <a href="https://github.com/jesmatienzo-tip/sysad2-12021/tree/activity3"> Activity 3 - Ansible Basics </a> </p>

```
activity 3
.
├── README.md
└── jesmatienzo-tip
    └── activity3
        ├── ansible.cfg
        └── inventory

2 directories, 3 files
```




