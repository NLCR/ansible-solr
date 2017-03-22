Role Name
=========

A brief description of the role goes here.

Requirements
------------

NLCR.java-oracle

Role Variables
--------------

```
defaults/main.yml
solr_url: https://archive.apache.org/dist/lucene/solr/6.4.2/solr-6.4.2.tgz
solr_version: 6.4.2
solr_path: '/opt/solr-{{ solr_version }}'
```
i will uncomment these vars in tasks/main.yml in a future
```
#    -i {{ solr_install_dir }}
#    -d {{ solr_home }}
#    -u {{ solr_user }}
#    -s {{ solr_service_name }}
#    -p {{ solr_port }}
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
