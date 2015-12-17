Role Name
=========

Ansible-galaxy role for installing Drush, a command line shell and scripting interface for Drupal.


Role Variables
--------------

Default variables: (see default/main.yml)
  
  `memory_limit: 512M`
  `destination_path: /usr/local/bin/drush`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sparkfabrik.drush, memory_limit: 512M, destination_path : /usr/local/bin/drush }

License
-------

BSD

