# How to contribute

* [Fork](https://help.github.com/articles/fork-a-repo) the
  [repository on github](https://github.com/bugsnag/bugsnag-cocoa)
* Commit and push until you are happy with your contribution
* Test your changes
* [Make a pull request](https://help.github.com/articles/using-pull-requests)
* Thanks!

## Releasing a new version

1. Update the CHANGELOG with new content
2. Update the version number
   * Bump the version in the homebrew formula URL in `tools/homebrew`
   * Update the version in `VERSION`
   * Update the version in
     `tools/fastlane-plugin/lib/fastlane/plugin/bugsnag/version.rb`
3. Commit your changes
4. Tag the release
5. Push
   * Create a new GitHub release with the changes
   * Update the fastlane-plugin-bugsnag gem
6. Update the documentation as needed on docs.bugsnag.com
