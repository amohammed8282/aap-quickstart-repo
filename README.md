# AAP Quickstart Lab Repo

This repository is a tiny starter for Red Hat Ansible Automation Platform (AAP) labs.

## Structure
```
inventories/
  lab.yml
playbooks/
  ping.yml
  packages.yml
group_vars/
  rhel.yml        # optional shared vars for rhel group
```

## First run
1. Create a Project in AAP pointing to this repo.
2. Create an Inventory and import `inventories/lab.yml` or copy the structure.
3. Create a Machine Credential for your VMs.
4. Create a Job Template for `playbooks/ping.yml` and run it.
5. Create a Job Template for `playbooks/packages.yml` (with become) and run it.
