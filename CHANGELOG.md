# Changelog

All notable changes to SilentBeep are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

_No unreleased changes yet._

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




