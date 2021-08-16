# Setup SCM Class

In azure run following in the azure-cli

```bash
cd clouddrive

git clone https://github.com/jesperberth/scmclass_setup/

cd automationclass_setup

cd azure

ansible-galaxy install -r requirements.yml

ansible-playbook 00_azure_class_setup.yml
```

```bash

az ad sp create-for-rbac --name ansibleuser --role Contributor



```
