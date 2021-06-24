
Change Log
==========================

2.8.0
--------------------------

- Enable reading large piped text.


2.7.4
--------------------------

- Fix an issue where stack trace displayed when using `--wait` option with some clients other than Terminal.app.
- Fix an issue where `--column` could misplace the insertion point when a negative number was given.


2.7.0
--------------------------

- Change `--column` count from 0-based to 1-based.
- Fix an issue where the last empty line was ignoed when specifying the cursor position with `--line` option.
- Improve error message when failed.


2.6.2
--------------------------

- Fix an issue where `cot` command failed to open paths or stdin containing backslash character.


2.6.1
--------------------------

- Fix an issue where `cot` command failed if the client application is non-scriptable.


2.6.0
--------------------------

- Bring the window that called `cot` to the front after `--wait`.


2.5.3
--------------------------

- Avoid creating an extra blank document if `cot` command creates new document.
- Fix an issue where launching application with `--background` option didn't make CotEditor visible.


2.5.2
--------------------------

- Fix a possible hang under some specific environments.


2.5.1
--------------------------

- Fix an issue where file(s) cannot be opened if the default Python is Python 3.


2.5.0
--------------------------

- Enable using wildcard for file path argument.


2.4.1
--------------------------

- Fix an issue where creating new blank file could fail.


2.4.0
--------------------------

- Create a new file if a non-existent file path is passed in with `--new` option.


2.3.1
--------------------------

- Fix an issue where `--line` option didn't work under specific environments.
- Fix an issue where command could failed if the default Python is Python3.
- Fix an issue where `--line` and `--column` options didn't move cursor to the desired location if file has blank lines at the end.


2.3.0
--------------------------

- Add `--wait` (`-w`) option to wait until a newly opened window closes.
- Optimize command performance.
- Fix an issue where command cannot open file whose path includes non-ascii character.


2.2.1
--------------------------

- Open symbolic link target rather than the link itself.
