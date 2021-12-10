# ansible_examples

#Run the ansible books as below:

#For single host

ansible-playbook loop_port_check_multi_task.yml -i 192.168.0.112,

#For all hosts in the hosts file

ansible-playbook loop_port_check_multi_task.yml -i hosts
