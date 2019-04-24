Ansible Role: Vireo 3
=========

Installs and configures Vireo 3.x


Requirements
------------

TBD


Role Variables
--------------

TBD


Dependencies
------------

Ansible roles (or other means) that provide the following:
  - Java 1.5 or higher
    - e.g. https://github.com/dheles/java-ansible-role
  - PostgreSQL 8.4, 9.1 or higher
    - e.g. https://github.com/dheles/postgres-ansible-role  
  - Python 2.4 or higher
    - TODO. Most operating systems, including Centos 7, have python pre-installed
  - Play! framework 1.2.5 (but not 2.x)
    - e.g. https://github.com/dheles/play-ansible-role
  - Apache HTTPD server (optional)
    - e.g. https://github.com/dheles/apache-ansible-role
  - Shibboleth authentication system (optional)
    - e.g. https://github.com/dheles/apache-ansible-role


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: vireo }


License
-------

CC0


Author Information
------------------

Drew Heles
