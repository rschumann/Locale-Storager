Locale Storager
===============

A little script that helps in managing the localeStorage of the browser.<br />
v 0.9 - January 11th 2012<br />
By Gaya Kessler - http://www.gayadesign.com

Usage:
------
The script stores strings and arrays (objects) in the browser's localeStorage. Also an easy way to parse the values and get the logical representation in Javascript variables.

    localeStorager.store(key, variable)
Store a variable in the localeStorage using a key.

    localeStorager.get(key)
Get the Javascript representation of the value using the key.

    localeStorager.remove(key)
Remove the value from the localeStorage.