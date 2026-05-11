# Changelog

All notable changes to SilentBeep are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

_No unreleased changes yet._

## [1.1.4] - 2026-05-11
### Fixed
- Fixed GitHub Pages update feed publishing in the release workflow.
- Fixed update notifications not refreshing the tray icon immediately.
- Fixed release notes scrolling inside Settings.
- Open Settings when clicking an update-available tray notification.
- Made available updates visible at the top of Settings.

## [1.1.3] - 2026-05-11
### Changed
- Enabled Windows autostart by default for new installations.

## [1.1.2] - 2026-05-11
### Fixed
- Fixed update feature

## [1.1.1] - 2026-05-10
### Fixed
- Fixed asymmetric margins in settings window
- Pinned scrollbar to right edge of settings window

## [1.1.0] - 2026-05-07
### Added
- Added USDT (TRC20) donation option in README
- Added badges for different states (update available, pause)
- Added grayscale night mode icon

### Fixed
- Fixed GDI handle leak when changing tray icon — previous icon is now disposed before assigning new one
- Fixed autostart setting being lost after reinstall or update — now saved to config and restored on startup
- Fixed small logo in settings window — cropped logo.png to remove empty space

## [1.0.5] - 2026-05-06
### Fixed
- Fixed startup jingle

## [1.0.4] - 2026-05-06
### Changed
- Added "Download and Install" button in settings to manually download and install updates
- Added tray icon badge (orange dot) when an update is available
- Added balloon notification when an update is available
- Release notes now show all versions from current to latest (plain text format)
- Renamed "Restart to Update" to "Download and Install" for clarity

## [1.0.3] - 2026-05-05
### Fixed
- Fixed tray icon not updating correctly when enabling/disabling the scheduler (ObjectDisposedException)

## [1.0.2] - 2026-04-27
### Added
- Display release notes in update section when an update is available (expandable section in settings)

## [1.0.1] - 2026-04-27
### Changed
- Small optimizations and code cleanup

## [1.0.0] - 2026-04-25
### Added
- Tray utility that keeps speakers awake with inaudible pulses
- Night mode: optionally pause beeps during specified nighttime hours
- Auto-updates from GitHub Releases (silent, applied on next launch)
- Windows autostart
- Graceful handling of system sleep/resume (scheduler re-aligns after wake)
- Localized UI in English and Russian with auto-detection and manual switcher
- Theme switcher (System / Light / Dark) with automatic detection of Windows theme









