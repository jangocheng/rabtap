# Changelog for rabtap

## unreleased

* rabtap now terminates if the first connection attempt fails, instead
  of retrying to connect. 
* termination behaviour improved
* tesgen tool add a message count to generated messages

## v1.8 (2018-05-06)

### Added

* a changelog ;)
* new `--consumers` option of the `info` command prints also information on
  the connection.
* new command `conn` for connection related operations. Currently allows
  to close a connection with `rabtap conn close <connection-name>`.

### Changed

* minor changes to output of `info` command (i.e. some values are now quoted)


