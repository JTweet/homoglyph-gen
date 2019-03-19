# homoglyph-gen

A python script to generate a list of possible homoglyph domains of a given domain name.
This may be useful to monitor for phishing sites when used in combination with certificate transparency or whois polling.

## Requirements
homoglyph-gen was developed using Python 3.7.2, other versions are untested, but will probably work though you may need to install additional dependencies.

## External dependencies
* [homoglyphs](https://pypi.org/project/homoglyphs/)

## Usage
```
# Display homoglyph domains for o-sp.com IDNA encoded
tweet@host$ ./homoglyph-gen o-sp.com
# Display homoglyph domains for o-sp.com as UTF-8
tweet@host$ ./homoglyph-gen o-sp.com --idna off
```