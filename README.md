#Kroger Google Calendar#

This script, as it stands right now, will update a user's google calendar with
their relative kroger store's work schedule using feed.kroger.com

## Installation

Easiest is to use [this repo](https://github.com/insanemode/kgc) and follow the instructions.

It's still not easy.

## User details pipeline

* Manually entered into `settings.json`
* pulled from file into `SETTINGS` global object
* sent to `pull_schedule`
* sent through `KrogerBrowser` object
* sent to website through `KrogerBrowser.login`

## Use ##
    python update.py [--calendar] [--debug]
