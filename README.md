# leppv_ansible

An ansible playbook to get you a lepp stack + varnish running in a few minutes on a CentOS 7 machine.

# Requirements:
CentOS 7 up and running  
Your ssh public key must be on the server  
Ansible installed  

## You may want to:
Place your **server ip address** inside the **inventory** file.  
Change variable values inside the **vars** directory. (especifically **application_path**, **permissions_postgres_pg_hba**, **nginx_server_name_ip** and **database_name**)  
Place your sql script inside the file **templates/db_file.sql.j2**  


