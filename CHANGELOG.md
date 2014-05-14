## v0.2.3:
* Fixed remote file to point at SG repo (so the file is still available)
* Fixed remote file checksum to be correct
* Fixed remote_file resource usage to just use create, let checksum handle
update or not.

## v0.2.2:
__MISSING__

## v0.2.1:
* Fixed `write_graphite` plugin issues when overriding `Host` via attributes.

## v0.2.0:
* Fixed issues with Chef 11 attributes changes.

## v0.1.1:
* Fix FC043.

## v0.1.0:
* Added test-kitchen support.

## v0.0.8:
* Altered remote_file action to :create_if_missing.

## v0.0.7:
* Bump collectd version to 5.1.1.

## v0.0.6:
* Fix for RHEL5 package support for compilation.

## v0.0.5:
* Install libraries for plugins prior to compilation.

## v0.0.4:
* Fixes Foodcritic failures.
* Package installation support.
* RHEL init script support.
* Added a recompilation recipe.

## v0.0.3:
* Added build-essential as a dependency.

## v0.0.2:
* Scoped Graphite auto-discovery to Chef environment.

## v0.0.1:
* Initial release.
