# ansible

### Playbook
ansible-playbook playbooks/playbook.yml -i $ENVIRONMENT_HOST_FILE

### limit playbook to a host/hosts
ansible-playbook playbooks/playbook.yml --limit $HOST

### user
pass user: --user=$USER

### start playbook at specific task:
--start-at-task=$TASK_NAME
