# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Types of changes
- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for soon-to-be removed features.
- `Removed` for now removed features.
- `Fixed` for any bug fixes.
- `Security` in case of vulnerabilities.
- 'TBA' to be added, antipated changes. 


### KN updates on fork
## [1.0.1] - 2025-01-02

## Added
- New disk image with updates to /etc/dhcpcd.conf file:
    - Hardcoded default static IP address default - 192.168.2.2
## TBA
making the IP address an editable parameter in the 'video-sync.conf' file

## [Unreleased]

## [1.0.0] - 2023-12-04

### Added

- New commands: `STOP`, `START`, `RESTART`.
- New file: `/boot/video-sync.info` for displaying system information.

### Changed

- Display my IP and MAC address in color during the boot process.

### Fixed

- Filter out hidden files generated by macOS (files with names starting with a dot '.') (#3).

