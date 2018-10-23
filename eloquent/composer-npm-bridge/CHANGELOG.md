# Composer NPM bridge changelog

## 4.0.1 (2017-09-19)

- **[FIXED]** Fixed "class not found" errors when the plugin is removed by
  Composer ([#5], [#17] - thanks [@garex]).

[#5]: https://github.com/eloquent/composer-npm-bridge/issues/5
[#17]: https://github.com/eloquent/composer-npm-bridge/pull/17
[@garex]: https://github.com/garex

## 4.0.0 (2017-07-12)

- **[BC BREAK]** With the introduction of NPM's [`package-lock.json`], *Composer
  NPM bridge* no longer manages shrinkwrap files.
- **[BC BREAK]** Dropped support for PHP 5.

[`package-lock.json`]: https://docs.npmjs.com/files/package-lock.json

## 3.0.1 (2016-02-22)

- **[FIXED]** Fixed bug where Isolator was unable to be autoloaded ([#11]).

[#11]: https://github.com/eloquent/composer-npm-bridge/issues/11

## 3.0.0 (2016-02-12)

- **[BC BREAK]** Stripped down implementation, many public methods removed.
- **[FIXED]** Updated Composer API version constraint ([#10]).

[#10]: https://github.com/eloquent/composer-npm-bridge/issues/10

## 2.1.1 (2014-09-08)

- **[IMPROVED]** Support for custom installation paths as determined by Composer
  plugins.

## 2.1.0 (2014-02-12)

- **[IMPROVED]** Composer dev/production modes are now honored when installing
  NPM dependencies.
- **[IMPROVED]** Can now be utilized as a dev-only dependency of the root
  package.

## 2.0.0 (2014-01-29)

- **[BC BREAK]** Completely re-written as a Composer plugin.
- **[IMPROVED]** Functions without custom Composer script configuration.

## 1.0.1 (2013-03-04)

- **[NEW]** [Archer] integration.
- **[NEW]** Implemented changelog.

[archer]: https://github.com/IcecaveStudios/archer
