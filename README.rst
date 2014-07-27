mktorrent builds for Windows
============================

MinGW builds:
-------------

* Download `mktorrent for Windows 32-bits`_.

* Download `mktorrent for Windows 64-bits`_.

.. _mktorrent for Windows 32-bits: https://github.com/coreb1te/mktorrent-for-windows/raw/master/mingw-builds/mingw32/mktorrent.exe
.. _mktorrent for Windows 64-bits: https://github.com/coreb1te/mktorrent-for-windows/raw/master/mingw-builds/mingw64/mktorrent.exe

Build configuration:
--------------------

* Windows 32-bits::

    make CC=i686-w64-mingw32-gcc USE_LONG_OPTIONS=1 USE_LARGE_FILES=1

* Windows 64-bits::

    make CC=x86_64-w64-mingw32-gcc USE_LONG_OPTIONS=1
