# Changes for jscc

### v0.3.3 @ 2016-10-23

- Fixes issue with sourceMap generating incorrect output.

### v0.3.2 @ 2016-10-22

- Fixes an issue with losing location in sourceMap after replacing memvars.
- Now JSCC always returns an object, even if there were no changes.
- Updated `devDependencies`.

### v0.3.1 @ 2016-10-14

- Source map includes the source filename (needed by jscc-brunch).
- Removed jscc own source maps from the distribution.
- The CommonJS version is validated by Coverty Scan.

### v0.3.0 @ 2016-10-06

- Initial Release published as v0.3.0 in npm over an old `jscc` tool from Taketoshi Aono.
