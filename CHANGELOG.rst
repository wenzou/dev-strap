Changelog
=========

0.4.1 (2015-06-24)
------------------

New
~~~

- _DEBUG flag. [Casey Duquette]

  Setting _DEBUG to "on" before executing will run the script in debug
  mode.

Changes
~~~~~~~

- Update changelog. [Casey Duquette]

- Use absolute paths to Brewfiles. [Casey Duquette]

Fix
~~~

- When shell profile gets modified, reload the current shell. [Casey
  Duquette]

  Some programs required some initialization in the bash profile of a
  user, but subsequent steps might fail unless the user closed the shell
  and reopened it to load the new settings. This change will do the
  reloading after steps that make changes to the login script.

- Added logic to handle special case installing python on osx. [Casey
  Duquette]

  One user on a fresh machine had to specify compiler flags to install
  python or it would complain about openssl libs not being available. I
  think this only affects people who use openssl or want to use the
  openssl from homebrew. I reran it on my computer and it still works
  okay.

0.4 (2015-03-17)
----------------

New
~~~

- Scala. [Casey Duquette]

Fix
~~~

- Changes due to dependency changes. [Casey Duquette]

0.3.2 (2015-03-16)
------------------

Changes
~~~~~~~

- Update changelog. [Casey Duquette]

- Update license file. [Casey Duquette]

Other
~~~~~

- Update osx.sh. [Casey]

  Homebrew installer moved

- Hide the jenv init output. [Casey Duquette]

0.3.1 (2015-03-05)
------------------

- Add error handling if whiptail exists, but is broken. [Casey Duquette]

0.3 (2015-03-05)
----------------

- More brew bundle changes + intellij. [Casey]

- Homebrew deprecated bundle command and added jdk. [Casey]

0.2.1 (2014-07-17)
------------------

Changes
~~~~~~~

- When running the installer, instead of running off current master, use
  the latest release, which is supposedly more stable. [Casey]

0.2 (2014-07-17)
----------------

New
~~~

- Added a new homebrew subcommand called rmtree and updated readme doc
  with a todo list. [Casey]

- Include ssh-copy-id for osx setup. [Casey]

Changes
~~~~~~~

- Changelog. [Casey]

- Changelog. [Casey Duquette]

Fix
~~~

- Pycharm -> pycharm community edition. [Casey]

0.1.1 (2014-07-11)
------------------

Fix
~~~

- Installation command. [Casey Duquette]

- Runability. [Casey Duquette]

- Runability. [Casey Duquette]

- Run script referenced config file before it downloaded. [Casey
  Duquette]

- Forget the logo. [Casey Duquette]

- Logo on readme page was misformatted on github. [Casey Duquette]

0.1 (2014-07-11)
----------------

New
~~~

- Readme added. [Casey Duquette]

- Added support for setting up a .NET development environment in OSX.
  [Casey Duquette]

- Internet explorer vm setup plus some refactoring. [Casey Duquette]

- Welcome screen. [Casey]

Changes
~~~~~~~

- Update changelog. [Casey Duquette]

- Reorg. to support install via curl (e.g. Homebrew) [Casey Duquette]

- Add Codelite IDE and wxwidgets to the list of developer tools to
  install. [Casey Duquette]

- Cleanup. [Casey]

Fix
~~~

- Some fixes after testing. [Casey]


