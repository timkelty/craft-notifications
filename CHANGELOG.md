# Notifications Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 1.1.0 - 2018-05-21
### Changed
- Notifications are no longer queued as this causes a lot of issues with serialization. Will find a better solution for this in the future.

## 1.0.6 - 2018-03-06
### Added
- Notification now extends the Craft base model for easier configuration

## 1.0.5 - 2018-02-28
### Fixed
- Fixed an error when trying to serialize an Entry that cannot be serialized

## 1.0.3 - 2018-01-23
### Fixed
- Fix the foreign key on the install migration

## 1.0.2 - 2018-01-23
### Fixed
- Fixes the stub used to create a notification

## 1.0.1 - 2018-01-14
### Added
- Added the `notifications/make` command to generate a stub

## 1.0.0 - 2018-01-14
### Added
- Initial release
