============================
Command Line Interface (CLI)
============================

After you have installed, type ``swap`` to verify that it worked:

::

    $ swap
    Usage: swap [OPTIONS] COMMAND [ARGS]...

    Options:
      -v, --version  Show Shuttle version and exit.
      -h, --help     Show this message and exit.

    Commands:
      bitcoin  Select Bitcoin provider.
      bytom    Select Bytom provider.
      vapor    Select Vapor provider.


.. click:: swap.cli.__main__:main
  :prog: swap
  :show-nested: