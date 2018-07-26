## insecure-platform-warning

[![Build Status](https://travis-ci.org/Oefenweb/ansible-insecure-platform-warning.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-insecure-platform-warning) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-insecure--platform--warning-blue.svg)](https://galaxy.ansible.com/Oefenweb/insecure-platform-warning)

Fixes the [InsecurePlatformWarning](https://urllib3.readthedocs.org/en/latest/security.html#insecureplatformwarning) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python` (will be installed)
* `python-dev` (will be installed)
* `build-essential` (will be installed)
* `libffi-dev` (will be installed)
* `libssl-dev` (will be installed)

#### Variables

* `insecure_platform_warning_conflicting` [default: `[]`]: Conflicting packages to remove (e.g. `[python-openssl]`)

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip))

#### Example

```yaml
---
- hosts: all
  roles:
    - insecure-platform-warning
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-insecure-platform-warning/issues)!
