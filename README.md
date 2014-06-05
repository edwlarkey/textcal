# textcal

Generate calendar for year in plain text and open that calendar to a specific
date in vim.

## Features

* Generate a calendar for a year in plain text.
* Open text calendar to today's date in vim.
* Open text calendar to specific date in vim

## Requirements

* Python
* [docopt](http://docopt.org/)

## Setup & Usage

1. Make `textcal` executable with `chmod +x textcal`

2. Move `textcal` to `~/bin` or somewhere else in your path.

3. Generate a calendar with `textcal --generate 2014 > 2014.textcal`

4. Edit `textcal` to the reflect the location of your CALENDAR.

5. Open calendar with `textcal` to go to today's date OR use `textcal --show 05-02` to go to May 2nd.
