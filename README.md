# job_ibm_test_webserver

=========

## Brief

This role is intended to build an nginx web server for test purposes

## Steps:

-----------------------------

##### Work to do:



----------------------------

## Requirements
------------

All dependencies will appear on requirements.yml file

## Role Variables
--------------

## How it works:
-------------
### vars/apps






-------------------------------------------------------------------

### tasks/task-templates

In order to

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost

      pre_tasks:
         - raw:  ansible-galaxy collection install -r requirements.yml
         - raw:  ansible-galaxy role install -r requirements.yml

      vars:
        #Vars that need to be defined on command line as --extra-vars
        #var to chose vars/apps file
        app_name:
        app_env:
        config_name:

      tasks:
        - name: Including role to test
          include_role:
            name: '../job_aurubis-helm-upgrade'


License
-------

BSD

Author Information
------------------
Made by @sergi-canas
