# SQLite Amalgamation Mirror [![Continuous Integration](https://github.com/jameswilddev/sqlite3-amalgamation-mirror/workflows/Full%20Test/badge.svg)] [![Continuous Integration](https://github.com/jameswilddev/sqlite3-amalgamation-mirror/workflows/Commit%20Changes/badge.svg)] [![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)

This is a mirror of the latest sqlite3.c file buildable from [https://github.com/sqlite/sqlite].

Whenever SQLite's source repository updates, Renovate will raise a PR to update this repository's submodule of it.

This will trigger a full test run.

On success, this will be automatically merged into master, where, shortly after, sqlite3.c will be built and committed automatically.

You can then include this repository as a submodule of your own repositories for easy access to sqlite3.c.
