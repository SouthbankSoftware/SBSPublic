# Southbank Software tester JS test

Write a test suite that validates the data contained in the file ().

The test suite can be written in a Javascript framework of your choice or as native Javascript code. It should be runnable in nodeJS:  we'll try and run it against 8.9.1.  You should include a package.json file that contains any dependencies.

The test suite should accept the file name from the command line, an environment variable or a configuration file.

There are three test cases to write:

1.  The case sensitive value of the proofType attribute should be "full" or "incremental."
2.  The date value in submitTimestamp should be no ealier than one year ago
3.  The value of the Country attribute should be a valid country code.  Use the rest service at (http://services.groupkt.com/country/get/iso3code) to validate this

