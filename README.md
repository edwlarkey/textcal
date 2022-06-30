# textcal

Moved to [https://git.sr.ht/~edwlarkey/textcal](https://git.sr.ht/~edwlarkey/textcal)

A plain text calendar generator

## Features

* Generate a calendar for a year in plain text.
* Open text calendar to today's date in vim.
* Open text calendar to specific date in vim

## Requirements

* Python

## Setup

1. Add `textcal` to your $PATH
1. Set `TEXTCAL=/path/to/calendar` in .bashrc or equivalent
1. Generate calendar `textcal create -y 2015 > /path/to/calendar`
1. Open calendar on today's date `textcal open`

## Usage

```
usage: textcal [-h] [--version] {create,open} ...

A plaintext calendar

positional arguments:
  {create,open}  Commands
    create       Create new calendar
    open         Open calendat at date

optional arguments:
  -h, --help     show this help message and exit
  --version      show program's version number and exit
```
