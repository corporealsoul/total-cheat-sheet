Ansible Cheat Sheet

### Inventory:
`-i [inventory-file]`: Specify an inventory file (default is /etc/ansible/hosts).

`ansible-inventory --list`: List all hosts in the inventory.

`ansible-inventory --become`: List all hosts that the current user can become on.

`ansible-inventory --groups`: List all groups in the inventory.

`ansible-inventory --add <host>`: Add a new host to the inventory.

`ansible-inventory --remove <host>`: Remove a host from the inventory.


### Ad-Hoc Commands:
`ansible [target] -m [module] -a "[module-arguments]"`: Run ad-hoc commands on specified targets.


### Playbooks:
`ansible-playbook [playbook.yml]`: Run an Ansible playbook.


### Inventory Groups:
`[group-name]`: Target a specific group in the inventory.

`all`: Target all hosts in the inventory.


### Modules:
Common Modules: `ping, shell, copy, file, service, apt, yum, package, user, lineinfile,` and more.

Use `-m` option with ad-hoc commands and tasks in playbooks.


### Variables:
`ansible [target] -e "var_name=var_value"`: Set variables on the command line.

Use variables in playbooks and templates.


### Conditionals:
Use when to add conditions in tasks based on variable values.


### Loops:
Use `with_items` to loop over lists in playbooks.


### Roles:
Organize tasks, variables, and files into reusable roles.

`ansible-galaxy init [role-name]` to create a new role.


### Handlers:
Define tasks to be triggered by events in playbooks.


### Facts:
`ansible [target] -m setup`: Display facts about the target machine.


### Register Output:
Capture the output of a task with register and use it in subsequent tasks.


### Vault:
Encrypt sensitive data using ansible-vault.


### Tags:
Apply tags to tasks and run only specific tagged tasks.


### Vault Password File:
Use `--vault-password-file` to specify a file containing the vault password.


### SSH Keys:
Use `--private-key` to specify an SSH key for authentication.


### Becoming Another User:
Use `--become or --become-user` to run tasks as another user (sudo).


### Ad-Hoc Examples:
`ansible all -m ping`: Test connectivity to all hosts.

`ansible web -m shell -a "uptime"`: Run a shell command on hosts in the "web" group.


### Playbook Examples:
See Ansible documentation for complete playbook examples for various use cases.


### Other Useful Commands
`ansible-vault` - Encrypt and decrypt Ansible variables.

`ansible-galaxy` - Manage Ansible roles and collections.

`ansible-doc` - Generate documentation for Ansible modules and roles.

<br>
