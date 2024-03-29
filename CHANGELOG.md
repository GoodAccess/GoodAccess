# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.4.2] - 2023-04-25

### Added 

- Get device informations for device inventory
- Optional argument for persistent (MSI only)

## [3.4.0] - 2022-12-16

### Added 

- Persistent connection. When persistent is enabled, the VPN will remain connected even after you log out or switch Windows user accounts (the connection runs as a service).
- Registry reading for MSI package. Set up default protocol, team name and auto updates during installation.

### Fixed

- Reconnecting with openvpn protocol.

## [3.3.4] - 2022-11-15

### Added

- Application reacts to windows taskbar theme and change color of the tray icon based on taskbar theme.
- Error codes for better indication of error.

### Changed

- The way application get data => problem when 90% team can not even verify team.
- Error and warning messages.

### Fixed
- When application is connected and update downloaded, application send disconnect request before installation (bug - connection stayed after installation)
- Disable mouse third and fourth button for forward and back action.
- Service dropped and start when application is running. Service dropped exception.

## [3.3.2] - 2022-11-04

### Fixed

- Background service working bug fix.

## [3.3.1] - 2022-11-02

### Change

- Change tap adapter. This new adapter allows us to access up to 1 Gbit/s speed

### Fixed
- Check connection for larger teams - problem with ip range.
- UX bug with shortcuts carousal - teams using many systems shortcuts.

## [3.3.0] - 2022-10-31

### Added

- Always on feature - app remember last status of connection.
- No internet connection detection.
- Control connection from tray icon.

### Change

- Notification system.

[3.4.2]: https://app.goodaccess.com/team-member/download/msi
