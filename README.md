Workflows
=========

Reusable GitHub Actions workflows.

Usage
-----

### Release Ansible role to Ansible Galaxy

```yaml
name: Release
on:
  release:
    types:
      - published
jobs:
  release:
    name: Release
    uses: gantsign:workflows/.github/workflows/ansible-galaxy-import.yml@v1
    secrets: inherit
```

License
-------

The Unlicense

Author Information
------------------

John Freeman

GantSign Ltd.
Company No. 06109112 (registered in England)
