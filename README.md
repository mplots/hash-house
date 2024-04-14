# hash-house

## Bootsrap
ansible-playbook -i inventory.yml playbook.yml -t bootstrap

## Ger all facts
ansible -u ubuntu -i inventory.yml hisenberg -m setup