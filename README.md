detectindent
============

Vim script for automatically detecting indent settings

[The original plugin](https://github.com/ciaranm/detectindent) (the one [in the official Vim plugin repository](http://www.vim.org/scripts/script.php?script_id=1171)) seems to be abandoned, so this is a fork of [raymond-w-ko’s version](https://github.com/raymond-w-ko/detectindent), which has, among other things, much more robust detection of indentation style. His README said this:

> I merged all the forks that I found were semi-reasonable in the GitHub network graph.
This was done in less than 15 minutes, so expect bugs!

My fork’s additions:

* set 0 for `shiftwidth` and -1 for `softtabstop` when supported, to make it easier for users to manually change indentation
* treat a `g:detectindent_preferred_expandtab` 0 value as signifying a desired default of `noexpandtab`
* slightly better wording of verbose log messages
* various refactorings
* style and formatting fixes in code and documentation

Feel free to submit [pull requests](https://github.com/roryokane/detectindent/pulls) or file [issues](https://github.com/roryokane/detectindent/issues).
