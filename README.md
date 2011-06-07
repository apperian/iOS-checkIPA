# iOS IPA Validator #

checkipa scans an IPA file and parses its Info.plist (in Payload directory)
and embedded.mobileprovision files. It performs checks of expected key/value
relationships and report the results.

## Installation ##

put checkipa file in your path and make it executable.

## Usage ##

Launch your favorite terminal program and run program, e.g.:

  $ checkipa -i "file name.ipa"

For options:

  $ checkipa --help
