[![PyPI](https://img.shields.io/pypi/v/kb-stopwatch.svg)](https://pypi.org/project/kb-stopwatch/)
![Python version](https://img.shields.io/badge/python-3-blue.svg)


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

Press the control key, which currently is restricted to space, to start
the stopwatch. Hit the control key again to stop the timer. Repeat as
many times as desired.
