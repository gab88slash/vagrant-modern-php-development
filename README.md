# Modern Php development

This is the first release by using of ansible galaxy for requirements and geerlinguy roles for configuration plus other few stuffs.

## Requirements

Ansible 2+
Vagrant

## How to use it

    ansible-galaxy install -r requirements.yml
    
    vagrant up
    
    

## TODO:

- I'd like to move on a galaxy free playbook.
- I'd like to have a better use of variables.
- I'd like to move to a not `vagrant provision` solution
- I'd like to have a deploy playbook
