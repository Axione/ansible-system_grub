# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.1](https://github.com/lotusnoir/ansible-system_grub/compare/2.2.0...2.2.1) - 2025-11-29

### Commits

- add no changes on run flag to keep idempotence [`1938405`](https://github.com/lotusnoir/ansible-system_grub/commit/193840529191b7990a5a32cc0f7b4b0e6f977fc3)

## [2.2.0](https://github.com/lotusnoir/ansible-system_grub/compare/2.1.0...2.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`e0445dd`](https://github.com/lotusnoir/ansible-system_grub/commit/e0445dd1853ccb9aada84978f709920c81f00e30)

## [2.1.0](https://github.com/lotusnoir/ansible-system_grub/compare/2.0.0...2.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`e5eaac0`](https://github.com/lotusnoir/ansible-system_grub/commit/e5eaac0ed944010c152f1e95fe98048afc8caac3)
- add oraclelinux10 support + lint and core fixes [`c05b6db`](https://github.com/lotusnoir/ansible-system_grub/commit/c05b6db0174d70ba41d18fabfea837f05634829b)

## [2.0.0](https://github.com/lotusnoir/ansible-system_grub/compare/1.1.0...2.0.0) - 2025-10-30

### Commits

- update core [`732332a`](https://github.com/lotusnoir/ansible-system_grub/commit/732332a8015b55fbe6a65f4e37d85b16e47a5093)
- fix lint [`15e9ff3`](https://github.com/lotusnoir/ansible-system_grub/commit/15e9ff3298b1b3197501f6a128ad2c78af11a037)
- fix molecule paralelism and little updates [`71cf6f2`](https://github.com/lotusnoir/ansible-system_grub/commit/71cf6f20f339ccf875fc1a902dcd08a40d7bf918)

## [1.1.0](https://github.com/lotusnoir/ansible-system_grub/compare/1.0.0...1.1.0) - 2025-01-17

### Commits

- add support for ubuntu24 [`3cd5ca7`](https://github.com/lotusnoir/ansible-system_grub/commit/3cd5ca75a9328492e49a7566a2987d3e1571bf18)
- add version on molecule play image to maintain support on old release [`d938e63`](https://github.com/lotusnoir/ansible-system_grub/commit/d938e6345ab35db2523d594a63ecc4430d43bf29)
- update molecule [`c09d2c2`](https://github.com/lotusnoir/ansible-system_grub/commit/c09d2c2b49400cd76516ec2c379c158958e8e9a1)
- add redhat 9 to default supported distrib [`17e9a1b`](https://github.com/lotusnoir/ansible-system_grub/commit/17e9a1be11079e7b2b0dcb205a718eac97e83570)
- remove redhat molecule checks [`5f4a8c5`](https://github.com/lotusnoir/ansible-system_grub/commit/5f4a8c5d01131276589426cbb2c1e2484afb17c9)
- sort testing distrib to avoid random changes [`6b62a82`](https://github.com/lotusnoir/ansible-system_grub/commit/6b62a82305114a61855c187d9ca19c55287f9971)
- update pre-commit and lint fix [`0cfc97d`](https://github.com/lotusnoir/ansible-system_grub/commit/0cfc97d50527c120c4469563956705401b66d451)
- remove rhel7 support and remove docker dind on pipeline [`2ca67a8`](https://github.com/lotusnoir/ansible-system_grub/commit/2ca67a856c1b44a64b66c462f0d930f7be09e27a)
- remove lint from pipeline [`67780ab`](https://github.com/lotusnoir/ansible-system_grub/commit/67780ab53cb88c57022cd7018db896baf8ce0902)
- remove pipelines tests, moved in precommits [`72779b6`](https://github.com/lotusnoir/ansible-system_grub/commit/72779b67eb5631a58069e4b63c3f3993b33f7a03)

## [1.0.0](https://github.com/lotusnoir/ansible-system_grub/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`9959a93`](https://github.com/lotusnoir/ansible-system_grub/commit/9959a931b216afad2a8de4ffd86a9de3f0aaa69f)
- update readme + precommit + include vars [`10786b4`](https://github.com/lotusnoir/ansible-system_grub/commit/10786b42a479ccbfe9b1514dbbf960bae1402b91)
- change import tasks to include in order to support facts on name [`464ad62`](https://github.com/lotusnoir/ansible-system_grub/commit/464ad628791a33807835b591999bddde1cca45b7)
- change regex to cover more use cases [`b15166c`](https://github.com/lotusnoir/ansible-system_grub/commit/b15166c29e988a968305fbfae4e160e406155f64)

## [0.2.0](https://github.com/lotusnoir/ansible-system_grub/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`9d16139`](https://github.com/lotusnoir/ansible-system_grub/commit/9d16139541d90adfd54715a53bc169b9cc411a45)
- add galaxy id [`5ba1b36`](https://github.com/lotusnoir/ansible-system_grub/commit/5ba1b369593812aa183edcc6226e860db5c400b3)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`829dcc8`](https://github.com/lotusnoir/ansible-system_grub/commit/829dcc82a13f792a40e3f2375a6f9dcb0da05ac4)
- add precommit for lint [`da6d1f8`](https://github.com/lotusnoir/ansible-system_grub/commit/da6d1f8527e50d0632799de57edd727eaf858c82)
- add quotes on options [`2b640ac`](https://github.com/lotusnoir/ansible-system_grub/commit/2b640acfe09ccd091ffd2078530f037f32cdbd79)
- add vars for path [`73ad5d6`](https://github.com/lotusnoir/ansible-system_grub/commit/73ad5d62053f82b15638f335f3eab93076c857c6)
- change tasks to allow all options change [`790021e`](https://github.com/lotusnoir/ansible-system_grub/commit/790021e8b19e31b2c4b11ded953feaeb7ca1dee7)
- fix checks [`4e566ae`](https://github.com/lotusnoir/ansible-system_grub/commit/4e566ae6e6ad94bc9de0daa076829785e0fe6cc3)
- fix idempotence [`0ae8675`](https://github.com/lotusnoir/ansible-system_grub/commit/0ae8675eb08ece19f4383678fbfa106b6cf58eff)
- split distro for molecule tests on ci [`f8e69ae`](https://github.com/lotusnoir/ansible-system_grub/commit/f8e69ae5833a44521d0a97ffec238237395176ec)
- add condition for secur bootloader [`deb0c7b`](https://github.com/lotusnoir/ansible-system_grub/commit/deb0c7bb7ec8ed8cea2dd484612202eb7fd7f466)
- update vars [`260d242`](https://github.com/lotusnoir/ansible-system_grub/commit/260d24247a49d676971be8381fe8ab4e04606fb8)
