# unreleased

# v0.1.4
* A friendly error is now returned when no argument is given [GH-2](https://github.com/conjurinc/summon-conjur/issues/2)

# v0.1.3
* Config now looks at `netrc_path` in conjurrc to find identity.file

# v0.1.2
* Config now uses env var `CONJUR_AUTHN_API_KEY` instead of `CONJUR_API_KEY`.

# v0.1.1
* Fixed an issue authenticating hosts - `/` is now properly escaped.

# v0.1.0
* Initial release