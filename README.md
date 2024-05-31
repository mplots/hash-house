# hash-house

## Bootsrap
ansible-playbook -i inventory.yml playbook.yml -t bootstrap --extra-vars `ansible_sudo_pass=yourPasswordHere`

## Get all facts
ansible -u ubuntu -i inventory.yml hisenberg -m setup


--extra-vars `ansible_sudo_pass=yourPasswordHere`