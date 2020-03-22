Ansible Certificate Authority
=============================

A basic pure Ansible certificate authority.

Commands
--------

### `init`

Initialize a new certificate authority.

### `trust`

Configure host to trust certificate authority.

### `issue`

Issue a new certificate to host.

### `sign-intermediate`

Sign a CSR created externally for an intermediate certificate authority.

Development
-----------
To run tests:

```
molecule test
```