ansible-role-playframework
==========================

Ansible role to manage Play Framework

Example :
```
 - hosts: all
   roles:
    - role: playframework
       playframework_apps:
        - { name: my_play_app, path: "/home/foo/app/my_play_app" }
        - { name: my_play_app2, port: 9001, path: "/tmp/my_play_app2", options: "-DapplyEvolutions.default=true" }
```