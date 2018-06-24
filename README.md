# Backup-Mysql-Ansible
Backup Mysql With Ansible

this ansible play it will exclude mysql databases and only backup the databases that matter for us 
```bash
ansible-playbook playbook.yml --extra-vars "host=localhost user=username pass=password db_host=127.0.0.1 dump_dir=~/backup"
```
