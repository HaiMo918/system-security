# System Security (`system-security`) - Change log

All notable changes to this role will be documented in this file.
This role adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Note: Developers - make sure to set the `BARC_role_version` variable when releasing new versions of this role.

## [Unreleased][unreleased]

### Added

* Local facts to record this role has been applied to a system and its version, plus supporting documentation sections
* Missing 'hostname' role for use when testing

### Fixed

* README formatting and typos
* Minor corrections to other files for formatting and typos
* Testing role dependencies should always use latest versions
* Pinning Ansible to pre-2.0 version in CI

### Changed

* Migrating from new Ansible Galaxy namespace, from 'BARC' to 'bas-ansible-roles-collection'
* Migrating from old Ansible Galaxy 'categories' to new 'tags' meta-data
* Migrating from old Repository in 'antarctica' to 'bas-ansible-roles-collection'
* Migrating from old Semaphore 'antarctica' organisation to 'bas-ansible-roles-collection'
* Simplifying CI setup tasks

## 0.1.0 - 30/11/2015

### Added

* Initial version
