# ansible-postgresql
# Install Ansible PostgreSQL Collection:
```
ansible-galaxy collection install community.postgresql
```

# Setup SSH Connection:
```
ssh-keygen -t rsa
ssh-copy-id -i ~/.ssh/id_rsa.pub user@ip-server
```

# Run:
```
ansible-playbook -i inventory.ini postgres.yml --ask-become-pass
```
