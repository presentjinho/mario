# Browser dependencies

The tutorial uses Kaboom **0.5.0**. `game.js` depends on that API; changing its major version requires a separate gameplay migration.

The script remains at its existing HTTPS URL. Its SHA-384 integrity value was computed from bytes matching `package/dist/kaboom.js` in the npm `kaboom@0.5.0` tarball. The tarball's npm SHA-512 integrity was verified before comparison. The CDN supports anonymous cross-origin requests. A changed or unavailable script will fail closed; do not remove integrity to work around a mismatch.

To review a future update, compare the published package and CDN bytes, verify the package integrity, inspect API compatibility, and then update the script URL and integrity together. Kaboom's upstream repository is archived; this pin is not a claim of ongoing upstream support. Imgur image references remain unchanged and are a separate availability/privacy dependency.
