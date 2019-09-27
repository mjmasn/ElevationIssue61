# React Native Issue \#26289

Issues:

- https://github.com/facebook/react-native/issues/26289
- https://github.com/facebook/react-native/issues/26544
- https://github.com/facebook/react-native/issues/26574

This repo is running React Native 0.61.1

Reproduction steps (this repo is the buggy version):

1. Clone repo
2. Run `yarn`
3. Run `yarn start`
4. Run `react-native run-android` in a separate terminal
5. See that the orange shape is broken (the elevation shadow is displayed on top of the shape instead of below it)

For the working 0.60.6 version, see: https://github.com/mjmasn/ElevationIssue60
