fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## increase

### increase firebase_version_code

```sh
[bundle exec] fastlane increase firebase_version_code
```

Responsible for fetching version code from play console and incrementing version code.

----


## Android

### android debug

```sh
[bundle exec] fastlane android debug
```

developement build

### android staging

```sh
[bundle exec] fastlane android staging
```

staging build

### android release

```sh
[bundle exec] fastlane android release
```

release build

### android clean

```sh
[bundle exec] fastlane android clean
```

Clean

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
