fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios create_app

```sh
[bundle exec] fastlane ios create_app
```

Create app on Apple Developer and App Store Connect sites

### ios screenshot

```sh
[bundle exec] fastlane ios screenshot
```

Take screenshots

### ios build

```sh
[bundle exec] fastlane ios build
```

Create ipa

### ios upload

```sh
[bundle exec] fastlane ios upload
```

Upload to App Store and submit for review

### ios do_everything

```sh
[bundle exec] fastlane ios do_everything
```

Create app, take screenshots, build and upload to App Store

### ios test

```sh
[bundle exec] fastlane ios test
```

Runs all the tests

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
