Role Name
=========

Installs PHPIPAM http://phpipam.net/

Requirements
------------

Default PHPIPAM login is Admin/ipamadmin

Role Variables
--------------

````
patch_discovery: true  #defines if current discovery functionality should be patched
patch_email: true  #defines if current email test functionality should be patched
phpipam_base: /phpipam/
phpipam_db_cluster: false #defines if backend db for pdns is clustered...define here or in group_vars/group
phpipam_db_host: localhost  #define db host
phpipam_db_name: phpipam  #define db name
phpipam_db_pass: phpipam  #define db password or define in group_vars/group
phpipam_db_user: phpipam  #define db user or define in group_vars/group
phpipam_download: http://sourceforge.net/projects/phpipam/files/latest/download
phpipam_primary: false  #define if using a clustered mariadb mysql and define a single node as primary in host_vars/host
phpipam_root: '{{ web_root }}/phpipam'  #defines the root folder of where phpipam is to be installed
phpipam_url: 'ipam.{{ pri_domain_name }}'  #defines the phpipam url to configure apache2 for if configured for url rewrite
phpipam_url_rewrite: false  #defines if apache2 should be configured for host headers for phpipam...will be configured as phpipam_url
pri_domain_name: example.org  #defines the primary domain name...define here or globally in group_vars/all
web_root: /var/www/html
````

Dependencies
------------
````
mrlesmithjr.apache2
mrlesmithjr.mariadb-mysql
````

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
