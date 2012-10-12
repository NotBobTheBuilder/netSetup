netSetup
========

A utility to assist in the creation of config files for common network services


NOTE: Example files (in M4 syntax) can only be preprocessed from *within* the example directory. Ensure your command sequence is the following:

cd Examples/

m4 dhcpd\_simple

The resulting output will then go through STDOUT. 

It may also be useful to pipe this through sed '/^$/d' to remove any newlines before the config starts.
