### Initialization:
`vagrant init [box-name]`: Create a new Vagrantfile using the specified base box.


### Basic Commands:
`vagrant up`: Start the Vagrant environment.

`vagrant halt`: Stop the running Vagrant environment.

`vagrant reload`: Reload the Vagrant environment.

`vagrant suspend`: Suspend the Vagrant environment.

`vagrant resume`: Resume a suspended Vagrant environment.

`vagrant destroy`: Destroy the Vagrant environment.


### SSH Access:
`vagrant ssh`: SSH into the default VM.

`vagrant ssh [vm-name]`: SSH into a specific VM (if you have multiple defined in your Vagrantfile).


### Box Commands:
`vagrant box list`: List all available Vagrant boxes.

`vagrant box add [box-name]`: Add a new box to your local box repository.

`vagrant box remove [box-name]`: Remove a box from the local repository.


### Status and Info:
`vagrant status`: Display the status of all VMs in the Vagrant environment.

`vagrant global-status`: Show detailed status information for all Vagrant environments.


### Provisioning:
`vagrant provision`: Rerun the provisioning scripts defined in your Vagrantfile.


### Plugin Management:
`vagrant plugin list`: List installed Vagrant plugins.

`vagrant plugin install [plugin-name]`: Install a Vagrant plugin.

`vagrant plugin uninstall [plugin-name]`: Uninstall a Vagrant plugin.


### Networking:
Modify the Vagrantfile to configure port forwarding, private networks, and more.

### Synced Folders:
Modify the Vagrantfile to configure synced folders between the host and guest.


### Snapshots (if using Vagrant with VirtualBox):
`vagrant snapshot save [snapshot-name]`: Create a snapshot of the current VM state.

`vagrant snapshot restore [snapshot-name]`: Restore a snapshot.

`PS D:\Server Snaps\The Architect> vagrant snapshot save '26 July 2023 23:18:47'`

`PS D:\Server Snaps\The Architect> vagrant snapshot restore '26 July 2023 23:18:47'`

`PS D:\Server Snaps\The Architect> vagrant snapshot delete '26 July 2023 23:18:47'`


### Vagrantfile Configuration:
Edit the Vagrantfile to customize VM settings, provisioners, and more.


### Box Providers:
You can specify different providers like VirtualBox, VMware, or AWS in the Vagrantfile.


### Multiple VMs:
You can define and manage multiple VMs within a single Vagrant environment.

<br>
