# CHANGELOG

## 0.3.1
* Fixed bug wherein Exhibitor dearchive reference was incorrect (contributed by
  @benley)

## 0.3.0
* Exhibitor will now explicitly look for dataDir and dataLogDir attributes
  under node[:zookeeper][:config], and prioritize them for calculated values.

## 0.2.1
* Set correct permissions for files Exhibitor needs to run (#7)
* Set correct parameter name for zookeeper-data-directory (#6)

## 0.2.0
* Massive cleanup and minor refactor
* Service now activated in a separate `service` recipe
* Renamed `node[:exhibitor][:defaultconfig]` to `node[:exhibitor][:config]`
* Renamed `node[:exhibitor][:opts]` to `node[:exhibitor][:cli]`
* Added helper library methods
* TODO: Some tests

## 0.1.1
* Cleanup and style fixes. No functional changes.

## 0.1.0
* Initial release of exhibitor, split from zookeeper, contributed by @wolf31o2 
