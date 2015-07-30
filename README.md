Role Name
=========

Installs PHPIPAM http://phpipam.net/

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

````
patch_discovery: true  #defines if current discovery functionality should be patched
patch_email: true  #defines if current email test functionality should be patched
phpipam_base: /phpipam/
phpipam_db_host: localhost  #define db host
phpipam_db_name: phpipam  #define db name
phpipam_db_pass: []  #define db password or define in group_vars/group
phpipam_db_user: []  #define db user or define in group_vars/group
phpipam_download: http://sourceforge.net/projects/phpipam/files/latest/download
phpipam_primary: false  #define if using a clustered mariadb mysql
phpipam_root: '{{ web_root }}/phpipam'
web_root: /var/www/html
````

Dependencies
------------

mrlesmithjr.apache2
mrlesmithjr.mariadb-mysql


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - { role: mrlesmithjr.apache2 }
        - { role: mrlesmithjr.mariadb-mysql }
        - { role: mrlesmithjr.phpipam }

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
