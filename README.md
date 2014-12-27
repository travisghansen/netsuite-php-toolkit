# NetSuite PHP Toolkit
The standard NetSuite-supplied toolkit with 1 major tweak: NAMESPACE support.

All classes are namespaced with NetSuite\WebServices\ to keep pollution down.

## Usage
 1. Introduced a NSconfig object
 1. Added a 'logging' parameter to NSconfig
 1. The NetSuiteService construct method gets an instantiated NSconfig object as it's first parameter
