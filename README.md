# Wizcoin


A Python module to represent the galleon, sickle, and knut coins of wizard currency.

## Installation

To install with pip on macOS or Linux, run:

    python3 -m pip install git+https://github.com/YouMax1/wizcoin.git

To install with pip on Windows, run:

    py -m pip install git+https://github.com/YouMax1/wizcoin.git

(This module is not yet completed.Please do not download it.)

Quickstart Guide
----------------
    
    Here's some example code demonstring how this module is used:

    >>> import wizcoin
    >>> coin = wizcoin.Wizcoin(2, 5, 10)
    >>> str(coin)
    '2g, 5s, 10k'
    >>> coin.value()
    1141

Contribute
----------

If you'd like to contribute to Wizcoin, check out https://github.com/YouMax1/wizcoin
