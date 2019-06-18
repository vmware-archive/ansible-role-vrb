# ansible-role-elasticsearch

Ansible playbook to automate installing and maintaining VMware VRealize BusinessStandard

## Requirements
Able to deploy VRealize Business Standard  Appliance usng ovf tool and vcenter. Currently VRealize Business Standard  Appliance is deployed into ESX cluster using vcenter parameters. Do we also need to support deployment of the VRealize Business Standard appliance into the host directly? 
Later support for VRealize Business Advanced will also be provided
## Role Variables


## playbook invoking the role
ansible/playbooks/supersddc/site_vra.yml
## tasks
vrb_ovadeploy.yml - used for deploying an appliance
Currently all these tasks are invoked from the front end  through tasks/main.yml based on ohe play  specified in the base.yml.j2 of supersddc gui 
# License and Copyright
 
Copyright 2015 VMware, Inc.  All rights reserved.

SPDX-License-Identifier: Apache-2.0 OR GPL-3.0-only

This code is Dual Licensed Apache-2.0 or GPLv3

