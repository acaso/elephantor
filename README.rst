Elephantor
===========

**elephantor** is a frontend to the duplicity backup tool written in Python.

Install
=======

**Install from pip**
::

$ pip install elephantor

**Install from github**
::

$ git clone https://github.com/bougie/elephantor

**Configuration**
::

# cp /etc/elephantor/config.sample.py /etc/elephantor/config.py

And fill variables with right value.

How-to
------

**launch a backup**
::

$ elephantor backup

**get a list of saved files**
::

$ elephantor list

**get a list of saved files for a given date**
::

$ elephantor list --time 2014-01-01

**do a restore in the /tmp/fubar directory**
::

$ elephantor restore -d /tmp/fubar

**restore the file toto ine the current directory**
::

$ elephantor restore -f toto

