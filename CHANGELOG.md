# Change Log


## Unreleased

### Changed

- Use `-t` instead of `-f` to specify an alternative location for the trusted networks file
- Move default trusted unit and trusted network files to `/etc/nmtrust/`. Existing users should simply move their files to upgrade:
```
# mkdir /etc/nmtrust
# mv /usr/local/etc/trusted_units /etc/nmtrust/
# mv /usr/local/etc/trusted_networks /etc/nmtrust/
```

### Fixed

- Properly process network names that contain whitespace

### Added

- Exclude networks by name, e.g. docker networks


## [ 1.0.0 ] - 2018-07-23

- Initial release
