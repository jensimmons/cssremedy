# Contributing to CSS Remedy

We'd love to have you contribute to this project.
You can get involved by
[creating or commenting on an issue](https://github.com/mozdevs/cssremedy/issues).

This repository is governed by Mozilla's
code of conduct and etiquette guidelines.
For more details, please read the
[Mozilla Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/).

## Pull Reguests

We're also happy to take pull requests,
both for fixing bugs/typos
and submitting new remedies.
For larger changes,
it's often best to file an issue for discussion first.

### Organization

The code is organized into:

- A core `remedy.css`
  that we recommend using broadly across most projects.
- A secondary `reminders.css`
  with more opinionated or potentially dangerous remedies
  that should be reviewed and considered on a case-by-case basis.
  All reminders are commented out by default.
- Additional specialized remedy files
  (such as `quotes.css`) that can be used as-needed,
  but may not be useful generally.

The `process` folder contains related materials:

- Other resets
- UA stylesheets from various browsers
- An html file to test against

### Documentation

We're using code comments with
[Doxray](https://github.com/himedlooff/doxray)
to automatically generate our online documentation.
Comments start with `/* doxray`,
and use [YAML](https://learnxinyminutes.com/docs/yaml/) structure,
and [Markdown](https://commonmark.org/help/)
for notes.
It looks like this:

```
/* doxray
label: Name The Remedy (required)

note: |
  Indented markdown note can include
  any [links](http://mozilla.org/) and
  *other* `markdown` **syntax** (recommended).

  The vertical bar `|` at the start of the note block
  allows the note to span multiple lines.

links:
  - https://example.com/any-relevant-links-including-github-discussion/
  - (optional)

category: name groups of remedies (required)
*/
```

Every file should start with a file-level
comment that describes the contents of that file,
using `category: file`.
