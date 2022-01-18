# Overview

A playbook to mix and match storage, user, queue and stacks for a HPC Environment.

# Usage

- Run with your desired options and inventory
  ```shell
  ansible-playbook -i myinventoryfile --user root --extra-vars "storage=nfs user_mgmt=local stack=openflighthpc" main.yml
  ```

`storage` can be `nfs`.
`user_mgmt` can be `local`, `nis` or `ipa`.
`stack` can be `omnia`, `openflighthpc` or `openhpc`.
