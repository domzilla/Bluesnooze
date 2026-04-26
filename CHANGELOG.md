# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [March 2023]

### Added
- Option to disconnect Bluetooth devices on sleep.

### Fixed
- Bluetooth devices could remain disconnected after a quick sleep/wake cycle.
- Bluetooth no longer fails to reconnect after unlocking the screen when the wake action is set to enable.

## [December 2022]

### Added
- Wi-Fi support: optionally disable Wi-Fi on sleep and re-enable on wake.
- Website menu item with the version number shown as a tooltip.

### Changed
- State is now restored when the screen is unlocked instead of on power up.

## [October 2022]

### Added
- Alert with instructions for showing the menu bar icon again after hiding it.
- Tooltip on the menu bar icon.

## [September 2022]

### Added
- Status bar icon is re-added when the app is launched a second time.
- Settings sync when the menu is opened, so manual edits via the `defaults` utility are picked up.

### Changed
- Lowered the minimum macOS version to 10.12.

## [August 2022]

### Added
- Wake behavior options: remember previous state, always enable, or never enable Bluetooth.
- Cmd+Q keyboard shortcut for the Quit menu item.

## [March 2022]

### Added
- Bluetooth state is remembered before sleep and restored on wake.

## [February 2021]

### Added
- Headless mode that hides the menu bar icon.
- Bluetooth is turned on when the app launches, and turned off during shutdown.

## [December 2020]

### Changed
- Updated the Homebrew cask install command for Homebrew 2.7.

## [July 2020]

### Added
- Homebrew installation instructions in the README.

## [June 2020]

### Added
- Installation instructions in the README.

## [April 2020]

### Added
- Initial release.
- Disable Bluetooth on sleep and re-enable on wake.
