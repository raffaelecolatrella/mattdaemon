mattdaemon
==========

.. _Python: https://python.org
.. _git repo: https://github.com/plausibility/mattdaemon
.. _plausibility: https://github.com/plausibility
.. _readthedocs: https://mattdaemon.readthedocs.org

Need to daemonize your Python2.7 projects? Matt Daemon has you covered.

Features
--------

- superuser (root) enforcement. Your script either requires it or it doesn't. You choose!

  -  If these checks fail, the script will exit with a status of **1**.

- Uses the double-fork magic of UNIX to daemonize.

Dependencies
------------

- `Python`_ 2.7

Notes
-----

- This is designed for CLI scripts, because it decouples from the parent environment and all.
- Includes annoying messages when you use root to run a script.
- ``daemon.start()`` and ``daemon.stop()`` don't print messages. You'll have to decide what to print, if anything.
- MIT Licensed code, so you're free to do whatever you want with this. Sell it, steal it, improve it, anything at all!

Running / Usage
---------------

- Add the script to your dependencies, it's on pypi! (``pip install mattdaemon``)
- Documentation is available on `readthedocs`_, so check there for usage.

Contributing
------------
If a feature you need is lacking, you know a better way to do something, or you just want to be nice and give out your stars, feel free to visit the mattdaemon `git repo`_; it's open source and MIT licensed!

Author
------
- `plausibility`_
