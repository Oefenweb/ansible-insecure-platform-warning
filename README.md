## insecure-platform-warning

[![Build Status](https://travis-ci.org/Oefenweb/ansible-insecure-platform-warning.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-insecure-platform-warning) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-insecure--platform--warning-blue.svg)](https://galaxy.ansible.com/list#/roles/4386)

Fixes the [InsecurePlatformWarning](https://urllib3.readthedocs.org/en/latest/security.html#insecureplatformwarning) in Debian-like systems.

#### Requirements

* `pip` (will not be installed)

#### Variables

None

## Dependencies

None

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
