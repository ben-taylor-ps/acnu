# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## [1.0.16] - 2024-01-05

### Added:

If without brackets

### Fixed:

Array now works correctly
Fixed some numbers displaying as identifiers instead


## [1.0.15] - 2023-12-21

### Added:

Macro call inside start sub code
Constant inside start sub code

### Fixed:

Macro call ordering, before it was sometimes overridden, inconsistent
Constant keywords updated so that if the word is OFF_POS it matches the whole word and not part
Allow declaration of a macro with a # in the name


## [1.0.12] - 2023-12-14

### Added:

Single line if

### Fixed:

While statement ended brackets prematurely

## [1.0.11] - 2023-12-14

### Fixed:

A round bracket in single quotes does not end a macro call highlight prematurely
A square bracket in single quotes does not end an array highlight prematurely

## [1.0.10] - 2023-12-14

### Fixed:

Array behaviour now reads to the correct closing square bracket and doesn't end early when there's a square bracket in a string

## [1.0.9] - 2023-12-13

### Added: 

Single quotes

### Fixed:

Made sure addmessagerank always reads the whole string
Macro call behaviour now reads to the correct bracket and doesn't end early

## [1.0.4] - 2023-12-11

### Fixed:

Macro call no longer ends on brackets inside strings
Macro snippet updated



## [1.0.0] - 2023-12-11

Initial Release