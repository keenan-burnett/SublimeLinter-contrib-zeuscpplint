SublimeLinter-contrib-zeuscpplint
================================

[![Build Status](https://travis-ci.org/SublimeLinter/SublimeLinter-contrib-zeuscpplint.svg?branch=master)](https://travis-ci.org/SublimeLinter/SublimeLinter-contrib-zeuscpplint)

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to [zeuscpplint](__linter_homepage__). It will be used with files that have the “__syntax__” syntax.

## Installation
SublimeLinter must be installed in order to use this plugin. 

Please use [Package Control](https://packagecontrol.io) to install the linter plugin.

Before using this plugin, ensure that `cpplint` is installed on your system.
To install `cpplint`, do the following:

1. Install [Python](http://python.org/download/) and [pip](http://www.pip-installer.org/en/latest/installing.html).

1. Install `cpplint` by typing the following in a terminal:
   ```
   [sudo] pip install cpplint
   ```

In order for `zeuscpplint` to be executed by SublimeLinter, you must ensure that its path is available to SublimeLinter. The docs cover [troubleshooting PATH configuration](http://sublimelinter.readthedocs.io/en/latest/troubleshooting.html#finding-a-linter-executable).

## Settings
- SublimeLinter settings: http://sublimelinter.readthedocs.org/en/latest/settings.html
- Linter settings: http://sublimelinter.readthedocs.org/en/latest/linter_settings.html

