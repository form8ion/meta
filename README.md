# meta

introduction to the organization and cross-repo issues

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

## Goals of this Organization

The projects under this organization (as well as some yet to be migrated from
[my personal account](https://github.com/travi)) are mostly a codification of
decisions I've made over time around how I prefer projects to be configured and
organized.

This was created to make _my_ life easier, but the tools are configurable for
various contexts. I do have additional configurability in mind for future
evolution, but if making something more configurable would make things easier
for you, please [open an issue](https://github.com/form8ion/meta/issues/new) so
we can discuss. I may be hesitant to accept changes that aren't helpful to me,
but I'm always open to at least discussing.

## Usage

<!-- consumer badges -->
[![MIT license][license-badge]][license-link]

### Project Scaffolding

The project scaffolding tools make it easy to create a new project using the
structure that I've found to work well.

They are intended to be run from your own CLI, so they provide only a
programmatic interface that can be imported into your existing tool. If you
need to create a new CLI tool, you can refer to
[my `commander` instance](https://github.com/travi/cli) or the
[form8ion `yargs` instance](https://github.com/form8ion/utils-cli).
[oclif](https://www.npmjs.com/package/oclif) is also worth considering, but I
personally have not tried that framework yet.

Once you have a CLI available, start with the
[project-scaffolder](https://github.com/travi/project-scaffolder), where you
can [configure](https://github.com/travi/project-scaffolder#options) your
personal or organizational details and include other
[supporting scaffolder plugins](https://github.com/form8ion/awesome#scaffolding).

## Contributing to this Documentation

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![PRs Welcome][PRs-badge]][PRs-link]
[![Greenkeeper badge](https://badges.greenkeeper.io/form8ion/meta.svg)](https://greenkeeper.io/)

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/form8ion/meta.svg
[ci-link]: https://travis-ci.com/form8ion/meta
[ci-badge]: https://img.shields.io/travis/com/form8ion/meta/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
