# v0.2.6
## Use Object spread instead of Object.assign

There is no change in library behaviour.

# v0.2.5
## Updates dependencies

# v0.2.4
## Adds index.html to deployment URL

GitHub pages, if not root, do not automatically redirect to `index.html`.

# v0.2.3
## Adds trailing slash to deployment URL

GitHub pages sometimes had inconsistent behaviour without it.

# v0.2.2
## Uses passed token to publish to gh-pages

# v0.2.1
## Fixes CLI

Command Line Interface directory (`bin/`) is now included in the published npm package.

# v0.2.0
## Adds Command Line Interface

The main functionality is now exposed as `deploy-directory-on-branch-to-gh-pages` command.

# v0.1.0
## Initial release

This release exposes the main functionality as the default `deploy` function.