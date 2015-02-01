Role Name
=========

Install and configure php for different versions (5.5 or 5.6).

Role Variables
--------------

    # Php conf
    lwiesel_php_version: 5.5
    lwiesel_php_conf_template: cli.ini.j2
    
    # Modules
    lwiesel_php_modules: []
    lwiesel_php_modules_available:
      - apcu
      - curl
      - enchant
      - gd
      - gearman
      - geoip
      - gmp
      - http
      - imagick
      - imap
      - interbase
      - intl
      - ldap
      - mcrypt
      - memcache
      - memcached
      - mongo
      - mysqlnd
      - odbc
      - pinba
      - pgsql
      - pspell
      - readline
      - recode
      - redis
      - snmp
      - spplus
      - sqlite
      - ssh2
      - sybase
      - tidy
      - xcache
      - xmlrpc
      - xsl

Example Playbook
----------------

The role can be used like this:

    roles:
        - { role: lwiesel.php, tags: php }

License
-------

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
