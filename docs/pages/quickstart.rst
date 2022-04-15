ManoPot Quickstart
===================

ManoPot is a simple TCP HoneyPot written in Python 3.

Installation
------------

    python -m pip install manopot

Running
-------

    python -m manopot


Debian package
---------------

ManoPot can also be installed as a systemd service on Debian based distributions.

Dowload the package from GitHub release, or build the Debian package with:

    dpkg-deb --build ./deb manopot-1.0.0.deb

Install the Debian package with:

    sudo dpkg -i manopot-1.0.0.deb

Config defaults to /etc/manopot.ini. Logs will be available in /var/log/manopot.log.


Source Code
-----------

https://github.com/Rand0mAccess/ManoPot


PyPI package
------------

https://pypi.org/project/manopot/


Documentation
-------------

http://manopot.rtfd.io/