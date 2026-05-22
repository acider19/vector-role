vector-role
=========

Ansible role for installing and configuring Vector.


Role Variables
--------------

| vars | default | description |
|------|---------|-------------|
| vector_version | 0.55.0 | Version of Vector to install |
| vector_arch | aarch64-unknown-linux-musl | Architecture of Vector to install |
| vector_http_port | 8080 | HTTP port for Vector to listen on |
| vector_install_dir | /opt/vector | Installation directory for Vector |
| vector_config_dir | /etc/vector | Configuration directory for Vector |
| vector_data_dir | /var/lib/vector | Data directory for Vector |
| vector_user | vector | User to run Vector as |
| vector_group | vector | Group to run Vector as |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector-role, vector_version: "0.55.0", vector_arch: "aarch64-unknown-linux-musl", vector_http_port: 8080 }
License
-------

MIT

Author Information
------------------

Artyom Muravskiy
Student of DevOps from zero course by Netology. FOPS-41.
