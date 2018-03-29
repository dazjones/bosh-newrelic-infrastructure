# newrelic-infrastructure release for BOSH

## Usage - Bosh Addon

```
addons:
- jobs:
  - name: bosh-newrelic-infrastructure
    properties:
      newrelic:
        license_key: ((newrelic_license_key))
    release: newrelic-infrastructure
  name: bosh-newrelic-infrastructure
releases:
- name: bosh-newrelic-infrastructure
  url: https://github.com/dazjones/bosh-newrelic-infrastructure/releases/download/v0.1.1/bosh-newrelic-infrastructure-0.1.1.tgz
  version: 0.1.1
  ```
