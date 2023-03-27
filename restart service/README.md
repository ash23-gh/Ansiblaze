# Ansible Playbook for Service Restart

This Ansible playbook provides a simple way to restart any service on your remote machine. The playbook uses systemd-udevd.service as an example service, but you can easily edit the service name to restart a different service on all hosts in your inventory file.

The playbook also checks the status of the service after the restart and prints the output for confirmation.
