sublime-dart-linter
===================

An attempt to leverage Dart's analyzer for linting and other nice magic in Sublime Text 3.

## Status

This package doesn't really do anything yet but feel free to jump in and help.

### TODO

- [ ] Find dartanalyzer (check settings for path to Dart SDK)
- [ ] Find the project root & packages directory
- [ ] Spawn subprocess/thread for dartanalyzer
- [ ] Parse the ouput from dartanalyzer (--machine flag might help)
- [ ] Filter issues to those in current file
- [ ] Create a text region for each issue
- [ ] Decorate the regions with gutter-mark or outline
- [ ] Display the corresponding warning/error in statusbar while the cursor is in region

