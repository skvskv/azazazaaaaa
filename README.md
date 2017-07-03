# azazazaaaaa

Run with e.g. 
``` 
ansible -i env-specific-inventories/cumulative.ini aws -m ping
ansible -i env-specific-inventories/cumulative.ini aws -a /bin/date
ansible-playbook -i env-specific-inventories/cumulative.ini --syntax-check playbooks/apt/apt-prepare.yml
ansible-playbook -i env-specific-inventories/cumulative.ini playbooks/apt/apt-prepare.yml
```

