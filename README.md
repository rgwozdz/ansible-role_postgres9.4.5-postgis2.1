# anisble-role_postgres9.4.5-postgis2.1
Ansible role for installation of PostgreSQL 9.4.5 and PostGIS 2.1 on Ubuntu 14.04

###Variables
|variable|required|default|description|
|---|---|---|---|
|postgres_user_password|no||password to set for postgres user|
|pg_hba_additions|no||any trusted connections to add in pg_hba.conf file|
|pg_listen_all|no| False| add listen_addresses="*"  to postgresql.conf?|

  
<br />

###Usage

1) Add this repo to your the `roles` directory of your Ansible directory.  
2) Set variables in your playbook or externally included variables file accordingly.  
3) Assuming the directory that this repo's contents are in is named `anisble-role_postgres9.4.5-postgis2.1`, the roles definition in your playbook should look something like this:  
  
    roles:
     - anisble-role_postgres9.4.5-postgis2.1

4) Run your playbook.


