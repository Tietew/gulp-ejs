# Changelog

## v4.0.0

This version features a complete rewrite of the plugin to update it's code to modern es6 javascript, which involve some breaking changes.

- Removed settings hash (third argument), consequentially `settings.ext` (setting output file extension) is no longer supported. If you need to rename the ejs files extension please use [gulp-rename](https://npmjs.com/package/gulp-rename).
- Renamed exposed `ejs` object to `__EJS__`

Please check the [README](https://github.com/rogeriopvl/gulp-ejs/blob/master/README.md) file for more info on how  migrate to version 4.

## Previous versions

Please check [The github releases page](https://github.com/rogeriopvl/gulp-ejs/releases) for previous versions changelog.
