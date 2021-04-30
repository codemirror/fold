## 0.18.1 (2021-04-30)

### Bug fixes

The fold gutter will now properly update when the editor's language config changes.

Fix an issue where the fold gutter could get out of date when changes below a given line affected the fold marker for that line.

### New features

The package now exports a `foldedRanges` function that can be used to query set of folded ranges in an editor state.

The newly exported `foldEffect` and `unfoldEffect` state effects can be used to control the fold state directly.

## 0.18.0 (2021-03-03)

### Bug fixes

Adds a screen reader announcement when code is folded or unfolded.

## 0.17.1 (2021-01-06)

### New features

The package now also exports a CommonJS module.

## 0.17.0 (2020-12-29)

### Breaking changes

First numbered release.

