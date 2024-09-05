[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

# Foundry VTT Theatre of the Mind Manager

This module provides an interface for designing and managing Theatre of the Mind in Foundry VTT.

In play the GM can open the interface and quickly see the available scene transitions. Scene transition commands can be embedded in to journal entries using the `@TOTM` enricher.

A 'scene' can be as simple as a single Foundry Scene, of a sequence of commands to update one or more scenes. This allows the GM to provide synckronised effects on multiple scenes (useful if the party is separated).

This module can be installed as normal in Foundry VTT.

Complete documentation for using this module is provided at [TBD].

## For developers

Fork and clone the repository.

```bash
git clone git@github.com:Mondarth/theatre-of-the-mind.git
cd theatre-of-the-mind
npm install
```

This will set up `git` hooks to ensure commit message integrity and run pre-commit tests.

If you have `docker` installed, you can use the following convenience commands.

| `npm run` Command | Description |
| ------- | ----------- |
| `build:docs` | Rebuild the documentation. |
| `serve:docs` | Run an nginx server on localhost port 8080 to serve the documentation site.<br>Stop the server directly with `docker stop docserver` |

### Other Developer Documentation

The appropriate documentation is produced under `docs/_build/html` by `npm run build:docs`, see above.

The current developer documentation accompanying a module release is at [TBD].
