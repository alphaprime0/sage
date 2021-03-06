configparser
============

Description
-----------

This library brings the updated configparser from Python 3.5 to Python
2.6-3.5.

The ancient ConfigParser module available in the standard library 2.x
has seen a major update in Python 3.2. This is a backport of those
changes so that they can be used directly in Python 2.6 - 3.5.

To use the configparser backport instead of the built-in version on both
Python 2 and Python 3, simply import it explicitly as a backport:

   from backports import configparser

If you'd like to use the backport on Python 2 and the built-in version
on Python 3, use that invocation instead:

   import configparser

For detailed documentation consult the vanilla version at
http://docs.python.org/3/library/configparser.html.
