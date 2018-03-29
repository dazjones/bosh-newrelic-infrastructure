# newrelic-infrastructure release for BOSH

## Usage - Bosh Addon

```
addons:
- jobs:
  - name: newrelic-infra-bosh
    properties:
      newrelic:
        license_key: ((newrelic_license_key))
    release: newrelic-infrastructure
  name: newrelic-infrastructure
releases:
- name: newrelic-infrastructure
  url: https://github.com/dazjonesbosh-newrelic-infrastructure/releases/download/v0.1.1/newrelic-infrastructure-0.1.1.tgz
  version: 0.1.1
  ```
