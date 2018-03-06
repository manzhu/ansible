# ansible

step1 yml is used to init a standalone bigip

# ansible-playbook -i no, step1_f5_standalone_init.yml

step2 yml is used to setup HA cluster

# ansible-playbook -i no, step2_f5_ha_establish.yml
