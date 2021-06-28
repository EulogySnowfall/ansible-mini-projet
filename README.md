# webapp-ansible-apache Role

## Copy Role

```bash
# Take project
git clone https://github.com/EulogySnowfall/ansible-mini-projet.git
cd ansible-mini-projet
# Copy roles
ansible-galaxy install -r roles/requirements.yml
# Test localhsot
cd roles/tests
ansible-playbook -i hosts.yml --ask-become-pass main.yml
cd ../..
# Validate hosts IP in hosts.yml 
# Install in second nodes
ansible-playbook -i hosts.yml main.yml
```