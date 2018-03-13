# Ansible-Hardening
Roles ansible for host hardening

First execute execute:
`ansible-playbook -i inventory.ini start.yml --ask-user-pass`

After ssh-key pass:
`ansible-playbook -i inventory.ini start.yml`

For execute an single role:
`ansible-playbook -i inventory.ini start.yml --tags <role_name>`
