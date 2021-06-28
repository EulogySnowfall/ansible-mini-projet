# webapp-ansible-apache Role

## Copy Role

```bash
# Pass admin
sudo su admin -
# Take project
git clone https://github.com/EulogySnowfall/ansible-mini-projet.git
cd ansible-mini-projet
# Copy roles
ansible-galaxy install -r roles/requirements.yml

# Test localhost (not work on eazytraining VM (no systemctl))
# cd roles/tests
# ansible-playbook -i hosts.yml --ask-become-pass main.yml
# cd ../..


# Validate hosts IP in hosts.yml 
# Install in second nodes

# For demo, vault_pass = admin 
ansible-playbook app_deploy.yml
```

## Remove roles

```bash
ansible-galaxy remove ansible-mini-projet
cd ~/
rm -rf ./ansible-mini-project
```