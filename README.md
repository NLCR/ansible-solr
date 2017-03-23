SOLR
=========

Simple for SOLR 6 installation

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

NLCR.java-oracle

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: NLCR.solr, solr_url: https://archive.apache.org/dist/lucene/solr/6.4.2/solr-6.4.2.tgz, solr_version: 6.4.2 }

License
-------

BSD

Author Information
------------------

Rudolf Kreibich
