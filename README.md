Wordpress Role
=========

A brief description of the role goes here.

Requirements
------------
* Ubuntu / Centos7
* omarpiotr.docker_role : for installing all docker dans docker-py
* set ssh_connexion as default
* become: true

Role Variables
--------------

* network_name: network name 
* wordpress_container: wordpress container name
* wordpress_data : wordpress volume name
* mysql_container: mysql container name
* mysql_root_password
* mysql_user
* mysql_password
* mysql_databse : database name for wordpress
* mysql_data: mysql volume name

Dependencies
------------

omarpiotr.docker_role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
hosts: all
  become: true
  roles:
    - wordpress_role
```

License
-------

BSD

