CHANGELOG
=========

Starting from version `0.8.0` the plugin uses [semantic versionning 2.0.0](http://semver.org/).

0.8.4 <small>(2015-12-29)</small>
------------------------------

* More refactoring
* Improve the way the plugin detects & sets the gulpfile
* Simplify task names gathering for plugin(s) integration
* Take in account whitespace characters before task names
* Fix: Get task names only if a gulpfile is found

------------------------------

0.8.3 <small>(2015-12-21)</small>
------------------------------

* Fix: Get focus back only when vim window id is different from 0

------------------------------

0.8.2 <small>(2015-12-21)</small>
------------------------------

* Refactoring
* Improve custom command process, `g:gv_custom_cmd` can now escape double quotes if needed
* Set back focus to the editor after using `GulpExt` (Need `wmctrl` & is Unix only)
* Update screenshots and documentation

------------------------------

0.8.1 <small>(2015-12-16)</small>
------------------------------

* Fix rvm_hack value
* Add more informations in the README.

------------------------------

0.8.0 <small>(2015-12-15)</small>
------------------------------

* Fixes bug introduced by ad764163f
* Improve definitions of commands & functions.
* Allowd rvm hack option to work everywhere & make it unix only.

### Features

* Add Unite source thanks to @dawnofthedev
* Add possibility to define a custom command to use with `GulpExt` (`g:gv_custom_cmd`).

------------------------------

0.7.1 <small>(2015-11-21)</small>
------------------------------

* Use `--gulpfile` flag

### Features

* Add CtrlP integration (`:CtrlPGulp`)

------------------------------

0.6.2 <small>(2015-10-27)</small>
------------------------------

### Fixes

* Fix GulpExt command
* Fix redrawing issue

### Features

* Add Dispatch integration (`g:gv_use_dispatch`)

------------------------------

0.6 <small>(2015-10-22)</small>
------------------------------

* Echo gulpfile name & tasks number before proceeding

### Features

* Add support of `gulpfile.coffee` & `gulpfile.babel.js`
* New command `GulpFile`
* New customization variable `g:gv_default_gulpfile`

------------------------------

0.5 <small>(2015-10-18)</small>
------------------------------

* Refactoring
* Add a doc file
* Add a CHANGELOG file

