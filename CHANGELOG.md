# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [March 2023]

### Added
- Ability to disconnect Bluetooth devices on sleep

### Fixed
- Race condition where Bluetooth devices can remain disconnected after quickly waking up from sleep
- Bluetooth reconnection after screen unlock when action is set to enable
- Incorrect log message for Wi-Fi related operations

### Changed
- Switched to os_log() for logging instead of print()
- Improved logging when setting Wi-Fi status
- Code cleanup and refactoring

## [December 2022]

### Added
- Wi-Fi support (disable/enable Wi-Fi on sleep/wake)
- Website menu item with version number tooltip

### Changed
- Restore state when screen is unlocked instead of on power up
- Upgraded LaunchAtLogin dependency
- Refactored Bluetooth feature in preparation for Wi-Fi support

## [October 2022]

### Added
- Alert message with instructions on how to show the icon again
- Tooltip for menu bar icon

## [September 2022]

### Added
- Re-add the status bar icon when the app is launched a second time
- Sync settings when menu is opened (supports manual edits via defaults utility)

### Changed
- Set minimum macOS version to 10.12
- Refactored menu updating code
- Clean up project configuration

## [August 2022]

### Added
- Option to determine Bluetooth behavior on wake: remember previous state, always enable, or never enable
- Cmd+Q keyboard shortcut for Quit menu item
- Menu separator before Quit item

### Changed
- Replaced Carthage with built-in Xcode Swift Package Manager

## [March 2022]

### Added
- Remember Bluetooth state before sleep (restore previous state on wake)

## [February 2021]

### Added
- Option to hide menu bar icon (headless mode)
- Turn Bluetooth ON when app is launched
- Turn off Bluetooth during shutdown

### Fixed
- Code signing identity setting

### Changed
- Updated to Xcode 12.4 settings
- Updated LaunchAtLogin to 4.0.0
- Updated installation instructions to reference official Homebrew cask

## [December 2020]

### Changed
- Updated Homebrew cask install command due to 2.7 deprecation

## [July 2020]

### Added
- Homebrew installation instructions

## [June 2020]

### Added
- Installation instructions in README

## [April 2020]

### Added
- Initial release
- README documentation
- Core functionality: disable Bluetooth on sleep, re-enable on wake
