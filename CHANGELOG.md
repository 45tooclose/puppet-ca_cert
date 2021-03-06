Changelog
=========

## Unreleased
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v2.0.0...HEAD)

## [v2.0.0](https://github.com/pcfens/puppet-ca_cert/tree/v2.0.0)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.8.0...v2.0.0)

This release has potentially breaking changes

- Move type validation from validate_type to Puppet  data types (removes support for Puppet 3) [\#42](https://github.com/pcfens/puppet-ca_cert/pull/42)


## [v1.8.0](https://github.com/pcfens/puppet-ca_cert/tree/v1.8.0)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.7.1...v1.8.0)

- Don't run enable_ca_trust on RHEL7 [\#37](https://github.com/pcfens/puppet-ca_cert/pull/40)


## [v1.7.1](https://github.com/pcfens/puppet-ca_cert/tree/v1.7.1)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.7.0...v1.7.1)

- Set better default folder permissions [\#37](https://github.com/pcfens/puppet-ca_cert/pull/37)


## [v1.7.0](https://github.com/pcfens/puppet-ca_cert/tree/v1.7.0)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.6.1...v1.7.0)

- CA File modes passed as parameters [\#33](https://github.com/pcfens/puppet-ca_cert/pull/33)
- Use remote_file instead of exec with curl/wget [\#32](https://github.com/pcfens/puppet-ca_cert/pull/32)
- Don't purge managed CAs [\#30](https://github.com/pcfens/puppet-ca_cert/pull/30)


## [v1.6.1](https://github.com/pcfens/puppet-ca_cert/tree/v1.6.0)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.6.0...v1.6.1)

- Handle URLs with special characters [\#24](https://github.com/pcfens/puppet-ca_cert/pull/24)
- Prevent wget from creating empty files when wget fails [\#25](https://github.com/pcfens/puppet-ca_cert/issues/25)

## [v1.6.0](https://github.com/pcfens/puppet-ca_cert/tree/v1.6.0)
[Full Changelog](https://github.com/pcfens/puppet-ca_cert/compare/v1.5.1...v1.6.0)

- Add SLES10 support (exodusftw) [\#22](https://github.com/pcfens/puppet-ca_cert/pull/22)
