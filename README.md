[![PyPI](https://img.shields.io/pypi/v/kb-stopwatch.svg)](https://pypi.org/project/kb-stopwatch/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/kb-stopwatch.svg)](https://pypi.org/project/kb-stopwatch/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# kb-stopwatch

This is a keyboard controlled stopwatch that runs in your terminal and
works without window focus. Downside to the window focus thing—you need
to run this as root. But compromises, right?

Anyway, this is good for ad-hoc speedrunning. Enjoy!

## Installation

Run directly from source with

```
sudo ./run_kbstopwatch.py
```

or install with pip with

```
pip3 install kb-stopwatch
```

and run with

```
sudo kb-stopwatch
```

## Usage

To start the stopwatch, press the control key, which you can set with

```
kb-stopwatch --control-key 'keyname'
```

(defaults to `'space'`). Hit the control key again to stop the timer.
Repeat.
