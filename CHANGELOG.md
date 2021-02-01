# Changelog & Release Notes

## UNRELEASED

- [Remedy] New: Proper display handling for `picture` and `source` elements
- [Remedy] New: Add basic `[hidden]` remedy
  to fix unintentional `display` overrides
- [Remedy] Fix: Audio without `[controls]` remains hidden by default

## v0.1.0-beta.2 - 9/18/2019

- [Reminder] Fix: Comment out reminders,
  so that authors have to explicitly opt-in
  case-by-case.
- [Docs] Add inline documentation comments
  (marked with `@docs`)
  using [Doxray](https://github.com/himedlooff/doxray)
  and YAML format.
- [NPM] Exclude irrelevant files from npm releases

## v0.1.0-beta.1 - 9/12/2019

This is an incomplete set of remedies,
and still very likely to change -
but we have to start somewhere.

- Move stylsheets into `css/` directory
- Organize the existing proposed & discussed remedies into three categories:
  - Universally recommended remedies in `remedy.css`
  - Optional remedies worth considering in `reminders.css`
  - Specialized remedies (such as `quotes.css`) in their own files
