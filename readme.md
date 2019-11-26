## ![OpenMCR](logo.png)

### _The Free and Open-Source Multiple Choice Exam Reader_

## Background

In response to the phenomonon that typical OMR (optical mark recognition, also
known as bubble sheets) exams sheets, scanning hardware, and processing software
can cost up to several thousand dollars per year, this software and the
corresponding multiple choice sheet were developed as an independent study
project by Ian Sanders, a mechanical engineering student at the University of
South Florida, under the direction of Dr. Autar Kaw.

This tool is intended to be simple, fast, and extremely reliable. One can
conduct and grade an exam simply by printing and scanning the sheets with any
standard machine. The software has been tested extensively to ensure that
software is as reliable as any other product available.

## Features

Features built into this tool incude:

- Quick bulk processing of scanned sheets
- Support for first, middle, and last name
- Support for course and student ID numbers
- Support for up to 64 different test variations
- Support for 1-75 questions per exam, with answer choices A-E
- Support for multiple answer selection (ie A and B)
- Data exported to standard CSV files
- Orientation-independent file reading (can read sideways scans, upside down
  scans, or even off-axis scans)
- Can read both pencil and pen marks

If desired, the following additional features can optionally be used:

- Automatic question scoring and grade calculation (even with multiple test
  forms)
- Sorting of output by desired values
- Creation of answer keys through scanned bubble sheets or through manual CSV
  creation

## Installation Instructions

To install the utility, simply download the latest release from the
[releases](https://github.com/iansan5653/open-mcr/releases) page and
install it. After installation, check your Start menu for a shortcut.

Currently, installers are only provided for Windows.

To print the multiple choice sheet, see
[multiple_choice_sheet.pdf](https://github.com/iansan5653/open-mcr/blob/master/code/assets/multiple_choice_sheet.pdf).
This can also be accessed from within the software.

## Usage Instructions

For full operating instructions, see the [Manual](code/assets/manual.md) or
click the "Open Help" button in the software.
