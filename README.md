# open-vm-tools

Installationand confuguration of the open vmware tools

## Requirements

For Redat based OS **epel** is required, but I do not put in in depencency.

## Role Variables

NONE

##  Dependencies

NONE

## Example Playbook


    - hosts: servers
      roles:
      - role: 5ok.open_vm_tools
        when: "ansible_virtualization_type == 'VMware' and ansible_virtualization_role == 'guest'"

## License

BSD

## Author Information

Peter Hudec (@hudecof)
