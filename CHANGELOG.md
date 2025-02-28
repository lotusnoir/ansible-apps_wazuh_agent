# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/2.0.0...2.1.0) - 2025-01-15

### Merged

- Fix repo signing issue [`#1`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/pull/1)

### Commits

- add support for ubuntu24 [`8bdc0b9`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/8bdc0b96c602c3f6bc15e6596be3aeecfac588e4)
- add version on molecule play image to maintain support on old release [`ba81501`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/ba81501b02e0ffba9a702be7adae94b162f599d2)
- update molecule [`05078b1`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/05078b1f1c1205994c501a5597d17526e06e7b84)
- add redhat 9 to default supported distrib [`1ad2865`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/1ad2865031d7ba98e67a431bf8148622422567f8)
- add redhat support [`627b158`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/627b15883cf0fc91d6ea59d03057671b8ae75865)
- remove redhat [`d1680c5`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/d1680c5f5de06555d14c46880e3874f3c57a31a7)
- Explicitly specify keyring [`a35dd67`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/a35dd6703cc04383035a1af8b5bb6fe3e3101197)
- sort testing distrib to avoid random changes [`4cc53ee`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/4cc53ee869c982aa22fd50c34af000889c19178e)
- update pre-commit and lint fix [`ae0ebd2`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/ae0ebd2d96cfacc71b48737e9f435d100d21c0cc)
- remove support for rhel7 and docker dind on gitlab [`73d9f18`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/73d9f183232b33fca4f8f57e560a2f495d68a547)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`06f3a59`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/06f3a593dbc26a2bfdc53d71d571eb6e899bd19c)
- update readme + precommit + include vars [`30b515b`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/30b515b117e4be475de2ba3b043a9fa2039ce422)
- update molecule playbook order and main include vars [`2f3adaf`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/2f3adaf3ca6149bab2599ab178f73a26448e59cb)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`ebe5a87`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/ebe5a8700a5d8fce8a39a3ec98fd7ce66d4d5083)
- add precommit for lint [`26b1611`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/26b1611d3c58ca0cc13e254264fd2246d4aa0642)
- fix checks [`8ecddd0`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/8ecddd044f069284d1b2147e9d27672b566eeb38)
- add new molecule all scenario [`1daa90e`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/1daa90e8993ff0a9b1aa4ae42405cd8edd912adf)
- split distro for molecule tests on ci [`7f911b5`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/7f911b544f580e7d13c38bed8cbbfaab9b25fdf4)
- update checks and Readme [`b80012f`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/b80012f73542d9579ef69188b566568c43275a5d)
- add molecule fix for ora9 [`6a00d1a`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/6a00d1a39ac505a7ee39de44ce61973e79872fbd)
- add custom repo + download only option [`803640e`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/803640ef28b3f33fd730c936d3811c2568092ebb)
- add deploy vars + windows support [`8353fe5`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/8353fe5f9621e1467c4994a9362d83f2b4e43546)
- add pwd + rootca support [`47c63f5`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/47c63f59cbaf710db8d83a2ed3f7f12121042a54)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`66f513c`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/66f513cceef711bc065449e326ee7698b9f9e528)
- minor: add oracleLinux support + little fixes [`775b734`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/775b734e3bdfb4a830b06065652b65c7cd856890)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/0.1.1...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`353f825`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/353f825c59b6d7d18d8593b16748fda3bfd61c0d)
- fix: remove unsupported centos8 + minor fixes [`8f6c0e3`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/8f6c0e3ec76738a3d548123729daea23ed810198)

## [0.1.1](https://github.com/lotusnoir/ansible-apps_wazuh_agent/compare/0.1.0...0.1.1) - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`8e16ba2`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/8e16ba291b87adeb66082ba03c7038b8ae8dc44d)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`3571318`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/357131855e8e4406d185e1abd1eaf87526c05505)

## 0.1.0 - 2021-11-09

### Commits

- initial commit [`31e7bb1`](https://github.com/lotusnoir/ansible-apps_wazuh_agent/commit/31e7bb1fc66227d5a8f1bdda0f0cbbc294477843)
