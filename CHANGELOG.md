# Change Log

## [next]

## [0.8.0] - 2016-05-07

### Added
- Add `zip`, `xml`, `mbstring` and `soap` PHP modules.
- Install `docker-engine` and `docker-compose`.

### Changed
- Raise required Vagrant version to 1.8.
- Use `boxcutter/ubuntu1604` as base-box.
- Optimize package-installation process.
- Update Node.js to version 6.0.x.

### Fixed
- Remove duplicated SERVER_NAME env-variable from Nginx configuration.

### Removed
- Remove some obsolete PPAs.

## [0.7.2] - 2016-02-06

### Changed
- Move installation of services to separate scripts.

### Fixed
- Improve duration of `npm install`.

## [0.7.1] - 2016-01-21

### Added
- Enable HTTP2 for Nginx.

### Changed
- Change default configuration to use Nginx by default.

### Fixed
- Enable Apache headers module.
- Set correct PHP socket path for Apache.

## [0.7.0] - 2015-12-21

### Changed
- Upgrade to PHP 7.0.

### Removed
- Remove port mapping for `live-reload`.

## [0.6.0] - 2015-11-10

### Added
- Add option to constrain the base-box version.
- Add the node-module `localtunnel`.
- Add the node-module `browser-sync`.

### Changed
- Upgrade to Nginx 1.9.
- Upgrade to Node.js 5.
- Upgrade to npm 3.
- Use GraphicsMagick instead of ImageMagick.
- Set utf8mb4 character-set for MySQL.
- Skip development dependencies for the installed node modules.

### Fixed
- Move MySQL configuration to the correct location.

## [0.5.0] - 2015-09-17

### Added
- Add Yeoman node module.
- Add custom fastcgi configuration file for Nginx.

### Changed
- Update base box to Ubuntu 15.04.
- Only pre-configure OPTIONS request in Nginx.
- Change Redis PPA to chris-lea/redis-server.
- Upgrade to Node.js 0.12.

### Removed
- Disable backup routine on Box halt/suspend/destroy.

## [0.4.3] - 2015-05-30

### Fixed
- Fix query-string in Nginx rewrite.
- Fix server-name regexp for hostname matching in Nginx.

### Changed
- Disable buffering to enable streaming for Nginx.

### Added
- Configure basic CORS headers for Nginx.

## [0.4.2] - 2015-03-02

### Fixed
- Allow overriding all Apache directives in .htaccess files.
- Set proper SQL mode for MySQL.

## [0.4.1] - 2015-03-02

### Fixed
- Fix nginx server-name regular expression to successfully match xip.io domains.
- Create MySQL backup directory and check it in to version control.

## [0.4.0] - 2015-02-28

### Added
- Add Apache 2.4 as alternative webserver.
- Configure port mapping for the live-reload server.
- Configure port mapping for the browser-sync server.
- Configure shared folders for hosts configuration.
- Configure custom shared folder mappings.
- Configure custom port forwarding.
- Configure the server's timezone.
- Install NTP daemon.

### Changed
- Rename `hosts` option to `webserver`.
- Upgrade NPM to the latest version on provisioning.

## [0.3.0] - 2015-01-03

### Added
- Add support for the Parallels provider.
- Add MySQL backup routine.
- Add support for DNS loopback/tunnel providers.
- Make the base box configurable.
- Add a license.
- Add a change log.

### Changed
- Replace Chef with shell provisioning.
- Replace Apache with Nginx.
- Change base box to Ubuntu 14.10.
- Raise Vagrant version requirement.
- Lower PHP opcache revalidation frequency.
- Improve loading of settings.yaml.
- Change settings.yaml structure.
- Improve PHP configuration.
- Upgrade Git to version 2.2.

### Removed
- Remove Apache.
- Remove Chef.

## [0.2.2] - 2014-08-13

## [0.2.1] - 2014-08-09

## [0.2.0] - 2014-07-27

## 0.1.0 - 2013-11-11

[next]: https://github.com/thasmo/vagrant.box/compare/v0.8.0...HEAD
[0.8.0]: https://github.com/thasmo/vagrant.box/compare/v0.7.2...v0.8.0
[0.7.2]: https://github.com/thasmo/vagrant.box/compare/v0.7.1...v0.7.2
[0.7.1]: https://github.com/thasmo/vagrant.box/compare/v0.7.0...v0.7.1
[0.7.0]: https://github.com/thasmo/vagrant.box/compare/v0.6.0...v0.7.0
[0.6.0]: https://github.com/thasmo/vagrant.box/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/thasmo/vagrant.box/compare/v0.4.3...v0.5.0
[0.4.3]: https://github.com/thasmo/vagrant.box/compare/v0.4.2...v0.4.3
[0.4.2]: https://github.com/thasmo/vagrant.box/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/thasmo/vagrant.box/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/thasmo/vagrant.box/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/thasmo/vagrant.box/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/thasmo/vagrant.box/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/thasmo/vagrant.box/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/thasmo/vagrant.box/compare/v0.1.0...v0.2.0
