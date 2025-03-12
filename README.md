Configure and install PostreSQL
=========

The role configures and installs PostgreSQL.

Role Variables
--------------

Example Playbook
----------------

```yaml
- hosts: servers
  vars:
    postgres_db_password: "password"

  roles:
    - role: tychobrouwer.postgres

    - role: tychobrouwer.postgres
      postgres_db_user: "postgres"
      postgres_db_name: "postgres"
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
