# Terraform
This is Terraform Repository

## Azure
provider : Version3.92.0

### azurerm_linux_virtual_machine
### Required
* admin_username
* location
* name
* network_interface_ids
* os_disk
* resource_group_name
* size

### optinal
* admin_password
When an admin_password is specified disable_password_authentication must be set to false.
One of either admin_password or admin_ssh_key must be specified.
* admin_ssh_key
One of either admin_password or admin_ssh_key must be specified.
* computer_name
* custom_data
* disable_password_authentication
When an admin_password is specified disable_password_authentication
* user_data
* zone
