# Ansible looks for roles in the following directories by default:
Current project directory
~/.ansible/roles
/etc/ansible/roles
/usr/share/ansible/roles

# create ansible role directory structure
ansible-galaxy init role_name


tasks - contains the main list of tasks to be executed by the role.
handlers - contains handlers, which may be used by this role or even anywhere outside this role.
defaults - default variables for the role.
vars - other variables for the role.
files - contains files which can be deployed via this role.
templates - contains templates which can be deployed via this role.
meta - defines some meta data for this role. See below for more details.

# Use roles via the roles: option in a playbook

