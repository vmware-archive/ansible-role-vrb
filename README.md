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
 
Copyright 2015 VMware, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

