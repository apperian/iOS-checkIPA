# iOS IPA Validator #

### originally by G. Gold, No longer maintained. ###

This tool is no longer maintained by Apperian. Feel free to take it and improve it, but we've moved on to other things and no longer have the time to keep this up to date.

`checkipa` scans an IPA file and parses its Info.plist (in Payload directory)
and embedded.mobileprovision files. It performs checks of expected key/value
relationships and reports the results.

## Installation ##

put `checkipa` file in your path and make it executable.

## Usage ##

Launch your favorite terminal program and run program, e.g.:

    $ checkipa -i "file name.ipa"

For options:

    $ checkipa --help
