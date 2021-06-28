# webapp-ansible-apache Role

## Copy Role

```bash
# Take project
git clone https://github.com/EulogySnowfall/ansible-mini-projet.git
cd ansible-mini-projet
# Copy roles
ansible-galaxy install -r roles/requirements.yml
cd test
ansible-playbook -i hosts.yml main.yml
# Validate hosts IP 

```