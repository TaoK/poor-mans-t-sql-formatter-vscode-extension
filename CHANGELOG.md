# Change Log

All notable changes to the "poor-mans-t-sql-formatter" VS Code extension will (hopefully) be documented in this file.

The intent is to follow the structure lais out at [Keep a Changelog](http://keepachangelog.com/), and follow semantic versioning.

## [Unreleased]


## [1.6.11] - 2019-01-19

- Added support for Azure Data Studio

## [1.6.10] - 2017-11-21

- Upstream fixes:
    - Fixed rare negative exponent problem, GitHub issue #142
    - Fixed "name" keyword detection issue, as per GitHub pull request #141
    - Fixed recently-introduced issue with "noformat" regions, GitHub Issue #182
    - Fixed longstanding formatting consistency issues with noformat and minimize, GitHub issues #183, #184, #185

## [1.6.6] - 2017-11-19

- Initial release
- All the same options and behaviors supported as SSMS, VS, Notepad++, Atom
- Matches main library version 1.6.5 (as per NPM dependency)
